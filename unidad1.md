# 🧠 Unidad 1

---

## 📚 Contenidos:



---

## 1. ¿Qué es la Lógica?
La lógica es una ciencia formal que estudia los principios y métodos que permiten distinguir cuándo un razonamiento es válido y correcto.  
Proviene del griego "logikḗ", relacionado con “razón”, “pensamiento” o “argumento”.  
Su objetivo es analizar cómo se construyen argumentos correctos y evitar errores de razonamiento.

## 2. ¿Qué es la Lógica Matemática?
La lógica matemática es la disciplina que estudia los métodos para razonar correctamente usando símbolos y reglas.  
Permite:
- Determinar si un argumento es válido.
- Demostrar teoremas matemáticos.
- Verificar la corrección de programas y algoritmos.
- Analizar conclusiones en ciencias físicas, naturales, sociales.
- Resolver problemas de forma ordenada en la vida cotidiana.

## 3. Proposiciones Lógicas
Una proposición lógica es un enunciado que puede ser **verdadero (1)** o **falso (0)**, pero no ambos a la vez.  
Ejemplos:
- "El sol es una estrella." → Verdadero  
- "2 + 2 = 5." → Falso  

Las proposiciones se clasifican en:
- **Simples**: no dependen de otras proposiciones.  
- **Compuestas**: se forman usando conectores lógicos.

## 4. Conectores Lógicos
Los conectores permiten unir proposiciones para formar expresiones más complejas.

| Conector | Símbolo | Significado |
|---------|---------|-------------|
| Negación | ¬p | “No p” |
| Conjunción | p ^ q | “p y q” |
| Disyunción | p v q | “p o q” |
| Condicional | p → q | “Si p entonces q” |
| Bicondicional | p ↔ q | “p si y solo si q” |

Ejemplo de proposición compuesta:  
**p v (q ^ ¬r)**

## 5. Tablas de Verdad
Una tabla de verdad muestra todos los posibles valores de verdad de una proposición.  
Sirve para:
- Verificar si una expresión es siempre verdadera (tautología),
- Siempre falsa (contradicción),
- O depende de sus variables (contingencia).

Las tablas permiten analizar cómo se comporta cada conector.

## 6. Inferencia
La inferencia es el proceso de obtener una conclusión a partir de una o más premisas.  
Es fundamental en matemáticas, ciencias y lógica formal.

Ejemplo:
Premisa: “Si estudias, apruebas.”  
Premisa: “Estudias.”  
Conclusión: “Apruebas.”

## 7. Reglas de Inferencia
Las reglas permiten validar si una conclusión se obtiene correctamente de las premisas.  
Las principales son:

- **Modus Ponens** (MP):  
  Si p → q y p es verdadero, entonces q es verdadero.

- **Modus Tollens** (MT):  
  Si p → q y ¬q, entonces ¬p.

- **Silogismo Disyuntivo**:  
  p v q, ¬p → entonces q.

- **Silogismo Hipotético**:  
  Si p → q, y q → r, entonces p → r.

Estas reglas se usan para demostraciones matemáticas y validación de algoritmos.

## 8. Aplicaciones Tecnológicas
La lógica proposicional tiene múltiples usos en computación y electrónica:

- **Contingencias:** se utilizan para construir circuitos de control.
- **Tautologías/Contradicciones:** permiten verificar la consistencia interna de algoritmos.
- **Reglas de inferencia:** sirven como pruebas de corrección en programas.
- **Circuitos lógicos:** utilizan conectores básicos como NOT, AND y OR.
- El análisis lógico es esencial en tecnologías como:
  - Circuitos integrados
  - Sistemas digitales
  - Diseño de compuertas (NAND, NOR, XOR)

## 9. Conjuntos Completos de Conectivas
Un conjunto de conectores es **funcionalmente completo** si permite construir cualquier proposición lógica usando solamente ese conjunto.

Ejemplos:
- { ^ , ¬ }  
- { v , ¬ }  
- También compuertas como NAND o NOR son funcionalmente completas.

Esto permite rediseñar expresiones lógicas usando solo ciertos conectores (importante en electrónica digital).

## 10. Formas Normales
Las proposiciones pueden transformarse en formatos estándar llamados **formas normales**:

### ✔ Forma Normal Disyuntiva (FND)
Una expresión escrita como una disyunción (OR) de conjunciones (AND) de literales.  
Ejemplo:  
(p ^ ¬q) v (q ^ r)

### ✔ Forma Normal Conjuntiva (FNC)
Una expresión escrita como una conjunción (AND) de disyunciones (OR).  
Ejemplo:  
(p v ¬q) ^ (q v r)

Estas formas se usan en:
- Diseño de circuitos
- Álgebra booleana
- Inteligencia artificial (SAT solvers)




### 🔬 1. APE (Aprendizaje Práctico Experimental)

📌 En los trabajos analicé proposiciones simples y compuestas, utilicé conectores lógicos (¬, ∨, ∧, →, ↔), construí **tablas de verdad** para verificar equivalencias y validez lógica y resolví ejercicios aplicando los conceptos fundamentales de la lógica proposicional.

Dentro de este campo, realizamos una actividad:

**📄 APE 1: Resolución de Ejercicios sobre Lógica Proposicional, Conectores y Tablas de Verdad**
* 🔗 Enclace: [APE 1](https://github.com/js-valencia/Matematicas-Discretas/blob/main/Actividades_U1/APE/MatematicasDiscretas_APE1.pdf)

----

###  👨‍🏫 2. ACD (Aprendizaje en Contacto con el Docente)

📌 En estos trabajos estudié y apliqué **leyes proposicionales** como la Ley De Morgan, idempotencia, doble negación, etc; practiqué **reglas de inferencia** como Modus Ponens, Modus Tollens, Silogismo, etc, además de resolver ejercicios aplicando razonamiento lógico paso a paso y analicé ejemplos y realicé ejercicios para crear **tablas de verdad correctamente**.

Dentro de este campo realizamos dos actividades:

**📄 ACD1: Lógica Proposicional, Conectores y Tablas de Verdad**
* 🔗 Enlace: [ADC 1](https://github.com/js-valencia/Matematicas-Discretas/blob/main/Actividades_U1/ACD/Presentación%201-%20NeoCore.pptx.pdf)

**📄 ACD 2: Implicaciones, Equivalencias y Razonamiento Deductivo (Leyes Proposicionales y Reglas de Inferencia)**
* 🔗 Enlace: [ACD 2](https://github.com/js-valencia/Matematicas-Discretas/blob/main/Actividades_U1/ACD/Leyes%20de%20las%20Proposiciones%20y%20Relgas%20de%20Inferencia.pdf)

  ----

### 📙 3. AA (Aprendizaje Autonomo)

📌 En estos trabajos investigué sobre **leyes de las proposiciones** y **reglas de inferencia**, resolví ejercicios para reforzar la comprensión y analicé equivalencias proposicionales aplicando las leyes paso a paso.

Dentro de este campo, realizamos dos actividades:

**📄 AA 1: Lectura de Ejercicios de Leyes de las Proposiciones y las Leyes de Inferencia**
* 🔗 Enlace: [AA 1](https://github.com/js-valencia/Matematicas-Discretas/blob/main/Actividades_U1/AA/Matemáticas%20Discretas%20AA_Lectura%20y%20Ejercicios.pdf)

**📄 AA 2: Portafolio Digital**
* 🔗 Enlace: [AA 2 (Este trabajo)](https://github.com/js-valencia/Matematicas-Discretas/blob/main/index.md)

----
