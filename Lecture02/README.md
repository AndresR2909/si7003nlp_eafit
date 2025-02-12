# SI7003 NLP lecture02


Para calcular las probabilidades \( P(\theta_1 \mid \text{"computer"}) \) y \( P(\theta_2 \mid \text{"computer"}) \), utilizamos el teorema de Bayes:

\[
P(\theta_i \mid w) = \frac{P(w \mid \theta_i) P(\theta_i)}{P(w)}
\]

Donde:

- \( P(w \mid \theta_i) \) es la probabilidad de observar la palabra dado el modelo \( \theta_i \).
- \( P(\theta_i) \) es la probabilidad a priori del modelo \( \theta_i \).
- \( P(w) \) es la probabilidad total de la palabra.

### Suposiciones
Asumimos que \( P(\theta_1) = P(\theta_2) = 0.5 \).

### 1. Probabilidades de la palabra bajo cada modelo
- \( P(\text{"computer"} \mid \theta_1) = 0.1 \)
- \( P(\text{"computer"} \mid \theta_2) = 0.4 \)

### 2. Cálculo de \( P(w) \)
\[
P(w) = P(w \mid \theta_1) P(\theta_1) + P(w \mid \theta_2) P(\theta_2)
\]
Sustituyendo los valores:
\[
P(w) = (0.1)(0.5) + (0.4)(0.5) = 0.05 + 0.2 = 0.25
\]

### 3. Aplicación del teorema de Bayes
\[
P(\theta_1 \mid \text{"computer"}) = \frac{P(\text{"computer"} \mid \theta_1) P(\theta_1)}{P(w)} = \frac{0.1 \cdot 0.5}{0.25} = \frac{0.05}{0.25} = 0.2
\]

\[
P(\theta_2 \mid \text{"computer"}) = \frac{P(\text{"computer"} \mid \theta_2) P(\theta_2)}{P(w)} = \frac{0.4 \cdot 0.5}{0.25} = \frac{0.2}{0.25} = 0.8
\]

### Resultados
- \( P(\theta_1 \mid \text{"computer"}) = 0.2 \)
- \( P(\theta_2 \mid \text{"computer"}) = 0.8 \)

La respuesta correcta es \( 0.2 \) y \( 0.8 \).

