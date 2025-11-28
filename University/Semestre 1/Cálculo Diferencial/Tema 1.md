## 1. 📌 Una función es una regla que asigna un único valor de salida a cada valor de entrada

**Afirmación clave:**  
Una **función** es una regla matemática que asigna **exactamente un elemento de un conjunto** a **exactamente un elemento de otro conjunto**.
### 🔹 Ideas clave:
- Toda función cumple la regla: **un solo resultado por cada entrada**.
- Se representa generalmente con letras como:  
    **f, g, h**
- Forma general de escritura:
    - $f(x)$
    - $y = f(x)$

### 🧠 Recordatorio conceptual:

- No puede haber dos salidas distintas para una misma entrada.
- La función es una relación **bien definida**, no cualquier relación.

---
## 2. 📌 En una función existen variable independiente y variable dependiente

**Afirmación clave:**  
En toda función hay una **variable independiente** que se elige libremente y una **variable dependiente** que resulta del valor de la función.

### 🔹 Ideas clave:

- **Variable independiente:**
    - Generalmente representada por **x** o **n**
    - Es el valor que se introduce en la función.
- **Variable dependiente:**
    - Generalmente representada por **f(x)** o **y**
    - Depende del valor de la variable independiente.

### ✅ Ejemplo visual:

- Si $f(x) = x^2$:
    - x = variable independiente
    - f(x) = variable dependiente

---

## 3. 📌 Existen diferentes tipos de funciones según su forma matemática

**Afirmación clave:**  
Las funciones se clasifican según la forma de su expresión algebraica, lo cual determina su comportamiento.

### 📊 Tipos de funciones importantes:

| Tipo de función        | Expresión         | Característica principal    |
| ---------------------- | ----------------- | --------------------------- |
| **Constante**          | $f(n) = 1$        | No cambia                   |
| **Logarítmica**        | $f(n) = \log n$   | Crecimiento lento           |
| **Lineal**             | $f(n) = n$        | Crecimiento proporcional    |
| **Lineal-logarítmica** | $f(n) = n \log n$ | Crece más rápido que lineal |
| **Cuadrática**         | $f(n) = n^2$      | Crecimiento acelerado       |
| **Polinómica**         | $f(n) = n^k$      | Depende del grado k         |
| **Exponencial**        | $f(n) = 2^n$      | Crecimiento muy rápido      |
| **Factorial**          | $f(n) = n!$       | Crecimiento extremado       |

### 📝 Nota importante:

- Si el exponente de la variable independiente es **1**, la función es **lineal**:    
    - $f(x) = x$

---
## 4. 📌 Existen funciones especiales usadas en matemática e inteligencia artificial

**Afirmación clave:**  
Algunas funciones no se clasifican solo por potencias, sino por su **comportamiento específico**, especialmente en IA.

---
### 🔹 Función Sigmoide
$$
\sigma(x) = \frac{1}{1 + e^{-x}}
$$
- Produce valores entre **0 y 1**
- Muy usada en:
    - Redes neuronales
    - Probabilidades
- Tiene forma de **S**
---
### 🔹 Función Hiperbólica (Tanh)
$$
f(x) = \tanh(x) = \frac{e^x - e^{-x}}{e^x + e^{-x}}  
$$
- Produce valores entre **-1 y 1**
- Similar a la sigmoide, pero centrada en 0
- Se usa en:
    - Redes neuronales
    - Procesamiento de señales
---
### 🔹 Función ReLU (Rectified Linear Unit)
$$
f(x) =  
\begin{cases}  
0, & x < 0 \  
x, & x \ge 0  
\end{cases}  
$$
- Si el número es negativo → salida = 0
- Si es positivo → se deja igual
- Muy usada en **deep learning**
- Es rápida computacionalmente
- Evita el problema del desvanecimiento del gradiente

---

## 5. 📌 Un límite describe el comportamiento de una función cuando se acerca a un valor
**Afirmación clave:**  
Un **límite** indica lo que ocurre con una función cuando la variable se **aproxima** a un determinado valor.
### 🔹 Ideas clave:
- No se evalúa necesariamente en el punto.
- Se analiza qué valor **tiende a tomar la función**.
- Forma conceptual:
    - “¿Qué pasa con f(x) cuando x se acerca a a?”

---
## 6. 📌 Los polinomios son funciones formadas por sumas de potencias de una variable

**Afirmación clave:**  
Un **polinomio** es una función formada por la suma de términos con potencias enteras positivas de una variable.
### 🔹 Forma general de un polinomio:
$$
a_1x^n + a_2x^{n-1} + \dots + a_nx  
$$
### 🔹 Componentes:
- $a_1, a_2, \dots, a_n$ → coeficientes
- $x$ → variable
- $n$ → grado del polinomio

---
## 7. 📌 Los ejemplos permiten comprender mejor el comportamiento de funciones y límites

**Afirmación clave:**  
Los ejemplos son esenciales para visualizar cómo se comportan las funciones y los límites en casos reales.

- Ejemplo referenciado:  
    **[[Ejemplo Tema 1]]**
- Sirven para:
    - Ver cómo varía f(x)
    - Interpretar el concepto de límite gráficamente
    - Confirmar resultados teóricos
---
# ✅ SÍNTESIS FINAL – IDEAS CLAVE DEL APUNTE

- Una **función** asigna un único valor de salida a cada valor de entrada.
- Las funciones se representan con **f, g o h**.
- Toda función tiene:
    - Variable independiente
    - Variable dependiente
- Existen **muchos tipos de funciones**: constante, lineal, cuadrática, exponencial, factorial, etc.
- Si el exponente de la variable es **1**, la función es **lineal**.
- Las **funciones especiales** como:
    - Sigmoide
    - Tanh
    - ReLU  
        son claves en inteligencia artificial.
- Un **límite** describe qué ocurre con una función cuando la variable **se acerca a un 
- Un **polinomio** es una suma de potencias de una variable.
- Los **ejemplos** permiten comprender el comportamiento real de las funciones.
---