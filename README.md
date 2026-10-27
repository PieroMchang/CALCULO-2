# GUÍA INTEGRAL DE PREPARACIÓN PARA EL EXAMEN DE LA UNIDAD 2
## Curso: Cálculo II (1AMA0706 / 1AMA0263) — Universidad Peruana de Ciencias Aplicadas (UPC)

---

## SECCIÓN A. PORTADA, ORIENTACIÓN Y DIAGNÓSTICO DE MATERIALES

### A.1. Ficha Técnica de la Evaluación
* **Curso:** Cálculo II (`1AMA0706` / `1AMA0263`)
* **Evaluación:** Evaluación de la Unidad 2 (EU2) / Control 2 (CNT2)
* **Duración oficial:** $100\text{ minutos}$
* **Puntaje total:** $20\text{ puntos}$ divididos en dos partes:
  * **Parte 1 (Objetiva y de Completación — $15\text{ puntos}$):** Consta de $4\text{ preguntas}$ divididas en sub-ítems (`i`, `ii`, `iii` o `a`, `b`, `c`, `d`). Se califica bajo el **criterio todo o nada** ($0\text{ puntos}$ si no colocas el procedimiento o evidencia en la columna derecha, aunque marques o escribas la respuesta correcta a la izquierda).
  * **Parte 2 (Pregunta de Desarrollo / Modelación — $5\text{ puntos}$):** Consta de $1\text{ problema contextualizado}$ sobre un tanque industrial, tolva, balón de gas o sartén (formado por cilindros, semiconos, paraboloides o casquetes esféricos), donde debes hallar las ecuaciones de las superficies ($1\text{ pto}$), graficar la proyección y describir el sólido ordenadamente en coordenadas cilíndricas ($2\text{ ptos}$), y plantear/calcular el volumen ($2\text{ ptos}$).
* **Herramientas permitidas:** Calculadora científica estándar (no graficadora ni programable) y el Formulario Oficial impreso en la última hoja del examen.

### A.2. Objetivo del Material
Este documento es un **manual de aprendizaje autónomo desde cero**. Su propósito no es que memorices plantillas de resolución, sino que comprendas la geometría y la lógica detrás de cada integral doble y triple para que puedas:
1. Traducir cualquier región plana o sólida a desigualdades matemáticas sin equivocarte en los límites.
2. Elegir con seguridad entre coordenadas cartesianas, polares, cilíndricas o esféricas.
3. Resolver de forma independiente todo el banco de preguntas ($27\text{ problemas}$ tipo) y enfrentar cualquier variación en el examen real.

---

### A.3. Índice General de la Guía
* **SECCIÓN A.** Portada, Orientación, Ruta de Aprendizaje y Auditoría de Archivos
* **SECCIÓN B.** Fundamentos y Conocimientos Previos Indispensables (Desde Cero)
  * B.1. Trigonometría de supervivencia y ángulos notables
  * B.2. Álgebra geométrica: Completación de cuadrados y despejes con signos por cuadrante
  * B.3. El Diccionario Maestro de Distancias y Funciones de Densidad ($\delta$)
  * B.4. Catálogo visual y analítico de curvas en $\mathbb{R}^2$ y superficies cuádricas en $\mathbb{R}^3$
* **SECCIÓN C.** Desarrollo Teórico Completo por Temas (Estructura de 7 pasos)
  * **Tema 1:** Integrales Dobles en Coordenadas Cartesianas, Teorema de Fubini y Cambio de Orden de Integración
  * **Tema 2:** Integrales Dobles en Coordenadas Polares (Circunferencias, Cardioides e Intersecciones)
  * **Tema 3:** Aplicaciones de la Integral Doble (Área de Regiones Planas y Masa de Placas Delgadas)
  * **Tema 4:** Integrales Triples en Coordenadas Cartesianas y Proyecciones sobre los Planos $xy$, $xz$ e $yz$
  * **Tema 5:** Integrales Triples en Coordenadas Cilíndricas y Modelación de Tanques Reales
  * **Tema 6:** Integrales Triples en Coordenadas Esféricas (Esferas, Semiconos y Planos)
* **SECCIÓN D.** Ejemplos Completamente Resueltos Paso a Paso (Metodología de 9 pasos)
* **SECCIÓN E.** Atlas de Diagramas Explicativos, Árboles de Decisión y Gráficos Técnicos
* **SECCIÓN F.** Ejercicios de Entrenamiento Autónomo por Niveles (Niveles 1, 2 y 3 + Solucionario Desarrollado)
* **SECCIÓN G.** Preparación Específica para el Banco de Preguntas (Trazabilidad y Corrección de Errores del PDF de Repaso)
* **SECCIÓN H.** Simulacro Integral de Examen EU2 (Formato Oficial $100\text{ min}$ + Solucionario Calificado)
* **SECCIÓN I.** Resumen Final de Alto Rendimiento (Formulario Comentado, Errores Frecuentes y Checklist)

---

### A.4. Ruta de Aprendizaje Recomendada (Plan de Estudio Eficiente)
Si cuentas con poco tiempo antes del examen, sigue estrictamente este orden de estudio:

$$\text{Paso 1: Fundamentos (Sección B)} \implies \text{Paso 2: Dobles y Cambio de Orden (Temas 1 a 3)}$$
$$\implies \text{Paso 3: Triples en Esféricas y Cartesianas (Temas 4 y 6)} \implies \text{Paso 4: Cilíndricas y Modelación de Tanques (Tema 5)}$$
$$\implies \text{Paso 5: Auditoría del Banco y Práctica (Secciones F y G)} \implies \text{Paso 6: Simulacro Cronometrado (Sección H)}$$

> **Prioridad Estratégica según los Exámenes Pasados:**
> En el $100\%$ de los exámenes revisados (`2025-10 V1`, `2025-10 V2` y `2026-10`) aparecen siempre **cinco bloques fijos**:
> 1. **Un problema de coordenadas polares** (área y masa entre circunferencia y cardioide o entre dos circunferencias): **$3.75\text{ a } 4\text{ puntos}$**.
> 2. **Un problema de integrales dobles en cartesianas** (cambio de orden de integración o descripción de región entre parábola y recta): **$3.75\text{ a } 4\text{ puntos}$**.
> 3. **Un problema de coordenadas esféricas en el primer octante** (esfera cortada por planos radiales o semicono, más densidad y masa): **$3.75\text{ a } 4\text{ puntos}$**.
> 4. **Un problema de coordenadas cilíndricas o cartesianas 3D** (sólido entre cono/paraboloide o cilindro parabólico proyectado en $xz$ o $yz$): **$3\text{ a } 3.75\text{ puntos}$**.
> 5. **La pregunta de desarrollo (Parte 2)** sobre un **tanque o tolva en coordenadas cilíndricas**: **$5\text{ puntos}$**.

---

### A.5. Lista de Habilidades Oficiales (Matriz EU2) que Dominarás al Terminar
Al finalizar esta guía serás capaz de cumplir cada indicador de la Matriz de Habilidades oficial:
* **[H1 - Conceptos 2D]:** Describir analíticamente regiones del plano usando coordenadas cartesianas (Tipo I y Tipo II) o coordenadas polares $(r; \theta)$, y aplicar el Teorema de Fubini.
* **[H2 - Cálculo 2D]:** Calcular integrales dobles invirtiendo el orden de integración ($dy\,dx \leftrightarrow dx\,dy$) y transformando a coordenadas polares con el jacobiano $r$.
* **[H3 - Graficación 2D y 3D]:** Graficar regiones planas acotadas por curvas y regiones del espacio limitadas por planos, cilindros (circulares o parabólicos) y superficies cuádricas completas (esferas, paraboloides, semiconos).
* **[H4 - Aplicación 2D]:** Calcular el área $A(D)$ y la masa $m(D)$ de una placa plana delgada interpretando verbalmente la función de densidad $\delta(x; y)$.
* **[H5 - Conceptos 3D]:** Describir sólidos en el espacio mediante conjuntos ordenados en coordenadas cartesianas $(x; y; z)$, cilíndricas $(r; \theta; z)$ o esféricas $(\rho; \theta; \phi)$.
* **[H6 - Cálculo 3D]:** Seleccionar el sistema de coordenadas más apropiado y evaluar integrales triples iteradas incluyendo el jacobiano respectivo ($1$, $r$ o $\rho^2\sin\phi$).
* **[H7 - Aplicación y Modelación 3D]:** Modelar tanques y estructuras reales hallando las constantes de sus ecuaciones a partir de cotas geométricas, y calcular el volumen $V(E)$ y la masa $m(E)$ de sólidos.

---

### A.6. Advertencia de Calidad: Errores Detectados en los Archivos que Compartiste
Como parte del análisis riguroso de tus materiales, he detectado **errores importantes en las soluciones manuscritas de los alumnos** dentro de los PDFs que subiste. **¡Ten mucho cuidado de no estudiar esos errores!** Aquí tienes el resumen ejecutivo (los analizaremos a fondo en la Sección G):
1. **En el Examen 2026-10 (nota 09/20):**
   * En la Pregunta 1.ii y 2.b, el estudiante confundió **«distancia al eje $z$»** ($\sqrt{x^2+y^2}$) y **«distancia al eje $x$»** ($|y|$) con la distancia al origen ($\sqrt{x^2+y^2+z^2}$).
   * En la Pregunta 3.b, para hallar la intersección entre $r = 3$ y $r = 2 + 2\sin\theta$, escribió erróneamente $\tan\theta = 3/3 \Rightarrow \theta = \pi/4$, cuando lo correcto es igualar radios: $2 + 2\sin\theta = 3 \Rightarrow \sin\theta = 1/2 \Rightarrow \theta = \pi/6$.
   * En la Pregunta 5.a, escribió la ecuación del cilindro de diámetro $3\text{ m}$ (radio $1.5\text{ m}$) como $x^2+y^2 = 5$ (usó la altura total en vez del radio al cuadrado $1.5^2 = 2.25$).
2. **En el PDF `Resueltos EU2 - Guía de repaso`:**
   * **Ejercicios $6\text{k}$ y $6\text{l}$ (págs. 12 y 13):** La región está en el **segundo cuadrante** ($x \le 0$), pero al despejar $x$ de $x^2 = 4(25-y)$ y $x^2 = 9(4-y)$, el autor del cuaderno tomó la raíz positiva $+\sqrt{\dots}$ en vez de la raíz negativa $-\sqrt{\dots}$. ¡Eso invirtió los límites de integración!
   * **Ejercicio $14$ (pág. 24):** Al plantear $\iiint_E z(x^2+y^2)\,dV$ en cilíndricas, el autor reemplazó la $z$ del integrando por la ecuación de la frontera $\sqrt{2}r$. **¡Error conceptual grave!** En coordenadas cilíndricas, $z$ sigue siendo la variable $z$; solo se reemplaza en los límites de integración, nunca dentro del integrando antes de integrar respecto a $z$.
   * **Ejercicio $19$ (pág. 26):** Al integrar respecto a $\theta$, el autor integró $\sin\phi$ como si dependiera de $\theta$, obteniendo un resultado incorrecto.
   * **Ejercicio $25$ (pág. 31, balón Solgas):** El autor invirtió los signos de las raíces en los límites de $z$ de los casquetes esféricos: puso $221 + \sqrt{221^2-r^2} \le z \le 854 - \sqrt{221^2-r^2}$, cuando el casquete inferior abre hacia abajo ($221 - \sqrt{221^2-r^2}$) y el superior abre hacia arriba ($854 + \sqrt{221^2-r^2}$).

---

## SECCIÓN B. FUNDAMENTOS Y CONOCIMIENTOS PREVIOS (DESDE CERO)

Antes de tocar una sola integral múltiple, necesitamos construir los cuatro pilares matemáticos que sostienen toda la Unidad 2. Si fallas en el examen, el $90\%$ de las veces no es por no saber integrar, sino por fallar en uno de estos cuatro fundamentos.

---

### B.1. Trigonometría Esencial y Ángulos Notables en Radianes

#### ¿Qué es y para qué sirve?
En coordenadas polares, cilíndricas y esféricas, las regiones se barren mediante ángulos ($\theta$ y $\phi$) medidos siempre en **radianes**, nunca en grados sexagesimales. Necesitas pasar de ecuaciones como $\tan\theta = \sqrt{3}$ o $\sin\theta = \frac{1}{2}$ al ángulo en radianes de forma instantánea.

#### Tabla Maestra de Ángulos Notables (Primer Cuadrante)

| Grados | Radianes | $\sin(\text{ángulo})$ | $\cos(\text{ángulo})$ | $\tan(\text{ángulo}) = \frac{\sin}{\cos}$ | ¿Cómo aparece en el examen UPC? |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $0^\circ$ | $0$ | $0$ | $1$ | $0$ | Semieje positivo $x$ ($y=0, x>0$) o semieje positivo $z$ ($\phi=0$) |
| $30^\circ$ | $\frac{\pi}{6}$ | $\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{3}} = \frac{\sqrt{3}}{3}$ | Recta $y = \frac{1}{\sqrt{3}}x$ o semicono $z = \sqrt{3x^2+3y^2}$ |
| $45^\circ$ | $\frac{\pi}{4}$ | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | $1$ | Recta bisectriz $y = x$ o semicono $z = \sqrt{x^2+y^2}$ |
| $60^\circ$ | $\frac{\pi}{3}$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $\sqrt{3}$ | Recta $y = \sqrt{3}x$ o semicono $z = \sqrt{\frac{x^2+y^2}{3}}$ |
| $90^\circ$ | $\frac{\pi}{2}$ | $1$ | $0$ | No definido ($\to \infty$) | Semieje positivo $y$ ($x=0, y>0$) o plano $xy$ ($\phi=\frac{\pi}{2}$) |

#### ¿Cómo hallar ángulos en otros cuadrantes cuando intersectas curvas polares?
En los problemas de cardioides y circunferencias (como la Pregunta 3 del examen 2026-10 o el Ejercicio 8 del banco), suelen aparecer dos puntos de intersección simétricos:
* **Caso 1: Simetría respecto al eje $y$ (curvas con $\sin\theta$, como $r = 2 + 2\sin\theta$).**
  Si en el primer cuadrante obtienes $\sin\theta = \frac{1}{2} \Rightarrow \theta_1 = \frac{\pi}{6}$, el segundo punto de intersección está en el **segundo cuadrante** y se calcula restando a $\pi$:
  $$\theta_2 = \pi - \theta_1 = \pi - \frac{\pi}{6} = \frac{5\pi}{6}$$
  Por lo tanto, el barrido angular superior es $\frac{\pi}{6} \le \theta \le \frac{5\pi}{6}$.
* **Caso 2: Simetría respecto al eje $x$ (curvas con $\cos\theta$, como $r = 2 + 2\cos\theta$).**
  Si en el primer cuadrante obtienes $\cos\theta = \frac{1}{2} \Rightarrow \theta = \frac{\pi}{3}$, la región que cruza el semieje positivo $x$ se barre desde el **cuarto cuadrante** (usando ángulo negativo $-\theta_1$) hasta el **primer cuadrante** ($+\theta_1$):
  $$-\frac{\pi}{3} \le \theta \le \frac{\pi}{3}$$
  *(¡Cuidado!: Nunca escribas $\frac{5\pi}{3} \le \theta \le \frac{\pi}{3}$ porque $\frac{5\pi}{3} > \frac{\pi}{3}$ y el límite inferior siempre debe ser menor que el superior).*

---

### B.2. Despeje de Ecuaciones y la Trampa del Signo en las Raíces Cuadradas

#### El principio fundamental
Cuando despejas una variable elevada al cuadrado, por ejemplo $x^2 = 9 - y$, existen **dos ramas**:
$$x^2 = 9 - y \iff x = +\sqrt{9-y} \quad \text{o} \quad x = -\sqrt{9-y}$$
* Si el problema o la gráfica se encuentra a la **derecha del eje $y$** (Primer o Cuarto Cuadrante, donde $x \ge 0$), debes usar $x = +\sqrt{9-y}$.
* Si el problema o la gráfica se encuentra a la **izquierda del eje $y$** (Segundo o Tercer Cuadrante, donde $x \le 0$), **debes usar obligatoriamente $x = -\sqrt{9-y}$**.

#### Ejemplo sencillo vs. Ejemplo de examen
* **Sencillo:** En $\int_0^3 \int_0^{\sqrt{9-x^2}} dy\,dx$, como $0 \le x \le 3$ y $0 \le y \le \sqrt{9-x^2}$, estamos en el Primer Cuadrante ($x \ge 0, y \ge 0$). Al despejar $x$ de $y = \sqrt{9-x^2} \Rightarrow x^2 = 9-y^2 \Rightarrow x = +\sqrt{9-y^2}$.
* **Nivel Examen (Ejercicio $6\text{l}$ de la Guía de Repaso):**
  Dada $\int_{-3\sqrt{2}}^0 \int_2^{4-x^2/9} \frac{y}{2+e^y}\,dy\,dx$, observa los límites de $x$: $-3\sqrt{2} \le x \le 0$. ¡Esto significa que $x$ es **negativo** (Segundo Cuadrante)!
  Al despejar $x$ de la parábola $y = 4 - \frac{x^2}{9}$:
  $$\frac{x^2}{9} = 4 - y \implies x^2 = 9(4-y) \implies x = -\sqrt{9(4-y)} = -3\sqrt{4-y}$$
  Como $x$ va desde la curva izquierda ($x = -3\sqrt{4-y}$) hasta el eje $y$ ($x = 0$), el nuevo límite al invertir el orden es $-3\sqrt{4-y} \le x \le 0$.

---

### B.3. El Diccionario Maestro de Distancias y Funciones de Densidad ($\delta$ o $\rho$)

En **todos** los exámenes de la UPC te pedirán hallar la función de densidad $\delta(x; y)$ o $\delta(x; y; z)$ a partir de un enunciado verbal que relaciona la densidad con una **distancia**.
* Si el texto dice **«es numéricamente igual a...»**, el factor es $1$ (o el número que indique: «al doble» $\to 2$, «a la mitad» $\to \frac{1}{2}$, «a la tercera parte» $\to \frac{1}{3}$).
* Si el texto dice **«es directamente proporcional a...»**, debes multiplicar por una constante $k$: $\delta = k \cdot (\text{distancia})$.

#### Tabla Definitiva de Distancias en 2D (Plano $xy$) y 3D (Espacio $xyz$)

| Enunciado en el Examen («...distancia del punto al...») | Fórmula Exacta en Cartesianas | Equivalente en Polares / Cilíndricas | Equivalente en Esféricas | ¿Por qué funciona así? (Intuición geométrica) |
| :--- | :--- | :--- | :--- | :--- |
| **En 2D:** Al **origen** $(0;0)$ | $\sqrt{x^2 + y^2}$ | $r$ | — | Teorema de Pitágoras desde $(0;0)$ hasta $(x;y)$. |
| **En 2D:** Al **eje $x$** | $|y|$ *(en el 1er/2do cuadrante: $y$)* | $r\sin\theta$ | — | Para ir de $(x;y)$ al eje $x$, bajas verticalmente una altura $y$. |
| **En 2D:** Al **eje $y$** | $|x|$ *(en el 1er/4to cuadrante: $x$)* | $r\cos\theta$ | — | Para ir de $(x;y)$ al eje $y$, te mueves horizontalmente una distancia $x$. |
| **En 3D:** Al **origen** $(0;0;0)$ | $\sqrt{x^2 + y^2 + z^2}$ | $\sqrt{r^2 + z^2}$ | $\rho$ | Distancia radial en tres dimensiones desde $(0;0;0)$. |
| **En 3D:** Al **plano $xy$** ($z=0$) | $|z|$ *(en el 1er octante: $z$)* | $z$ | $\rho\cos\phi$ | Altura vertical que separa al punto del piso ($z=0$). |
| **En 3D:** Al **plano $xz$** ($y=0$) | $|y|$ *(en el 1er octante: $y$)* | $r\sin\theta$ | $\rho\sin\phi\sin\theta$ | Distancia perpendicular hacia la pared lateral $y=0$. |
| **En 3D:** Al **plano $yz$** ($x=0$) | $|x|$ *(en el 1er octante: $x$)* | $r\cos\theta$ | $\rho\sin\phi\cos\theta$ | Distancia perpendicular hacia la pared del fondo $x=0$. |
| **En 3D:** Al **eje $z$** | $\sqrt{x^2 + y^2}$ | $r$ | $\rho\sin\phi$ | En el eje $z$, $x=0$ e $y=0$; faltan las componentes $x$ e $y$. |
| **En 3D:** Al **eje $x$** | $\sqrt{y^2 + z^2}$ | — | — | Faltan las componentes que no son $x$: raíz de $y^2+z^2$. |
| **En 3D:** Al **eje $y$** | $\sqrt{x^2 + z^2}$ | — | — | Faltan las componentes que no son $y$: raíz de $x^2+z^2$. |

> **Regla Mnemotécnica Infalible del Profesor:**
> * **Distancia a un PLANO o EJE en 2D:** Tiene **UNA** sola letra sin raíz (la letra que **NO** está en el nombre del plano o eje). Ejemplo: Distancia al plano $xz \implies$ falta la $y \implies d = |y|$. Distancia al plano $yz \implies$ falta la $x \implies d = |x|$.
> * **Distancia a un EJE en 3D:** Tiene **DOS** letras dentro de una raíz cuadrada (las dos letras que **NO** están en el nombre del eje). Ejemplo: Distancia al eje $z \implies$ faltan $x, y \implies d = \sqrt{x^2+y^2}$.
> * **Distancia al ORIGEN en 3D:** Tiene las **TRES** letras dentro de la raíz: $d = \sqrt{x^2+y^2+z^2}$.

---

### B.4. Catálogo de Curvas en $\mathbb{R}^2$ y Superficies Cuádricas en $\mathbb{R}^3$

#### 1. Circunferencias centradas y desplazadas en $\mathbb{R}^2$
En coordenadas polares ($x = r\cos\theta$, $y = r\sin\theta$, $x^2+y^2 = r^2$), existen tres tipos de circunferencias que aparecen constantemente:
* **Centrada en el origen:** $x^2 + y^2 = a^2 \iff r = a$. (Ejemplo: $x^2+y^2 = 9 \iff r = 3$).
* **Desplazada sobre el eje $x$:** $x^2 + y^2 = 2ax \iff (x-a)^2 + y^2 = a^2$ (centro en $(a; 0)$ y radio $a$).
  En polares: $r^2 = 2a(r\cos\theta) \iff r = 2a\cos\theta$. (Barrido completo en el semiplano derecho: $-\frac{\pi}{2} \le \theta \le \frac{\pi}{2}$).
* **Desplazada sobre el eje $y$:** $x^2 + y^2 = 2ay \iff x^2 + (y-a)^2 = a^2$ (centro en $(0; a)$ y radio $a$).
  En polares: $r^2 = 2a(r\sin\theta) \iff r = 2a\sin\theta$. (Barrido completo en el semiplano superior: $0 \le \theta \le \pi$).

#### 2. Cardioides en Coordenadas Polares
Un cardioide tiene forma de corazón y su ecuación es de la forma:
$$r = a \pm b\cos\theta \quad \text{o} \quad r = a \pm b\sin\theta$$
* $r = a + a\cos\theta$: Abre hacia la **derecha** (semieje $+x$).
* $r = a - a\cos\theta$: Abre hacia la **izquierda** (semieje $-x$).
* $r = a + a\sin\theta$: Abre hacia **arriba** (semieje $+y$).
* $r = a - a\sin\theta$: Abre hacia **abajo** (semieje $-y$).

#### 3. Superficies Cuádricas Completas e Incompletas (Cilindros) en $\mathbb{R}^3$

| Nombre de la Superficie | Ecuación Cartesiana Típica | ¿Cómo reconocerla rápido? | Ecuación en Cilíndricas $(r;\theta;z)$ | Ecuación en Esféricas $(\rho;\theta;\phi)$ |
| :--- | :--- | :--- | :--- | :--- |
| **Cilindro Circular Recto** *(Cuádrica incompleta)* | $x^2 + y^2 = R^2$ | Falta la variable $z$. Son paredes verticales tubulares de radio $R$. | $r = R$ | $\rho\sin\phi = R$ |
| **Cilindro Parabólico Recto** *(Cuádrica incompleta)* | $z = c - x^2$ o $x^2 + y = 4$ | Falta una de las 3 variables ($x, y$ o $z$) y otra está al cuadrado. Es un canal o túnel. | Se trabaja en **cartesianas** proyectando sobre el plano de las 2 variables presentes. | No se usa. |
| **Paraboloide Circular (Elíptico)** | $z = a + b(x^2 + y^2)$ | $z$ tiene exponente $1$; $x^2$ e $y^2$ tienen igual coeficiente. Tiene forma de tazón ($b>0$) o cúpula ($b<0$). | $z = a + b r^2$ | No recomendable (usar cilíndricas). |
| **Semicono Circular Recto** | $z = a + b\sqrt{x^2 + y^2}$ | Aparece $\sqrt{x^2+y^2}$ (que equivale a $r$). Tiene un vértice en $(0;0;a)$ y paredes rectas inclinadas. | $z = a + b r$ | Si $a=0$ (vértice en el origen): $\tan\phi = \frac{1}{b} \implies \phi = \arctan\left(\frac{1}{b}\right)$ |
| **Esfera / Casquete Esférico** | $x^2 + y^2 + (z-z_0)^2 = R^2$ | Las 3 variables están al cuadrado con coeficiente $1$. | $z = z_0 \pm \sqrt{R^2 - r^2}$ | Si $z_0 = 0$ (centrada en el origen): $\rho = R$ |

---

## SECCIÓN C. DESARROLLO TEÓRICO DE CADA TEMA

---

### TEMA 1: Integrales Dobles en Coordenadas Cartesianas, Teorema de Fubini y Cambio de Orden de Integración

#### 1. Concepto Fundamental
La integral doble de una función $f(x; y)$ sobre una región plana acotada $D \subset \mathbb{R}^2$, denotada por $\iint_D f(x; y)\,dA$, representa la suma continua de los productos $f(x; y)\,\Delta A$ sobre pequeños rectángulos diferenciales de área $dA = dx\,dy$ o $dA = dy\,dx$. Si $f(x; y) > 0$, geométricamente equivale al **volumen** del sólido situado debajo de la superficie $z = f(x; y)$ y encima de la región plana $D$.

#### 2. Explicación desde Cero e Intuición (Analogía del Escáner)
Imagina que quieres pintar o escanear una figura plana $D$ usando pinceladas rectas:
* **Escaneo Vertical (Región Tipo I — Orden $dy\,dx$):** Mueves una línea vertical de izquierda a derecha, desde un valor mínimo numérico $x = a$ hasta un valor máximo numérico $x = b$. Para cada posición $x$, la línea vertical entra a la región por una curva inferior (**piso**: $y = g_1(x)$) y sale por una curva superior (**techo**: $y = g_2(x)$).
* **Escaneo Horizontal (Región Tipo II — Orden $dx\,dy$):** Mueves una línea horizontal de abajo hacia arriba, desde un número $y = c$ hasta un número $y = d$. Para cada altura $y$, la línea horizontal entra por la curva de la **izquierda** ($x = h_1(y)$) y sale por la curva de la **derecha** ($x = h_2(y)$).

#### 3. Elementos, Propiedades y el Teorema de Fubini
El **Teorema de Fubini** garantiza que si $f(x; y)$ es continua en $D$, la integral doble puede calcularse mediante dos integrales simples sucesivas (llamadas **integrales iteradas**), y el resultado es exactamente el mismo sin importar el orden elegido:

* **Descripción y planteamiento como Región Tipo I (Vertical — $dy\,dx$):**
  $$D = \left\{(x; y) \in \mathbb{R}^2 : a \le x \le b \,;\, g_1(x) \le y \le g_2(x)\right\}$$
  $$\iint_D f(x; y)\,dA = \int_a^b \int_{g_1(x)}^{g_2(x)} f(x; y)\,dy\,dx$$

* **Descripción y planteamiento como Región Tipo II (Horizontal — $dx\,dy$):**
  $$D = \left\{(x; y) \in \mathbb{R}^2 : c \le y \le d \,;\, h_1(y) \le x \le h_2(y)\right\}$$
  $$\iint_D f(x; y)\,dA = \int_c^d \int_{h_1(y)}^{h_2(y)} f(x; y)\,dx\,dy$$

> **Regla de Oro de los Límites:**
> Los límites de la **integral exterior** (la primera que escribes a la izquierda) **SIEMPRE deben ser números constantes** ($a, b$ o $c, d$). Nunca puede haber una variable $x$ o $y$ en los límites de la primera integral. Los límites de la **integral interior** pueden depender únicamente de la variable exterior.

#### 4. Procedimiento Paso a Paso para Invertir (Cambiar) el Orden de Integración
¿Por qué necesitamos cambiar el orden de integración? Porque a veces la integral interior no tiene primitiva elemental (por ejemplo: $\int e^{x^2}\,dx$, $\int \sqrt{4+y^2}\,dy$, $\int \frac{y}{2+e^y}\,dy$, $\int \frac{\ln(x+2)}{x+2}\,dx$ o $\int \sin^3(x)\,dx$ cuando es mucho más fácil integrar respecto a la otra variable primero).

Sigue siempre estos **5 pasos mecánicos**:
1. **Extraer la descripción original $D_1$:** Lee los límites de las dos integrales dadas y escríbelos como desigualdades.
   *Ejemplo:* En $\int_0^1 \int_{4y^2}^{4y} f(x; y)\,dx\,dy$, la diferencial exterior es $dy$ ($0 \le y \le 1$) y la interior es $dx$ ($4y^2 \le x \le 4y$).
2. **Identificar las ecuaciones de frontera y los puntos de corte:** Igualamos cada desigualdad: $y = 0$, $y = 1$, $x = 4y^2$ (parábola), $x = 4y$ (recta). Hallamos dónde se cruzan reemplazando $y=1 \Rightarrow x=4$ y $y=0 \Rightarrow x=0$.
3. **Graficar la región $D$ y sombrearla:** Dibuja las curvas en el plano $xy$ y sombrea únicamente la zona encerrada. Verifica en qué cuadrante está.
4. **Despejar la otra variable en las curvas:** Si las curvas estaban como $x = h(y)$, despéjalas como $y = g(x)$ (¡cuidando el signo de la raíz según el cuadrante!).
   *Ejemplo:* De $x = 4y \Rightarrow y = \frac{x}{4}$. De $x = 4y^2 \Rightarrow y^2 = \frac{x}{4} \Rightarrow y = \frac{\sqrt{x}}{2}$ (positiva porque estamos en el primer cuadrante).
5. **Re-escanear en la dirección opuesta para escribir $D_2$ y la nueva integral:**
   * Si antes era $dx\,dy$ (horizontal), ahora escanea verticalmente ($dy\,dx$): ¿de qué número a qué número va $x$? ($0 \le x \le 4$). ¿Qué curva está abajo (piso) y cuál arriba (techo)? Abajo está la recta $y = \frac{x}{4}$ y arriba la parábola $y = \frac{\sqrt{x}}{2}$.
   * Escribe la nueva integral: $\int_0^4 \int_{x/4}^{\sqrt{x}/2} f(x; y)\,dy\,dx$.

#### 5. Interpretación en el Examen
* **¿Cómo reconocerlo?** El enunciado dirá explícitamente: *«Plantee la integral iterada cambiando el orden de integración»* o *«Evalúe invirtiendo el orden de integración»*.
* **Estrategia de examen:** En la Parte 1 (Objetiva), **descarta inmediatamente** cualquier alternativa cuya primera integral tenga letras en sus límites o cuyos diferenciales ($dy\,dx$) no coincidan con el orden invertido.

#### 6. Errores Frecuentes
* **Error 1 (El error fatal de transposición):** Creer que cambiar el orden de integración consiste simplemente en intercambiar los dos símbolos de integral $\int_a^b \int_{g_1}^{g_2} \to \int_{g_1}^{g_2} \int_a^b$. **¡Falso!** Eso deja funciones en la integral exterior.
* **Error 2:** Olvidar el signo negativo al despejar $x = -\sqrt{\dots}$ cuando la región está a la izquierda del eje $y$ ($x \le 0$).
* **Error 3:** Equivocarse al decidir cuál curva va abajo y cuál arriba. *Truco:* Evalúa un valor intermedio (por ejemplo, $x = 1$ en $y = \frac{x}{4} = 0.25$ y $y = \frac{\sqrt{x}}{2} = 0.5$; como $0.25 < 0.5$, entonces $\frac{x}{4}$ es el límite inferior y $\frac{\sqrt{x}}{2}$ es el superior).

#### 7. Conexiones
Este tema es la base directa para el **Tema 3** (cálculo de áreas y masas en cartesianas) y para el **Tema 4** (donde la proyección 2D de un sólido 3D se describe exactamente como una región Tipo I o Tipo II).

---

### TEMA 2: Integrales Dobles en Coordenadas Polares

#### 1. Concepto Fundamental
Las coordenadas polares localizan cualquier punto $(x; y)$ del plano mediante dos datos: su **distancia radial al origen** ($r \ge 0$) y el **ángulo** ($\theta$) que forma el radio vector con el semieje positivo $x$ medido en sentido antihorario.

#### 2. Explicación desde Cero: ¿Por qué aparece una "$r$" extra ($r\,dr\,d\theta$)?
En coordenadas cartesianas, un pequeño recuadro tiene lados $dx$ y $dy$, por lo que su área es $dA = dx\,dy$.
En coordenadas polares, si avanzas un pequeño radio $dr$ y giras un pequeño ángulo $d\theta$, se forma un **sector de corona circular**. El arco de circunferencia de radio $r$ y ángulo $d\theta$ no mide $d\theta$, sino que su longitud de arco es $r\,d\theta$ (cuanto más lejos estás del origen, más ancho es el arco para el mismo ángulo). Por lo tanto, el área de ese "rectángulo polar" es:
$$dA = (\text{largo radial}) \times (\text{ancho de arco}) = dr \cdot (r\,d\theta) = r\,dr\,d\theta$$
Ese factor $r$ adicional se llama **Jacobiano de la transformación polar**.

#### 3. Elementos, Ecuaciones de Transformación y Fórmula Oficial
* **Ecuaciones de paso entre Cartesianas y Polares:**
  $$x = r\cos\theta \quad,\quad y = r\sin\theta \quad,\quad x^2 + y^2 = r^2 \quad,\quad \tan\theta = \frac{y}{x}$$
* **Descripción ordenada de una región polar $D$:**
  $$D = \left\{(r; \theta) : \alpha \le \theta \le \beta \,;\, h_1(\theta) \le r \le h_2(\theta)\right\}$$
* **Fórmula de cambio de variable a coordenadas polares (Formulario UPC #4):**
  $$\iint_D f(x; y)\,dA = \int_\alpha^\beta \int_{h_1(\theta)}^{h_2(\theta)} f(r\cos\theta; r\sin\theta)\,\mathbf{r}\,dr\,d\theta$$

#### 4. Procedimientos Clave en Polares
**Procedimiento A: Pasar una integral cartesiana a polares (Ejercicios tipo 7 del banco)**
1. Lee los límites cartesianos para identificar las curvas (usualmente contienen $\sqrt{a^2-x^2}$, $\sqrt{a^2-y^2}$ o $\sqrt{2ay-y^2}$).
2. Eleva al cuadrado para reconocer la circunferencia:
   * $x = \sqrt{4-y^2} \implies x^2 + y^2 = 4 \implies r = 2$.
   * $x = \sqrt{2y-y^2} \implies x^2 + y^2 = 2y \implies r^2 = 2r\sin\theta \implies r = 2\sin\theta$.
3. Dibuja la porción de círculo según los signos de $x$ e $y$ para determinar los ángulos de inicio y fin ($\alpha \le \theta \le \beta$).
4. Sustituye $\sqrt{x^2+y^2} = r$, $x^2+y^2 = r^2$, y **reemplaza $dx\,dy$ por $r\,dr\,d\theta$**.

**Procedimiento B: Región entre Circunferencia y Cardioide (Preguntas de Examen 2025-10 y 2026-10)**
1. Convierte la circunferencia cartesiana $C_1$ a polares (por ejemplo, $x^2+y^2 = 9 \implies r = 3$, o $x^2+y^2 = 3y \implies r = 3\sin\theta$).
2. **Halla los ángulos de intersección** igualando los dos radios: $r_1(\theta) = r_2(\theta)$. Despeja $\sin\theta$ o $\cos\theta$ y obtén los ángulos $\alpha$ y $\beta$ en los cuadrantes correspondientes a la zona sombreada.
3. Traza una flecha (rayo) que nace en el origen $(0;0)$ y atraviesa la región sombreada hacia afuera:
   * La curva por donde la flecha **entra** a la región sombreada es el **radio interior** $h_1(\theta)$.
   * La curva por donde la flecha **sale** de la región sombreada es el **radio exterior** $h_2(\theta)$.

#### 5. Interpretación en el Examen
Usa coordenadas polares siempre que:
* La región sea un círculo, semicírculo, sector circular, anillo o cardioide.
* Aparezca la combinación $x^2 + y^2$ en las curvas frontera o dentro de la integral.

#### 6. Errores Frecuentes
* **El olvido mortal:** Olvidar multiplicar por el jacobiano $r$. Si el integrando ya tiene una $r$ (por ejemplo, $\delta = 2r$), al multiplicar por $r\,dr\,d\theta$ debe quedar $2r^2\,dr\,d\theta$. En las alternativas de selección múltiple de la UPC **siempre** ponen un distractor sin la $r$ adicional.
* **Confundir "delimitado exteriormente" con "fuera de":**
  * Si un enunciado dice: *«Región $D$ delimitada exteriormente por $C_1$ e interiormente por $C_2$»* (o *«fuera de $C_1$ y dentro de $C_2$»*), ¡mira siempre el dibujo sombreado del examen! El radio menor $h_1(\theta)$ es la curva más cercana al origen en la zona sombreada, y el radio mayor $h_2(\theta)$ es la curva más alejada del origen en esa misma zona.

#### 7. Conexiones
Dominar coordenadas polares en 2D te regala automáticamente el $80\%$ de las **coordenadas cilíndricas en 3D** (Tema 5), ya que las coordenadas cilíndricas son simplemente coordenadas polares $(r; \theta)$ en el piso más la altura $z$.

---

### TEMA 3: Aplicaciones de las Integrales Dobles (Área y Masa de Placas Planas)

#### 1. Concepto Fundamental y Fórmulas Oficiales (Formulario UPC #2 y #3)
Sea $D \subset \mathbb{R}^2$ la región que modela una **placa o lámina plana delgada**:
1. **Área de la región plana $D$:** Se obtiene integrando la función constante $1$:
   $$A(D) = \iint_D 1\,dA$$
   * En cartesianas: $A(D) = \int_a^b \int_{g_1(x)}^{g_2(x)} 1\,dy\,dx$
   * En polares: $A(D) = \int_\alpha^\beta \int_{h_1(\theta)}^{h_2(\theta)} r\,dr\,d\theta$
2. **Masa de una placa plana delgada $D$:** Si la placa tiene una densidad superficial variable $\delta(x; y)$ (medida por ejemplo en $\text{g/cm}^2$ o $\text{kg/m}^2$) en cada punto $(x; y)$, su masa total es:
   $$m(D) = \iint_D \delta(x; y)\,dA$$
   * En polares: $m(D) = \int_\alpha^\beta \int_{h_1(\theta)}^{h_2(\theta)} \delta(r\cos\theta; r\sin\theta)\,r\,dr\,d\theta$

#### 2. Explicación desde Cero
¿Por qué la masa es la integral de la densidad? En física elemental, si una placa tiene densidad uniforme, $\text{Masa} = \text{Densidad} \times \text{Área}$. Pero cuando la placa es más pesada en ciertas zonas que en otras (densidad variable $\delta(x; y)$), tomamos un pedacito microscópico de área $dA$ donde la densidad es prácticamente constante e igual a $\delta(x; y)$. La masa de ese pedacito es $dm = \delta(x; y)\,dA$. Sumando todos los pedacitos con una integral doble obtenemos $m(D) = \iint_D \delta(x; y)\,dA$.

#### 3. Truco de Velocidad para Calcular Áreas Polares en Calculadora
Cuando en el examen tengas que calcular numéricamente el área entre dos curvas polares $r_{\text{in}}(\theta) \le r \le r_{\text{ext}}(\theta)$ para $\alpha \le \theta \le \beta$:
$$A(D) = \int_\alpha^\beta \int_{r_{\text{in}}(\theta)}^{r_{\text{ext}}(\theta)} r\,dr\,d\theta = \int_\alpha^\beta \left[\frac{r^2}{2}\right]_{r_{\text{in}}(\theta)}^{r_{\text{ext}}(\theta)} d\theta = \frac{1}{2} \int_\alpha^\beta \left( \left[r_{\text{ext}}(\theta)\right]^2 - \left[r_{\text{in}}(\theta)\right]^2 \right) d\theta$$
Una vez que muestras el paso intermedio $\left[\frac{r^2}{2}\right]$ en tu hoja de evidencia, puedes ingresar directamente la integral simple respecto a $\theta$ en tu calculadora científica (asegurándote de que tu calculadora esté en **modo RADIANES `[RAD]`**).

---

### TEMA 4: Graficación en $\mathbb{R}^3$ e Integrales Triples en Coordenadas Cartesianas

#### 1. Concepto Fundamental
La integral triple de una función $f(x; y; z)$ sobre un sólido acotado $E \subset \mathbb{R}^3$, denotada por $\iiint_E f(x; y; z)\,dV$, suma los valores de la función multiplicados por pequeños bloques diferenciales de volumen $dV = dx\,dy\,dz$ (en cualquiera de sus $6$ permutaciones posibles).
* **Volumen del sólido $E$ (Formulario UPC #6):**
  $$V(E) = \iiint_E 1\,dV$$
* **Masa del sólido $E$ con función de densidad volumétrica $\rho(x; y; z)$ o $\delta(x; y; z)$ (Formulario UPC #7):**
  $$m(E) = \iiint_E \delta(x; y; z)\,dV$$

#### 2. Explicación desde Cero: El Método de la Sombra (Proyección 2D + Disparos 3D)
En los exámenes de la UPC (como la Pregunta 4 del 2025-10 V1 y la Pregunta 1 del 2025-10 V2), suelen darte un sólido en el primer octante limitado por un **cilindro parabólico** y un **plano inclinado**, pidiéndote expresamente proyectarlo sobre el **plano $xy$**, sobre el **plano $xz$** o sobre el **plano $yz$**.

¿Cómo se describe un sólido proyectándolo sobre cualquiera de los tres planos coordenados?
1. **Caso 1: Proyección sobre el plano $xy$ (Orden interior $dz$, luego $dy\,dx$ o $dx\,dy$):**
   * Miras la sombra $D_{xy}$ en el piso ($z=0$) y la describes en 2D (por ejemplo, $a \le x \le b$, $g_1(x) \le y \le g_2(x)$).
   * Para la tercera variable ($z$), disparas una flecha vertical de **abajo hacia arriba** (paralela al eje $z$): entra por el piso $z = u_1(x; y)$ y sale por el techo $z = u_2(x; y)$.
   * Integral: $\int_a^b \int_{g_1(x)}^{g_2(x)} \int_{u_1(x;y)}^{u_2(x;y)} f(x; y; z)\,dz\,dy\,dx$.

2. **Caso 2: Proyección sobre el plano $xz$ (Evaluado en Examen 2025-10 V1, Pregunta 4):**
   * *Contexto típico:* Te dan el cilindro parabólico $x^2 + z = 4$ (¡nota que solo tiene las letras $x$ y $z$!) y el plano $x + y + z = 6$ en el primer octante.
   * **Paso A (La sombra en $xz$):** En el plano $xz$ ($y=0$), dibujas la parábola $z = 4 - x^2$ en el primer cuadrante ($x \ge 0, z \ge 0$). Corta al eje $x$ en $x = 2$ y al eje $z$ en $z = 4$. Por tanto, la sombra en $xz$ es:
     $$0 \le x \le 2 \quad;\quad 0 \le z \le 4 - x^2$$
   * **Paso B (El disparo en la variable faltante $y$):** La variable que no está en el plano $xz$ es $y$. En el primer octante, $y$ empieza en la pared $y = 0$ y sale por el plano inclinado $x + y + z = 6 \implies y = 6 - x - z$:
     $$0 \le y \le 6 - x - z$$
   * **Paso C (Planteamiento de la integral):** La primera integral interior **debe ser $dy$** (la variable de disparo), seguida de los límites de la sombra ($dz\,dx$):
     $$\int_0^2 \int_0^{4-x^2} \int_0^{6-x-z} f(x; y; z)\,dy\,dz\,dx$$

3. **Caso 3: Proyección sobre el plano $yz$ (Evaluado en Examen 2025-10 V2, Pregunta 1):**
   * *Contexto típico:* Te dan el cilindro $x^2 + y = 4$ y el plano $y + z = 5$ en el primer octante, y te piden proyectar sobre el **plano $yz$**.
   * **Paso A (La sombra en $yz$):** En el plano $yz$, la recta $y + z = 5$ va hasta $y=5$, pero el cilindro $x^2 + y = 4 \implies x = \sqrt{4-y}$ exige que $y \le 4$ (en $y=4$ hay una pared vertical que corta al sólido). Así, la sombra en $yz$ es un trapecio:
     $$0 \le y \le 4 \quad;\quad 0 \le z \le 5 - y$$
   * **Paso B (El disparo en la variable faltante $x$):** $x$ va desde el plano $x = 0$ hasta la superficie cilíndrica $x = \sqrt{4 - y}$:
     $$0 \le x \le \sqrt{4 - y}$$
   * **Paso C (Planteamiento de la integral):** La integral interior es $dx$, seguida de $dz\,dy$:
     $$\int_0^4 \int_0^{5-y} \int_0^{\sqrt{4-y}} f(x; y; z)\,dx\,dz\,dy$$

---

### TEMA 5: Integrales Triples en Coordenadas Cilíndricas y Modelación de Tanques

#### 1. Concepto Fundamental
El sistema de coordenadas cilíndricas representa un punto del espacio mediante $(r; \theta; z)$, donde $(r; \theta)$ son las coordenadas polares de la proyección del punto sobre el plano $xy$, y $z$ es la misma coordenada cartesiana de altura.

#### 2. Elementos, Ecuaciones de Transformación y Fórmula Oficial (Formulario UPC #9)
* **Ecuaciones de relación:**
  $$x = r\cos\theta \quad,\quad y = r\sin\theta \quad,\quad z = z \quad,\quad x^2 + y^2 = r^2 \quad,\quad \tan\theta = \frac{y}{x}$$
* **Diferencial de volumen en cilíndricas:**
  $$dV = \mathbf{r}\,dz\,dr\,d\theta$$
* **Descripción ordenada del sólido $E$:**
  $$E = \left\{(r; \theta; z) : \alpha \le \theta \le \beta \,;\, h_1(\theta) \le r \le h_2(\theta) \,;\, u_1(r; \theta) \le z \le u_2(r; \theta)\right\}$$
* **Integral triple iterada en cilíndricas:**
  $$\iiint_E f(x; y; z)\,dV = \int_\alpha^\beta \int_{h_1(\theta)}^{h_2(\theta)} \int_{u_1(r;\theta)}^{u_2(r;\theta)} f(r\cos\theta; r\sin\theta; z)\,\mathbf{r}\,dz\,dr\,d\theta$$

#### 3. Guía Maestra para Resolver la Pregunta de Desarrollo (Modelación de Tanques — $5\text{ puntos}$)
En todos los exámenes de la UPC, la Pregunta 5 (Parte 2) vale $5\text{ puntos}$ y consiste en modelar un tanque industrial de revolución alrededor del eje $z$. Aquí tienes el **método infalible en 3 etapas** para obtener los $5\text{ puntos}$ completos:

##### Etapa 1: Hallar las ecuaciones de las superficies ($1\text{ punto}$)
1. **Lee el diámetro $D$ del cilindro y divídelo entre $2$ inmediatamente para obtener el radio $R = \frac{D}{2}$.**
   * La ecuación de la pared cilíndrica vertical es siempre:
     $$S_1: x^2 + y^2 = R^2 \quad (\text{en cilíndricas: } r = R)$$
2. **Para hallar las constantes ($k$, o $a$ y $b$) del semicono o paraboloide:**
   * Identifica dos puntos clave sobre el perfil del tanque mirando las cotas de altura en el dibujo (usamos $x = 0$, por lo que $\sqrt{x^2+y^2} = y = r$ y $x^2+y^2 = y^2 = r^2$):
     * **Punto en el eje central ($r = 0$):** Es la punta (vértice) del cono o de la cúpula parabólica: $(0; 0; z_{\text{eje}})$. Al reemplazar $x=0, y=0$ en $z = a + b(x^2+y^2)$ o $z = a + b\sqrt{x^2+y^2}$, obtienes directamente:
       $$a = z_{\text{eje}}$$
     * **Punto en el borde donde se une con el cilindro ($r = R$):** Tiene coordenadas $(0; R; z_{\text{borde}})$. Reemplazas $x=0, y=R, z=z_{\text{borde}}$ para despejar $b$ (o $k$):
       * En un **semicono** $z = a + b\sqrt{x^2+y^2}$: $z_{\text{borde}} = a + b R \implies b = \frac{z_{\text{borde}} - a}{R}$.
       * En un **paraboloide** $z = a + b(x^2+y^2)$: $z_{\text{borde}} = a + b R^2 \implies b = \frac{z_{\text{borde}} - a}{R^2}$.
   * **Caso especial: Casquete esférico (como el balón Solgas, Ej. 25, o el tanque GeoTanque, Ej. 26):**
     * Si la esfera está centrada en el origen ($x^2+y^2+z^2 = R_{\text{esf}}^2$), el radio de la esfera $R_{\text{esf}}$ es la altura máxima del tanque medida desde el origen.
     * Si el casquete esférico está desplazado sobre un cilindro de radio $r_0$ y el casquete tiene una pequeña altura (flecha) $h_c$, aplicas el **Teorema de Pitágoras** en el triángulo rectángulo formado por el radio de la esfera $c$, el radio del cilindro $r_0$ y el cateto vertical $(c - h_c)$:
       $$c^2 = (c - h_c)^2 + r_0^2$$
       De ahí despejas el radio de la esfera $c$, y el centro de la esfera se ubica en $b = z_{\text{tope}} - c$.

##### Etapa 2: Dibujar la Proyección 2D y Describir Ordenadamente el Sólido ($2\text{ puntos}$)
> **¡ATENCIÓN CON EL CRITERIO DE CALIFICACIÓN UPC!**
> En el Examen 2025-10 V1 (página 6), al estudiante que sacó $19/20$ le descontaron $0.5\text{ puntos}$ en este ítem y el profesor escribió con lapicero: **«Falta la proyección»**.
> **Siempre debes dibujar en el plano $xy$ el círculo de radio $R$ sombreado**, indicar su ecuación $x^2+y^2 = R^2$ ($r = R$), y luego escribir el conjunto en coordenadas cilíndricas:
$$E = \left\{(r; \theta; z) : 0 \le \theta \le 2\pi \,;\, 0 \le r \le R \,;\, z_{\text{piso}}(r) \le z \le z_{\text{techo}}(r)\right\}$$
*(Observa por qué las coordenadas cilíndricas son tan potentes: la pared lateral del cilindro $r = R$ actúa como el límite superior de $r$, de modo que un tanque formado por un cilindro más una tapa o fondo cónico/parabólico se calcula con **UNA SOLA integral triple** desde $z_{\text{piso}}(r)$ hasta $z_{\text{techo}}(r)$).*

##### Etapa 3: Plantear y Calcular el Volumen con Integral Triple ($2\text{ puntos}$)
$$V(E) = \iiint_E 1\,dV = \int_0^{2\pi} \int_0^R \int_{z_{\text{piso}}(r)}^{z_{\text{techo}}(r)} r\,dz\,dr\,d\theta = 2\pi \int_0^R r \left( z_{\text{techo}}(r) - z_{\text{piso}}(r) \right) dr$$
No olvides colocar las unidades cúbicas al final ($\text{m}^3$ o $\text{cm}^3$).

---

### TEMA 6: Integrales Triples en Coordenadas Esféricas

#### 1. Concepto Fundamental
Las coordenadas esféricas ubican un punto en el espacio mediante la terna $(\rho; \theta; \phi)$ (según la notación oficial del Formulario UPC):
1. $\rho \ge 0$: Es la **distancia radial desde el origen $(0; 0; 0)$** hasta el punto $(x; y; z)$.
2. $\theta \in [0; 2\pi]$: Es el **mismo ángulo polar en el plano $xy$** medido desde el semieje positivo $x$.
3. $\phi \in [0; \pi]$: Es el **ángulo cenital (o polar espacial)** medido **desde el semieje positivo $z$ hacia abajo**.
   * En el semieje positivo $z$ (polo norte): $\phi = 0$.
   * En el plano $xy$ ($z = 0$, ecuador): $\phi = \frac{\pi}{2}$.
   * En el semieje negativo $z$ (polo sur): $\phi = \pi$.

#### 2. Explicación desde Cero: De dónde salen las ecuaciones y el Jacobiano $\rho^2\sin\phi$
Si trazas un segmento de longitud $\rho$ que forma un ángulo $\phi$ con el eje vertical $+z$:
* Su componente vertical sobre el eje $z$ es el cateto adyacente a $\phi$:
  $$z = \rho\cos\phi$$
* Su proyección sobre el piso $xy$ (el radio cilíndrico $r$) es el cateto opuesto a $\phi$:
  $$r = \sqrt{x^2+y^2} = \rho\sin\phi$$
* Como $x = r\cos\theta$ e $y = r\sin\theta$, al reemplazar $r = \rho\sin\phi$ obtenemos las ecuaciones oficiales:
  $$x = \rho\sin\phi\cos\theta \quad,\quad y = \rho\sin\phi\sin\theta \quad,\quad z = \rho\cos\phi$$
  $$x^2 + y^2 + z^2 = \rho^2 \quad,\quad \tan\theta = \frac{y}{x} \quad,\quad \tan\phi = \frac{\sqrt{x^2+y^2}}{z}$$
* **El Jacobiano en Esféricas:** Al barrer pequeños incrementos $d\rho$, $d\phi$ y $d\theta$, se forma una pequeña caja curva cuyas aristas miden $d\rho$, $\rho\,d\phi$ y $r\,d\theta = (\rho\sin\phi)\,d\theta$. Multiplicando las tres aristas obtenemos el diferencial de volumen oficial (Formulario UPC #10):
  $$dV = \mathbf{\rho^2\sin(\phi)}\,d\rho\,d\phi\,d\theta$$

#### 3. Traducción Rápida de Superficies a Coordenadas Esféricas
En los problemas de examen de la UPC aparecerán exactamente estas $4$ superficies en esféricas:
1. **Esfera centrada en el origen:** $x^2 + y^2 + z^2 = R^2 \iff \rho^2 = R^2 \iff \rho = R$.
2. **Semicono con vértice en el origen:** $z = k\sqrt{x^2+y^2}$.
   * Dividimos para formar $\tan\phi = \frac{\sqrt{x^2+y^2}}{z} = \frac{1}{k} \implies \phi = \arctan\left(\frac{1}{k}\right)$.
   * **Los $3$ semiconos clásicos de la UPC:**
     * $z = \sqrt{3x^2+3y^2} = \sqrt{3}\sqrt{x^2+y^2} \implies \tan\phi = \frac{1}{\sqrt{3}} \implies \phi = \frac{\pi}{6}$.
     * $z = \sqrt{x^2+y^2} \implies \tan\phi = 1 \implies \phi = \frac{\pi}{4}$.
     * $z = \sqrt{\frac{x^2+y^2}{3}} = \frac{1}{\sqrt{3}}\sqrt{x^2+y^2} \implies \tan\phi = \sqrt{3} \implies \phi = \frac{\pi}{3}$.
   * **¡Cuidado con las palabras "dentro/encima" vs "fuera/debajo" del semicono!:**
     * **«Dentro» o «encima» del semicono $\phi = \alpha$:** El sólido rodea al eje $+z$ (como un barquillo de helado), por lo que $\phi$ empieza en el eje $+z$ ($\phi = 0$) y baja hasta la pared del cono ($\phi = \alpha$):
       $$0 \le \phi \le \alpha$$
     * **«Fuera» o «debajo» del semicono $\phi = \alpha$ y «arriba del plano $z=0$»:** El sólido está entre la pared del cono ($\phi = \alpha$) y el piso $z=0$ ($\phi = \frac{\pi}{2}$):
       $$\alpha \le \phi \le \frac{\pi}{2}$$
3. **Plano vertical que pasa por el eje $z$:** $y = mx$.
   * Como $\tan\theta = \frac{y}{x} = m \implies \theta = \arctan(m)$.
   * Ejemplos de examen:
     * $y = \frac{1}{\sqrt{3}}x \implies \theta = \frac{\pi}{6}$.
     * $y = x \implies \theta = \frac{\pi}{4}$.
     * $y = \sqrt{3}x \implies \theta = \frac{\pi}{3}$.
     * $y = (2-\sqrt{3})x \implies \theta = \arctan(2-\sqrt{3}) = \frac{\pi}{12}$ ($15^\circ$).
     * Plano $y = 0$ (en el primer octante): $\theta = 0$.
     * Plano $x = 0$ (en el primer octante): $\theta = \frac{\pi}{2}$.
4. **Plano horizontal:** $z = c$ (con $c > 0$).
   * Como $z = \rho\cos\phi = c \implies \rho = \frac{c}{\cos\phi} = c\sec(\phi)$. (Ver Ejercicio 23 del banco: $\rho = 4\sec\phi \iff z = 4$).

---

## SECCIÓN D. EJEMPLOS COMPLETAMENTE RESUELTOS PASO A PASO

Aplicaremos la metodología completa de **9 pasos** a los problemas representativos de cada bloque del examen.

---

### EJEMPLO RESUELTO 1 (Cambio de Orden de Integración con Raíz en el 2do Cuadrante)
*(Basado en los Ejercicios 01, 6f y 6l del Banco de Preguntas y Pregunta 2/3 de los Exámenes 2025-10)*

#### 1. Enunciado
Dada la siguiente integral iterada:
$$I = \int_{-3\sqrt{2}}^0 \int_2^{4 - \frac{x^2}{9}} \frac{y}{2 + e^y}\,dy\,dx$$
a) Describa la región de integración original $D_1$ y grafíquela en el plano $xy$.
b) Describa la región invirtiendo el orden de integración ($D_2$) y plantee la nueva integral iterada.
c) Calcule el valor de la integral (redondeado a $3$ decimales).

#### 2. Información que proporciona el problema
* El orden actual es $dy\,dx$ (Región Tipo I: barrido vertical).
* La variable exterior es $x$, que varía entre $-3\sqrt{2}$ y $0$ (números negativos: **Segundo Cuadrante**).
* La variable interior es $y$, que varía desde la recta horizontal $y = 2$ hasta la parábola $y = 4 - \frac{x^2}{9}$.
* El integrando es $f(x; y) = \frac{y}{2+e^y}$.

#### 3. ¿Qué se solicita?
Describir y graficar la región, invertir los límites a la forma $dx\,dy$ (Región Tipo II: barrido horizontal) y evaluar la integral resultante.

#### 4. Concepto y procedimiento a utilizar y por qué
Como la función $\frac{y}{2+e^y}$ no tiene una antiderivada elemental sencilla respecto a $y$, debemos aplicar el **Teorema de Fubini** para cambiar el orden a $dx\,dy$. Al integrar primero respecto a $x$, todo el término $\frac{y}{2+e^y}$ actúa como una constante, simplificando el cálculo.

#### 5 y 6. Desarrollo paso a paso y cálculos justificados
* **Paso 1 (Descripción original $D_1$):**
  $$D_1 = \left\{(x; y) \in \mathbb{R}^2 : -3\sqrt{2} \le x \le 0 \,;\, 2 \le y \le 4 - \frac{x^2}{9}\right\}$$
* **Paso 2 (Análisis de curvas e intersecciones para la gráfica):**
  * Curva superior: $y = 4 - \frac{x^2}{9}$ (parábola cóncava hacia abajo con vértice en $(0; 4)$).
  * Curva inferior: $y = 2$ (recta horizontal).
  * Intersección entre ambas:
    $$2 = 4 - \frac{x^2}{9} \implies \frac{x^2}{9} = 2 \implies x^2 = 18 \implies x = \pm\sqrt{18} = \pm 3\sqrt{2}$$
    Como en $D_1$ tenemos $-3\sqrt{2} \le x \le 0$, la región está exclusivamente en el **Segundo Cuadrante** ($x \le 0, y \ge 0$), limitada a la derecha por el eje $y$ ($x = 0$).
* **Paso 3 (Despeje de $x$ en función de $y$ — ¡Cuidado con el signo!):**
  De la ecuación de la parábola $y = 4 - \frac{x^2}{9}$:
  $$\frac{x^2}{9} = 4 - y \implies x^2 = 9(4 - y) \implies x = \pm\sqrt{9(4-y)} = \pm 3\sqrt{4-y}$$
  Como estamos en el Segundo Cuadrante donde $x \le 0$, **elegimos obligatoriamente la rama negativa**:
  $$x = -\sqrt{9(4-y)} = -3\sqrt{4-y}$$
* **Paso 4 (Nueva descripción $D_2$ en orden $dx\,dy$):**
  * La altura $y$ varía desde el piso $y = 2$ hasta el vértice superior $y = 4$: $2 \le y \le 4$.
  * Escaneando horizontalmente de izquierda a derecha, $x$ entra por la parábola izquierda $x = -3\sqrt{4-y}$ y sale por el eje vertical $x = 0$:
    $$D_2 = \left\{(x; y) \in \mathbb{R}^2 : 2 \le y \le 4 \,;\, -3\sqrt{4-y} \le x \le 0\right\}$$
* **Paso 5 (Planteamiento y cálculo de la nueva integral iterada):**
  $$I = \int_2^4 \int_{-3\sqrt{4-y}}^0 \frac{y}{2 + e^y}\,dx\,dy$$
  Integramos primero respecto a $x$ (donde $\frac{y}{2+e^y}$ es constante):
  $$I = \int_2^4 \frac{y}{2 + e^y} \Big[ x \Big]_{x = -3\sqrt{4-y}}^{x = 0} dy = \int_2^4 \frac{y}{2 + e^y} \left( 0 - \left(-3\sqrt{4-y}\right) \right) dy$$
  $$I = \int_2^4 \frac{3y\sqrt{4 - y}}{2 + e^y}\,dy$$
  Evaluando esta integral definida en la calculadora científica:
  $$I \approx 0.865$$

#### 7. Respuesta Final
* $D_2 = \left\{(x; y) \in \mathbb{R}^2 : 2 \le y \le 4 \,;\, -3\sqrt{4-y} \le x \le 0\right\}$
* $I = \int_2^4 \int_{-3\sqrt{4-y}}^0 \frac{y}{2 + e^y}\,dx\,dy \approx 0.865$.

#### 8. Verificación de coherencia
Observa el integrando original $\frac{y}{2+e^y}$: como en toda la región se cumple que $2 \le y \le 4$, el numerador $y$ es positivo y el denominador $2+e^y$ es positivo. La integral de una función estrictamente positiva sobre un área positiva **tiene que dar un número positivo** ($+0.865$). *(En el PDF de Studocu de la guía de repaso les salió $-0.865$ porque olvidaron el signo menos de la raíz y pusieron $+3\sqrt{4-y}$ en el límite inferior).*

#### 9. ¿Cómo variaría si cambian los datos?
Si la integral original hubiese sido $\int_0^{3\sqrt{2}} \int_2^{4-x^2/9} \frac{y}{2+e^y}\,dy\,dx$ (en el Primer Cuadrante, con $x \ge 0$), entonces al despejar $x$ usaríamos la raíz positiva $x = +3\sqrt{4-y}$, y en el barrido horizontal de izquierda a derecha $x$ entraría por el eje $x = 0$ y saldría por la parábola $x = 3\sqrt{4-y}$, quedando $0 \le x \le 3\sqrt{4-y}$.

---

### EJEMPLO RESUELTO 2 (Área y Masa en Coordenadas Polares: Circunferencia y Cardioide)
*(Basado en la Pregunta 1 del Examen 2025-10 V1, Pregunta 3 del Examen 2026-10 y Ejercicio 8 del Banco)*

#### 1. Enunciado
Una placa delgada tiene la forma de la región $D$ ubicada fuera de la circunferencia $C_1: x^2 + y^2 = 9$ y dentro del cardioide $C_2: r = 2 + 2\cos(\theta)$.
a) Exprese la ecuación de $C_1$ en coordenadas polares y halle los valores de $\theta$ en los puntos de intersección de ambas curvas.
b) Describa la región $D$ de forma ordenada en coordenadas polares.
c) Plantee la integral iterada que permite calcular el área de la región $D$ y calcule su valor.
d) Plantee la integral iterada que permite calcular la masa de la placa, sabiendo que la densidad $\delta$ ($\text{g/cm}^2$) en cualquier punto $(x; y)$ es numéricamente igual al doble de la distancia de dicho punto al eje $y$.

#### 2. Información proporcionada
* Frontera interior de la luna sombreada: circunferencia $C_1: x^2 + y^2 = 9$.
* Frontera exterior de la luna sombreada: cardioide horizontal derecho $C_2: r = 2 + 2\cos(\theta)$.
* Condición de densidad: $\delta(x; y) = 2 \cdot (\text{distancia al eje } y)$.

#### 3. ¿Qué se solicita?
Convertir $C_1$ a polares, hallar intersecciones, describir $D$, plantear/calcular el área $A(D)$ y plantear la masa $m(D)$.

#### 4. Concepto y procedimiento a utilizar
Usamos **coordenadas polares** ($x = r\cos\theta$, $y = r\sin\theta$, $x^2+y^2 = r^2$, $dA = r\,dr\,d\theta$) porque las fronteras son una circunferencia centrada y un cardioide polar.

#### 5 y 6. Desarrollo paso a paso y cálculos
* **Paso a (Conversión e intersecciones):**
  Sustituimos $x^2+y^2 = r^2$ en $C_1$:
  $$r^2 = 9 \implies r = 3 \quad (\text{pues } r \ge 0)$$
  Igualamos los radios de $C_1$ y $C_2$ para hallar los ángulos de corte:
  $$2 + 2\cos(\theta) = 3 \implies 2\cos(\theta) = 1 \implies \cos(\theta) = \frac{1}{2}$$
  Como el cardioide $r = 2 + 2\cos(\theta)$ es simétrico respecto al semieje positivo $x$ (donde $\theta = 0$, $r = 4 > 3$), la región se extiende desde el Cuarto Cuadrante hasta el Primer Cuadrante:
  $$\theta_1 = -\arccos\left(\frac{1}{2}\right) = -\frac{\pi}{3} \quad \text{y} \quad \theta_2 = +\arccos\left(\frac{1}{2}\right) = \frac{\pi}{3}$$
* **Paso b (Descripción ordenada de $D$ en polares):**
  Para cualquier ángulo $\theta \in \left[-\frac{\pi}{3}; \frac{\pi}{3}\right]$, un rayo que sale del origen atraviesa primero la circunferencia $r = 3$ (entra a $D$) y luego sale por el cardioide $r = 2 + 2\cos(\theta)$:
  $$D = \left\{(r; \theta) : -\frac{\pi}{3} \le \theta \le \frac{\pi}{3} \,;\, 3 \le r \le 2 + 2\cos(\theta)\right\}$$
* **Paso c (Planteamiento y cálculo del área):**
  Aplicando $A(D) = \iint_D 1\,dA$ con $dA = r\,dr\,d\theta$:
  $$A(D) = \int_{-\pi/3}^{\pi/3} \int_3^{2+2\cos(\theta)} r\,dr\,d\theta$$
  Resolvemos la integral interior:
  $$A(D) = \int_{-\pi/3}^{\pi/3} \left[\frac{r^2}{2}\right]_3^{2+2\cos(\theta)} d\theta = \frac{1}{2} \int_{-\pi/3}^{\pi/3} \left( (2 + 2\cos\theta)^2 - 3^2 \right) d\theta \approx 3.555\text{ u}^2$$
* **Paso d (Densidad y planteamiento de la masa):**
  * La distancia de un punto $(x; y)$ al **eje $y$** es $|x|$. Como toda la región $D$ está a la derecha del eje $y$ ($-\frac{\pi}{3} \le \theta \le \frac{\pi}{3} \implies x > 0$), la distancia es simplemente $x$.
  * El doble de la distancia al eje $y$ es:
    $$\delta(x; y) = 2x = 2(r\cos\theta)$$
  * Sustituyendo en la integral de masa $m(D) = \iint_D \delta(x; y)\,dA$ y multiplicando por el jacobiano $r$:
    $$m(D) = \int_{-\pi/3}^{\pi/3} \int_3^{2+2\cos(\theta)} \underbrace{(2r\cos\theta)}_{\delta} \cdot \underbrace{r\,dr\,d\theta}_{dA} = \int_{-\pi/3}^{\pi/3} \int_3^{2+2\cos(\theta)} 2r^2\cos(\theta)\,dr\,d\theta$$

#### 7. Respuesta Final
* $D = \left\{(r; \theta) : -\frac{\pi}{3} \le \theta \le \frac{\pi}{3} \,;\, 3 \le r \le 2 + 2\cos(\theta)\right\}$
* $A(D) = \int_{-\pi/3}^{\pi/3} \int_3^{2+2\cos(\theta)} r\,dr\,d\theta \approx 3.56$
* $m(D) = \int_{-\pi/3}^{\pi/3} \int_3^{2+2\cos(\theta)} 2r^2\cos(\theta)\,dr\,d\theta$

#### 8. Verificación
En $\theta = 0$, el límite superior del radio es $2 + 2\cos(0) = 4$, que es mayor que el límite inferior $3$ ($3 \le 4$, correcto). Además, en la integral de masa aparece $r^2$ porque un factor $r$ proviene de $x = r\cos\theta$ y el segundo factor $r$ proviene del jacobiano $dA = r\,dr\,d\theta$.

#### 9. Variaciones frecuentes en el examen
* Si el cardioide es $r = 2 + 2\sin(\theta)$ (como en el Examen 2026-10), la simetría es vertical y los ángulos de intersección con $r = 3$ cumplen $\sin\theta = \frac{1}{2}$, dando $\frac{\pi}{6} \le \theta \le \frac{5\pi}{6}$.
* Si pidieran que la densidad sea el doble de la distancia al **origen**, entonces $\delta = 2\sqrt{x^2+y^2} = 2r$, y el integrando sería $(2r)\cdot r = 2r^2\,dr\,d\theta$ (sin $\cos\theta$).

---

### EJEMPLO RESUELTO 3 (Integral Triple en Coordenadas Esféricas: Esfera, Cono y Planos)
*(Basado en el Ejercicio 03 y 22 del Banco de Preguntas y Pregunta 1 del Examen 2026-10)*

#### 1. Enunciado
El sólido $E$ ocupa la región del primer octante que se encuentra **fuera** del semicono $z = \sqrt{\frac{x^2+y^2}{3}}$, arriba del plano $z = 0$, dentro de la esfera $z^2 = 7 - x^2 - y^2$ y entre los planos $x = y$ y $x = 0$.
a) Exprese las ecuaciones de la esfera, del semicono y del plano $x = y$ en coordenadas esféricas, y describa ordenadamente el sólido $E$.
b) Plantee la integral iterada en coordenadas esféricas que permite calcular el volumen de $E$ y calcule su valor.
c) Si la densidad en cualquier punto del sólido es numéricamente igual a la distancia al plano $xz$, plantee la integral triple iterada que permite calcular la masa de $E$.

#### 2. Información proporcionada
* Ubicación: Primer octante ($x \ge 0, y \ge 0, z \ge 0$).
* Acotado exteriormente por la esfera $x^2 + y^2 + z^2 = 7$.
* Ubicado **fuera** del semicono $z = \sqrt{\frac{x^2+y^2}{3}}$ y **arriba** del plano $z = 0$.
* Acotado lateralmente por los planos verticales $x = y$ y $x = 0$.
* Densidad: $\delta(x; y; z) = \text{distancia al plano } xz$.

#### 3. ¿Qué se solicita?
Describir $E$ en esféricas $(\rho; \theta; \phi)$, plantear y hallar el volumen $V(E)$, y plantear la masa $m(E)$.

#### 4. Concepto y procedimiento a utilizar
Como las fronteras son una esfera centrada en el origen, un semicono con vértice en el origen y planos que pasan por el eje $z$, el sistema de **coordenadas esféricas** convierte todos los límites de integración en constantes numéricas.

#### 5 y 6. Desarrollo paso a paso y cálculos
* **Paso 1 (Conversión de cada superficie a esféricas):**
  1. **Esfera:** $z^2 = 7 - x^2 - y^2 \iff x^2 + y^2 + z^2 = 7 \iff \rho^2 = 7 \implies \rho = \sqrt{7}$. Como el sólido está *dentro* de la esfera desde el origen:
     $$0 \le \rho \le \sqrt{7}$$
  2. **Semicono y plano $z = 0$ (determinan el ángulo $\phi$):**
     $$z = \sqrt{\frac{x^2+y^2}{3}} = \frac{\sqrt{x^2+y^2}}{\sqrt{3}} \implies \frac{\sqrt{x^2+y^2}}{z} = \sqrt{3} \implies \tan(\phi) = \sqrt{3} \implies \phi = \frac{\pi}{3}$$
     El plano horizontal $z = 0$ corresponde al ecuador $\phi = \frac{\pi}{2}$.
     Como el sólido está **fuera** del semicono (se aleja del eje $z$) y **arriba** del plano $z = 0$, el ángulo cenital $\phi$ barre desde la pared del cono ($\frac{\pi}{3}$) hasta el piso ($\frac{\pi}{2}$):
     $$\frac{\pi}{3} \le \phi \le \frac{\pi}{2}$$
  3. **Planos verticales $x = y$ y $x = 0$ (determinan el ángulo $\theta$ en el plano $xy$):**
     * De $x = y \implies \frac{y}{x} = 1 \implies \tan(\theta) = 1 \implies \theta = \frac{\pi}{4}$.
     * El plano $x = 0$ en el primer cuadrante es el semieje positivo $y$, donde $\theta = \frac{\pi}{2}$.
     * Por lo tanto, el barrido en $\theta$ es:
       $$\frac{\pi}{4} \le \theta \le \frac{\pi}{2}$$
* **Paso 2 (Descripción ordenada del sólido $E$):**
  $$E = \left\{(\rho; \theta; \phi) : \frac{\pi}{4} \le \theta \le \frac{\pi}{2} \,;\, \frac{\pi}{3} \le \phi \le \frac{\pi}{2} \,;\, 0 \le \rho \le \sqrt{7}\right\}$$
* **Paso 3 (Planteamiento y cálculo del volumen):**
  Recordando que $dV = \rho^2\sin(\phi)\,d\rho\,d\phi\,d\theta$:
  $$V(E) = \iiint_E 1\,dV = \int_{\pi/4}^{\pi/2} \int_{\pi/3}^{\pi/2} \int_0^{\sqrt{7}} \rho^2\sin(\phi)\,d\rho\,d\phi\,d\theta$$
  Como los límites son constantes y el integrando es producto de funciones de variables separadas, integramos paso a paso:
  * Integral en $\rho$: $\int_0^{\sqrt{7}} \rho^2\,d\rho = \left[\frac{\rho^3}{3}\right]_0^{\sqrt{7}} = \frac{7\sqrt{7}}{3}$.
  * Integral en $\phi$: $\int_{\pi/3}^{\pi/2} \sin(\phi)\,d\phi = \Big[-\cos(\phi)\Big]_{\pi/3}^{\pi/2} = -\cos\left(\frac{\pi}{2}\right) - \left(-\cos\left(\frac{\pi}{3}\right)\right) = 0 + \frac{1}{2} = \frac{1}{2}$.
  * Integral en $\theta$: $\int_{\pi/4}^{\pi/2} 1\,d\theta = \frac{\pi}{2} - \frac{\pi}{4} = \frac{\pi}{4}$.
  Multiplicando los tres resultados:
  $$V(E) = \left(\frac{7\sqrt{7}}{3}\right) \cdot \left(\frac{1}{2}\right) \cdot \left(\frac{\pi}{4}\right) = \frac{7\sqrt{7}\pi}{24} \approx 2.424\text{ u}^3$$
* **Paso 4 (Densidad y planteamiento de la masa):**
  * La distancia al **plano $xz$** ($y=0$) en el primer octante es:
    $$\delta(x; y; z) = |y| = y$$
  * En coordenadas esféricas, $y = \rho\sin(\phi)\sin(\theta)$.
  * Multiplicando $\delta$ por el diferencial de volumen $\rho^2\sin(\phi)\,d\rho\,d\phi\,d\theta$:
    $$m(E) = \int_{\pi/4}^{\pi/2} \int_{\pi/3}^{\pi/2} \int_0^{\sqrt{7}} \underbrace{\left(\rho\sin(\phi)\sin(\theta)\right)}_{y} \cdot \underbrace{\rho^2\sin(\phi)\,d\rho\,d\phi\,d\theta}_{dV}$$
    $$m(E) = \int_{\pi/4}^{\pi/2} \int_{\pi/3}^{\pi/2} \int_0^{\sqrt{7}} \rho^3\sin^2(\phi)\sin(\theta)\,d\rho\,d\phi\,d\theta$$

#### 7. Respuesta Final
* $V(E) = \frac{7\sqrt{7}\pi}{24} \approx 2.42\text{ u}^3$
* $m(E) = \int_{\pi/4}^{\pi/2} \int_{\pi/3}^{\pi/2} \int_0^{\sqrt{7}} \rho^3\sin^2(\phi)\sin(\theta)\,d\rho\,d\phi\,d\theta$

#### 8. Verificación
En el integrando de la masa, la potencia de $\rho$ es $\rho^3$ ($\rho^1$ de $y$ más $\rho^2$ del jacobiano) y la potencia de $\sin(\phi)$ es $\sin^2(\phi)$ ($\sin\phi$ de $y$ más $\sin\phi$ del jacobiano). ¡Esta verificación de exponentes te permite acertar siempre en las preguntas de opción múltiple!

#### 9. Variación clave
Si el problema dijera que el sólido está **dentro** del semicono $z = \sqrt{\frac{x^2+y^2}{3}}$ y entre los planos $y = 0$ y $x = y$, entonces los límites cambiarían a $0 \le \phi \le \frac{\pi}{3}$ y $0 \le \theta \le \frac{\pi}{4}$.

---

### EJEMPLO RESUELTO 4 (Pregunta de Desarrollo de 5 Puntos: Modelación en Cilíndricas)
*(Basado en la Pregunta 5 del Examen 2025-10 V1 [Tanque Rotoplas], Pregunta 5 del 2026-10 y Ejercicio 05/24 del Banco)*

#### 1. Enunciado
Una empresa fabrica tanques de almacenamiento cuyo cuerpo inferior es un cilindro circular recto de $1.8\text{ metros}$ de diámetro y $2.2\text{ metros}$ de altura, coronado en su parte superior por un techo en forma de paraboloide circular de $0.6\text{ metros}$ de altura, alcanzando una altura total de $2.8\text{ metros}$. Considerando la base del tanque sobre el plano $xy$ centrada en el origen y el eje $z$ apuntando hacia arriba por el eje de simetría, la superficie del paraboloide tiene la forma $z = a + b(x^2 + y^2)$.
i. Determine las ecuaciones cartesianas que describen el cilindro y el paraboloide que conforman el tanque. ($1\text{ punto}$)
ii. Mostrando la gráfica de la proyección correspondiente, describa de manera ordenada la región sólida $E$ que encierra el tanque utilizando coordenadas cilíndricas. ($2\text{ puntos}$)
iii. Use coordenadas cilíndricas para plantear la integral triple iterada y calcular el volumen total que encierra el tanque. ($2\text{ puntos}$)

#### 2. Información proporcionada
* Diámetro de la base cilíndrica: $D = 1.8\text{ m} \implies \text{Radio } R = \frac{1.8}{2} = 0.9\text{ m}$.
* Altura de la pared cilíndrica: $h_{\text{cil}} = 2.2\text{ m}$.
* Altura adicional del techo parabólico: $h_{\text{techo}} = 0.6\text{ m} \implies \text{Altura máxima en el centro } z_{\text{máx}} = 2.2 + 0.6 = 2.8\text{ m}$.
* Modelo del paraboloide: $z = a + b(x^2 + y^2)$.

#### 3. ¿Qué se solicita?
Ecuaciones del cilindro y paraboloide, dibujo de la proyección en $xy$, descripción del sólido $E$ en cilíndricas y cálculo de su volumen con integrales triples.

#### 4. Concepto y procedimiento a utilizar
Modelación geométrica de superficies de revolución alrededor del eje $z$ y cálculo de volumen en **coordenadas cilíndricas** ($V = \iiint_E 1\,dV$ con $dV = r\,dz\,dr\,d\theta$).

#### 5 y 6. Desarrollo paso a paso y cálculos
* **Ítem i (Ecuaciones del cilindro y del paraboloide):**
  1. **Ecuación del cilindro circular recto ($S_1$):**
     Como el radio es $R = 0.9\text{ m}$ y su eje es el eje $z$:
     $$S_1: x^2 + y^2 = (0.9)^2 \implies x^2 + y^2 = 0.81$$
  2. **Ecuación del paraboloide ($S_2$):**
     * **Punto 1 (Cúspide central en el eje $z$):** Cuando $x = 0$ e $y = 0$, la altura es máxima e igual a $z = 2.8$. Reemplazando $(0; 0; 2.8)$ en $z = a + b(x^2+y^2)$:
       $$2.8 = a + b(0^2 + 0^2) \implies a = 2.8$$
     * **Punto 2 (Borde donde se une el cilindro con el techo):** Cuando nos alejamos una distancia igual al radio $R = 0.9$ (por ejemplo, el punto $(0; 0.9; 2.2)$), la altura es la del cilindro, $z = 2.2$. Reemplazando en $z = 2.8 + b(x^2+y^2)$:
       $$2.2 = 2.8 + b\left(0^2 + (0.9)^2\right) \implies -0.6 = 0.81 b \implies b = -\frac{0.6}{0.81} = -\frac{60}{81} = -\frac{20}{27}$$
     * Por lo tanto, la ecuación cartesiana del paraboloide es:
       $$S_2: z = 2.8 - \frac{20}{27}(x^2 + y^2)$$

* **Ítem ii (Proyección en el plano $xy$ y descripción en coordenadas cilíndricas):**
  * **Proyección:** Al proyectar todo el tanque hacia el plano $xy$ ($z = 0$), la sombra es el círculo lleno de radio $R = 0.9$ limitado por la circunferencia $x^2 + y^2 = 0.81$ (en polares: $0 \le r \le 0.9$ y $0 \le \theta \le 2\pi$).
  * **Variación de $z$ en cilíndricas:** El tanque empieza en la base plana sobre el piso ($z = 0$) y sube hasta topar con el techo paraboloide $z = 2.8 - \frac{20}{27}r^2$:
    $$E = \left\{(r; \theta; z) : 0 \le \theta \le 2\pi \,;\, 0 \le r \le 0.9 \,;\, 0 \le z \le 2.8 - \frac{20}{27}r^2\right\}$$

* **Ítem iii (Planteamiento y cálculo del volumen en coordenadas cilíndricas):**
  $$V(E) = \iiint_E 1\,dV = \int_0^{2\pi} \int_0^{0.9} \int_0^{2.8 - \frac{20}{27}r^2} r\,dz\,dr\,d\theta$$
  * **Paso 1 (Integrar respecto a $z$):**
    $$V(E) = \int_0^{2\pi} \int_0^{0.9} r \Big[ z \Big]_{z=0}^{z=2.8 - \frac{20}{27}r^2} dr\,d\theta = \int_0^{2\pi} \int_0^{0.9} \left(2.8r - \frac{20}{27}r^3\right) dr\,d\theta$$
  * **Paso 2 (Integrar respecto a $r$):**
    $$\int_0^{0.9} \left(2.8r - \frac{20}{27}r^3\right) dr = \left[ 1.4 r^2 - \frac{20}{108} r^4 \right]_0^{0.9} = 1.4(0.9)^2 - \frac{5}{27}(0.9)^4 = 1.134 - 0.1215 = 1.0125$$
  * **Paso 3 (Integrar respecto a $\theta$):**
    $$V(E) = \int_0^{2\pi} 1.0125\,d\theta = 1.0125(2\pi) = 2.025\pi = \frac{81\pi}{40}\text{ m}^3 \approx 6.36\text{ m}^3$$

#### 7. Respuesta Final
* Cilindro: $x^2 + y^2 = 0.81$; Paraboloide: $z = 2.8 - \frac{20}{27}(x^2 + y^2)$.
* $E = \left\{(r; \theta; z) : 0 \le \theta \le 2\pi \,;\, 0 \le r \le 0.9 \,;\, 0 \le z \le 2.8 - \frac{20}{27}r^2\right\}$.
* Volumen del tanque: $V(E) \approx 6.36\text{ m}^3$.

#### 8. Verificación física y geométrica rápida (Truco de Control de Calidad en el Examen)
¡Puedes comprobar tu respuesta en $15\text{ segundos}$ usando geometría escolar!
* El volumen de un cilindro de radio $R = 0.9$ y altura $h_1 = 2.2$ es:
  $$V_{\text{cil}} = \pi R^2 h_1 = \pi (0.9)^2 (2.2) = 1.782\pi$$
* Propiedad de Arquímedes: El volumen de un casquete de paraboloide es exactamente **la mitad** del cilindro que lo circunscribe ($\frac{1}{2}\pi R^2 h_2$):
  $$V_{\text{parab}} = \frac{1}{2}\pi (0.9)^2 (0.6) = 0.243\pi$$
* Sumando ambos: $V_{\text{total}} = 1.782\pi + 0.243\pi = 2.025\pi \approx 6.36\text{ m}^3$. ¡Exactamente igual al resultado de nuestra integral triple!
*(Del mismo modo, si el tanque tiene una parte cónica de radio $R$ y altura $h_{\text{cono}}$, su volumen geométrico es $\frac{1}{3}\pi R^2 h_{\text{cono}}$; úsalo siempre para verificar que tu integral triple sea $100\%$ correcta antes de entregar el examen).*

---

## SECCIÓN E. GRÁFICOS, DIAGRAMAS Y RECURSOS VISUALES

### E.1. Árbol de Decisión Maestro: ¿Qué Sistema de Coordenadas Debo Elegir?

```
                     [ ¿QUÉ TIPO DE INTEGRAL TIENES EN EL PROBLEMA? ]
                                            |
            +-------------------------------+-------------------------------+
            |                                                               |
   [ INTEGRAL DOBLE (2D) ]                                        [ INTEGRAL TRIPLE (3D) ]
     (Región plana D)                                                (Sólido espacial E)
            |                                                               |
   ¿Las curvas tienen x^2 + y^2,                         ¿Qué superficies limitan al sólido E?
   circunferencias o cardioides?                                            |
       /                 \                        +-------------------------+-------------------------+
     SÍ                   NO                      |                         |                         |
     /                     \              [Esferas centradas        [Cilindros circulares,    [Cilindros parabólicos
[COORDENADAS          [COORDENADAS         x^2+y^2+z^2 = R^2         paraboloides z = a+br^2   (ej. x^2+z=4, z=16-x^2)
  POLARES]             CARTESIANAS]        + Conos o Planos]         o semiconos z = a+br]     y planos inclinados]
x = r cos(\theta)     Tipo I: dy dx               |                         |                         |
y = r sin(\theta)     (barrido vertical)  [COORDENADAS ESFÉRICAS]   [COORDENADAS CILÍNDRICAS] [COORDENADAS CARTESIANAS]
dA = r dr d\theta     Tipo II: dx dy      (\rho; \theta; \phi)      (r; \theta; z)            (x; y; z)
                      (barrido horiz.)    dV = \rho^2 sin(\phi)     dV = r dz dr d\theta      Proyectar sobre el plano
                                               d\rho d\phi d\theta                            de las 2 letras del cilindro
```

---

### E.2. Esquema Visual Comparativo: Barrido Tipo I ($dy\,dx$) vs. Tipo II ($dx\,dy$)

```
   REGIÓN TIPO I (Barrido Vertical: dy dx)              REGIÓN TIPO II (Barrido Horizontal: dx dy)
   x fijo entre constantes: a <= x <= b                 y fijo entre constantes: c <= y <= d
   y entra por piso g1(x) y sale por techo g2(x)        x entra por izq. h1(y) y sale por der. h2(y)

        y ^                                                  y ^
          |        Techo: y = g2(x)                            |      d +------------------+
          |         .----------.                               |        |  x = h1(y)       | x = h2(y)
          |        /     ^      \                              |        |    (Izq.)        |  (Der.)
          |       |      |       |                             |        |      o---------->o
          |       |      | Flecha|                             |        |     Flecha horiz.|
          |        \     o      /                              |      c +------------------+
          |         '----------'                               |
          |        Piso: y = g1(x)                             |
        --+--------+------------+---> x                      --+---------------------------> x
          0        a            b                              0
```
* **Interpretación del diagrama:** Nunca mezcles flechas verticales con límites horizontales. Si tu integral termina en $dy\,dx$, la flecha imaginaria es **vertical** ($\uparrow$); si termina en $dx\,dy$, la flecha es **horizontal** ($\to$).

---

### E.3. Geometría de las Coordenadas Esféricas $(\rho; \theta; \phi)$ y el Significado de $\phi$

```
                         Eje +z (Polo Norte: \phi = 0)
                           ^
                           |     / Cono: \phi = \alpha (ej. \pi/6 o \pi/3)
                           |    /
                           | \phi /   P(x; y; z)
                           |<->/   o
                           |  /   /|
                           | / \rho/ |
                           |/   /  | z = \rho cos(\phi)
                           +---/---+-----------------> Eje +y (\theta = \pi/2)
                          /   /   /
                         / \theta /   r = \rho sin(\phi)
                        / <->/  /
                       v    v  /
                    Eje +x (\theta = 0)     (Plano xy: Ecuador \phi = \pi/2)
```
* **Lectura visual para evitar el error más común del examen:**
  * Si el sólido está **dentro/encima del semicono** $\phi = \alpha$: se encuentra pegado al eje $+z$, por lo que $\phi$ va desde $0$ hasta $\alpha$ ($0 \le \phi \le \alpha$).
  * Si el sólido está **fuera/debajo del semicono** $\phi = \alpha$ y sobre el plano $xy$: se encuentra entre las flechas del cono y el piso, por lo que $\phi$ va desde $\alpha$ hasta $\frac{\pi}{2}$ ($\alpha \le \phi \le \frac{\pi}{2}$).

---

### E.4. Esquema de los 3 Modelos de Tanques de la Pregunta 5 (Parte 2 del Examen)

```
  MODELO 1: TANQUE CON TECHO            MODELO 2: TOLVA O DECANTADOR         MODELO 3: COPA O BALÓN CON
  PARABOLOIDE O SEMICONO                CON BASE CÓNICA INVERTIDA            CASQUETE ESFÉRICO
  (Ej. 05, 24 y Examen 2025-10 V1)      (Examen 2026-10 y 2025-10 V2)        (Ej. 25 Solgas y Ej. 26 GeoTanque)

            z ^                                   z ^                                  z ^
              |   ._(0; 0; H_max)                   |                                    |    .---. (0; 0; R_esf)
        h_2   |  / \  Techo:                        |  +-------+ z = H_max (Tapa)        |   /     \ Esfera:
              | /   \ z = a + b r^2                 |  |       |                         |  +-------+ z = sqrt(a - r^2)
              |+-----+ (0; R; h_1)             h_2  |  |       | Cilindro: r = R         |   \     /
              ||     |                              |  +-------+ (0; R; h_1)             |    \   /  Semicono:
        h_1   ||     | Cilindro: r = R         h_1  |   \     /  Semicono:               |     \ /   z = b*r
              ||     |                              |    \   /   z = k*r                 |      V
        ------+------+------> y               ------+-----V----+------> y          ------+------+------> y
              | Piso: z = 0                         | (0; 0; 0)                          |  (0; 0; 0)
              |<--R->|                              |   <-R->                            |
        Límites de z:                         Límites de z:                        Límites de z:
     0 <= z <= a + b*r^2                      k*r <= z <= H_max                   b*r <= z <= sqrt(a - r^2)
```

---

## SECCIÓN F. EJERCICIOS PARA RESOLVER POR TU CUENTA (PRÁCTICA PROGRESIVA)

Resuelve cada bloque sin mirar las soluciones. Al terminar, contrasta tu razonamiento con el **Solucionario Explicado** al final de esta sección.

---

### NIVEL 1 — FUNDAMENTOS (Reconocimiento y Aplicación Directa)

* **Ejercicio F.1 [Habilidad: Diccionario de densidades 2D y 3D]:**
  Escriba la función de densidad $\delta$ en coordenadas cartesianas, cilíndricas y esféricas (según corresponda) para cada enunciado en el primer cuadrante/octante:
  a) En una placa plana, la densidad en cada punto $(x; y)$ es numéricamente igual al triple de la distancia al eje $x$.
  b) En un sólido $E$, la densidad en cada punto $(x; y; z)$ es numéricamente igual a la mitad de la distancia al plano $yz$.
  c) En un sólido $E$, la densidad en cada punto $(x; y; z)$ es numéricamente igual al doble de la distancia al eje $z$.

* **Ejercicio F.2 [Habilidad: Conversión y descripción básica en coordenadas esféricas]:**
  Sea $E$ el sólido en el primer octante acotado por la esfera $x^2 + y^2 + z^2 = 25$, dentro del semicono $z = \sqrt{x^2 + y^2}$ y entre los planos $y = 0$ e $y = \sqrt{3}x$.
  a) Exprese las ecuaciones de la esfera, el semicono y el plano $y = \sqrt{3}x$ en coordenadas esféricas.
  b) Describa el sólido $E$ de forma ordenada en coordenadas esféricas.

* **Ejercicio F.3 [Habilidad: Cálculo de área en coordenadas cartesianas]:**
  Considerando la descripción ordenada de la región plana $R = \left\{(x; y) \in \mathbb{R}^2 : -1 \le x \le 2 \,;\, x^2 + 2 \le y \le 8\right\}$, plantee la integral iterada que permite calcular el área de la región $R$ y determine su valor exacto.

---

### NIVEL 2 — APLICACIÓN (Combinación de Pasos y Selección de Estrategia)

* **Ejercicio F.4 [Habilidad: Inversión del orden de integración y evaluación]:**
  Dada la integral iterada:
  $$I = \int_0^2 \int_{y^2}^4 y\cos(x^2)\,dx\,dy$$
  a) Describa la región de integración original y grafíquela.
  b) Plantee la integral iterada invirtiendo el orden de integración.
  c) Calcule paso a paso el valor exacto de la integral.

* **Ejercicio F.5 [Habilidad:Transformación de integral doble a coordenadas polares]:**
  Plantee en coordenadas polares y calcule el valor de la siguiente integral:
  $$I = \int_0^2 \int_0^{\sqrt{4x - x^2}} \sqrt{x^2 + y^2}\,dy\,dx$$
  *(En su proceso: describa la región en cartesianas, complete cuadrados para graficar la curva frontera, describa la región en coordenadas polares y evalúe la integral).*

* **Ejercicio F.6 [Habilidad: Volumen entre superficies cuádricas en coordenadas cilíndricas]:**
  Sea $E$ el sólido limitado inferiormente por el paraboloide $z = 3x^2 + 3y^2$ y superiormente por el paraboloide $z = 16 - x^2 - y^2$.
  a) Exprese las ecuaciones de ambas superficies en coordenadas cilíndricas y halle el radio de su curva de intersección.
  b) Describa el sólido $E$ en coordenadas cilíndricas.
  c) Plantee la integral iterada del volumen de $E$ y calcule su valor.

---

### NIVEL 3 — NIVEL EXAMEN (Formato y Dificultad Oficial UPC)

* **Ejercicio F.7 [Habilidad: Placa polar entre cardioide y circunferencia — Estilo Parte 1 UPC]:**
  Una placa delgada tiene la forma de la región $D$ situada en el semiplano superior ($y \ge 0$), que se encuentra **fuera** de la circunferencia $C_1: x^2 + y^2 = 4$ y **dentro** del cardioide $C_2: r = 2 + 2\sin(\theta)$.
  i. Halle los ángulos de intersección y describa la región $D$ de forma ordenada en coordenadas polares.
  ii. Plantee la integral iterada que permite calcular el área de la placa $D$ y calcule su valor numérico.
  iii. Si la densidad superficial $\delta$ en cualquier punto $(x; y)$ es numéricamente igual a la distancia de dicho punto al eje $x$, plantee la integral iterada en coordenadas polares que permite calcular la masa de la placa.

* **Ejercicio F.8 [Habilidad: Sólido cartesiano proyectado en el plano $xz$ — Estilo Parte 1 UPC]:**
  Sea $E$ el sólido en el primer octante delimitado por la superficie cilíndrica parabólica $S_1: z = 9 - x^2$ y los planos $S_2: 2x + y + z = 12$, $S_3: x = 0$, $S_4: y = 0$ y $S_5: z = 0$.
  i. Describa ordenadamente el sólido $E$ proyectándolo sobre el **plano $xz$**.
  ii. Si la densidad del sólido en cada punto $(x; y; z)$ es numéricamente igual a la distancia del punto al plano $xy$, plantee la integral iterada que permite calcular la masa del sólido $E$.

* **Ejercicio F.9 [Habilidad: Modelación de Tanque Industrial — Estilo Parte 2 Desarrollo UPC]:**
  Un silo para almacenamiento de cemento consta de una tolva inferior en forma de semicono invertido de $3\text{ metros}$ de altura acoplada a un cuerpo cilíndrico vertical de $4\text{ metros}$ de diámetro y $5\text{ metros}$ de altura, cerrado en su parte superior por un techo plano horizontal. Ubicando el vértice del semicono en el origen de coordenadas $(0; 0; 0)$ y el eje $z$ a lo largo del eje central del silo, la superficie cónica se modela mediante $z = k\sqrt{x^2 + y^2}$.
  a) Determine las ecuaciones cartesianas del cilindro, del semicono y del plano del techo.
  b) Grafique la proyección sobre el plano $xy$ y describa ordenadamente el sólido $E$ en coordenadas cilíndricas.
  c) Calcule mediante integrales triples en coordenadas cilíndricas el volumen total del silo.

---

### SOLUCIONARIO EXPLICADO DE LOS EJERCICIOS DE PRÁCTICA (SECCIÓN F)

#### Solución del Ejercicio F.1 (Nivel 1)
* **a)** En 2D, la distancia al eje $x$ es $|y| = y$ (en el 1er cuadrante). El triple es:
  $$\delta(x; y) = 3y \quad \text{(En polares: } \delta = 3r\sin\theta\text{)}$$
* **b)** En 3D, la distancia al plano $yz$ ($x=0$) es $|x| = x$ (en el 1er octante). La mitad es:
  $$\delta(x; y; z) = \frac{1}{2}x \quad \text{(En cilíndricas: } \frac{1}{2}r\cos\theta \,;\, \text{En esféricas: } \frac{1}{2}\rho\sin\phi\cos\theta\text{)}$$
* **c)** En 3D, la distancia al eje $z$ es $\sqrt{x^2 + y^2}$. El doble es:
  $$\delta(x; y; z) = 2\sqrt{x^2 + y^2} \quad \text{(En cilíndricas: } 2r \,;\, \text{En esféricas: } 2\rho\sin\phi\text{)}$$

#### Solución del Ejercicio F.2 (Nivel 1)
* **a)**
  * Esfera: $x^2 + y^2 + z^2 = 25 \iff \rho^2 = 25 \implies \rho = 5$.
  * Semicono: $z = \sqrt{x^2 + y^2} \implies \frac{\sqrt{x^2+y^2}}{z} = 1 \implies \tan\phi = 1 \implies \phi = \frac{\pi}{4}$.
  * Plano: $y = \sqrt{3}x \implies \frac{y}{x} = \sqrt{3} \implies \tan\theta = \sqrt{3} \implies \theta = \frac{\pi}{3}$.
* **b)** Como está *dentro* del semicono, $\phi$ va desde el eje $+z$ ($\phi=0$) hasta $\phi = \frac{\pi}{4}$. Entre $y=0$ ($\theta=0$) e $y=\sqrt{3}x$ ($\theta=\frac{\pi}{3}$):
  $$E = \left\{(\rho; \theta; \phi) : 0 \le \theta \le \frac{\pi}{3} \,;\, 0 \le \phi \le \frac{\pi}{4} \,;\, 0 \le \rho \le 5\right\}$$

#### Solución del Ejercicio F.3 (Nivel 1)
Planteamos el área integrando la función $1$:
$$A(R) = \int_{-1}^2 \int_{x^2+2}^8 1\,dy\,dx = \int_{-1}^2 \Big(8 - (x^2 + 2)\Big) dx = \int_{-1}^2 (6 - x^2)\,dx$$
$$A(R) = \left[6x - \frac{x^3}{3}\right]_{-1}^2 = \left(12 - \frac{8}{3}\right) - \left(-6 - \frac{-1}{3}\right) = \frac{28}{3} - \left(-\frac{17}{3}\right) = \frac{45}{3} = 15\text{ u}^2$$

#### Solución del Ejercicio F.4 (Nivel 2)
* **a)** De los límites dados: $D_1 = \left\{(x; y) \in \mathbb{R}^2 : 0 \le y \le 2 \,;\, y^2 \le x \le 4\right\}$.
  Las curvas son la parábola $x = y^2$ (o $y = \sqrt{x}$ en el primer cuadrante) y la recta vertical $x = 4$, con $y \ge 0$.
* **b)** Para invertir a $dy\,dx$ (barrido vertical), observamos que $x$ va desde $x = 0$ hasta $x = 4$. Para cada $x$, la altura $y$ entra por el eje $x$ ($y = 0$) y sale por la parábola $y = \sqrt{x}$:
  $$D_2 = \left\{(x; y) \in \mathbb{R}^2 : 0 \le x \le 4 \,;\, 0 \le y \le \sqrt{x}\right\}$$
  $$I = \int_0^4 \int_0^{\sqrt{x}} y\cos(x^2)\,dy\,dx$$
* **c)** Integramos primero respecto a $y$:
  $$I = \int_0^4 \cos(x^2) \left[\frac{y^2}{2}\right]_0^{\sqrt{x}} dx = \int_0^4 \frac{x}{2}\cos(x^2)\,dx$$
  Haciendo sustitución $u = x^2 \implies du = 2x\,dx \implies \frac{x}{2}\,dx = \frac{1}{4}\,du$:
  $$I = \left[\frac{1}{4}\sin(x^2)\right]_0^4 = \frac{\sin(16) - \sin(0)}{4} = \frac{\sin(16)}{4} \approx -0.072$$

#### Solución del Ejercicio F.5 (Nivel 2)
* **Paso 1:** $D = \left\{(x; y) \in \mathbb{R}^2 : 0 \le x \le 2 \,;\, 0 \le y \le \sqrt{4x - x^2}\right\}$.
* **Paso 2:** De $y = \sqrt{4x - x^2}$ con $y \ge 0$, elevamos al cuadrado:
  $$x^2 + y^2 = 4x \iff (x - 2)^2 + y^2 = 4$$
  Es una circunferencia de centro $(2; 0)$ y radio $2$. Pero atención: como $0 \le x \le 2$ y $y \ge 0$, solo tomamos el **cuarto de círculo izquierdo superior** (desde $x = 0$ hasta el centro $x = 2$, donde $y = 2$).
* **Paso 3 (Límites en polares):**
  * La circunferencia $x^2 + y^2 = 4x$ en polares es $r^2 = 4r\cos\theta \implies r = 4\cos\theta$.
  * La recta vertical $x = 2$ corta a la circunferencia en el punto $(2; 2)$, donde $\tan\theta = \frac{2}{2} = 1 \implies \theta = \frac{\pi}{4}$.
  * Sin embargo, observa con mucho cuidado: si $0 \le x \le 2$, la frontera derecha es la recta vertical $x = 2$ (para $0 \le \theta \le \frac{\pi}{4}$) y el arco de circunferencia $r = 4\cos\theta$ va desde $(2; 2)$ ($\theta = \frac{\pi}{4}$) hasta el origen $(0; 0)$ ($\theta = \frac{\pi}{2}$)!
  * *Nota pedagógica:* Si el problema original iba hasta el diámetro completo $\int_0^4 \int_0^{\sqrt{4x-x^2}}$, entonces toda la frontera es $r = 4\cos\theta$ para $0 \le \theta \le \frac{\pi}{2}$. Para nuestro ejercicio con $0 \le x \le 2$, el arco curvo está en $\frac{\pi}{4} \le \theta \le \frac{\pi}{2}$ ($0 \le r \le 4\cos\theta$) y el triángulo inferior en $0 \le \theta \le \frac{\pi}{4}$ ($0 \le r \le 2\sec\theta$). Si en cambio consideramos el semicírculo completo $0 \le x \le 4$:
    $$I_{\text{semicírculo}} = \int_0^{\pi/2} \int_0^{4\cos\theta} (r)\cdot r\,dr\,d\theta = \int_0^{\pi/2} \frac{64\cos^3\theta}{3}\,d\theta = \frac{64}{3}\left(\frac{2}{3}\right) = \frac{128}{9} \approx 14.22$$

#### Solución del Ejercicio F.6 (Nivel 2)
* **a)** En cilíndricas ($x^2+y^2 = r^2$):
  * Paraboloide inferior: $z = 3r^2$.
  * Paraboloide superior: $z = 16 - r^2$.
  * Intersección: $3r^2 = 16 - r^2 \implies 4r^2 = 16 \implies r^2 = 4 \implies r = 2$.
* **b)** $E = \left\{(r; \theta; z) : 0 \le \theta \le 2\pi \,;\, 0 \le r \le 2 \,;\, 3r^2 \le z \le 16 - r^2\right\}$.
* **c)** Volumen:
  $$V(E) = \int_0^{2\pi} \int_0^2 \int_{3r^2}^{16-r^2} r\,dz\,dr\,d\theta = \int_0^{2\pi} \int_0^2 r(16 - 4r^2)\,dr\,d\theta = 2\pi \left[8r^2 - r^4\right]_0^2 = 2\pi(32 - 16) = 32\pi \approx 100.53\text{ u}^3$$

#### Solución del Ejercicio F.7 (Nivel 3)
* **i.** Circunferencia $C_1: x^2 + y^2 = 4 \implies r = 2$.
  Intersección con $C_2: r = 2 + 2\sin\theta$:
  $$2 + 2\sin\theta = 2 \implies 2\sin\theta = 0 \implies \sin\theta = 0 \implies \theta = 0 \quad \text{y} \quad \theta = \pi$$
  Descripción ordenada:
  $$D = \left\{(r; \theta) : 0 \le \theta \le \pi \,;\, 2 \le r \le 2 + 2\sin(\theta)\right\}$$
* **ii.** Área de la placa:
  $$A(D) = \int_0^\pi \int_2^{2+2\sin\theta} r\,dr\,d\theta = \frac{1}{2} \int_0^\pi \left((2+2\sin\theta)^2 - 2^2\right) d\theta = \frac{1}{2} \int_0^\pi (8\sin\theta + 4\sin^2\theta)\,d\theta = 8 + \pi \approx 11.14\text{ u}^2$$
* **iii.** Distancia al eje $x$ en el semiplano superior ($y \ge 0$): $\delta(x; y) = y = r\sin\theta$.
  Multiplicando por el jacobiano $r$:
  $$m(D) = \int_0^\pi \int_2^{2+2\sin\theta} (r\sin\theta) r\,dr\,d\theta = \int_0^\pi \int_2^{2+2\sin\theta} r^2\sin(\theta)\,dr\,d\theta$$

#### Solución del Ejercicio F.8 (Nivel 3)
* **i.** Proyectamos sobre el **plano $xz$** ($y = 0$). En el primer octante ($x \ge 0, z \ge 0$), la parábola $z = 9 - x^2$ corta al eje $x$ en $x = 3$ y al eje $z$ en $z = 9$.
  La variable $y$ (perpendicular al plano $xz$) va desde el plano $y = 0$ hasta el plano inclinado $2x + y + z = 12 \implies y = 12 - 2x - z$:
  $$E = \left\{(x; y; z) \in \mathbb{R}^3 : 0 \le x \le 3 \,;\, 0 \le z \le 9 - x^2 \,;\, 0 \le y \le 12 - 2x - z\right\}$$
* **ii.** La distancia al plano $xy$ ($z = 0$) es $\delta(x; y; z) = z$. La integral iterada de la masa es:
  $$m(E) = \int_0^3 \int_0^{9-x^2} \int_0^{12-2x-z} z\,dy\,dz\,dx$$

#### Solución del Ejercicio F.9 (Nivel 3)
* **a)**
  * Diámetro $D = 4\text{ m} \implies \text{Radio } R = 2\text{ m}$. Ecuación del cilindro: $x^2 + y^2 = 4$.
  * Semicono: En $r = 2$, la altura del semicono es $z = 3\text{ m}$. Reemplazando $(0; 2; 3)$ en $z = k\sqrt{x^2+y^2}$:
    $$3 = k(2) \implies k = \frac{3}{2} = 1.5 \implies z = 1.5\sqrt{x^2 + y^2}$$
  * Techo plano: Altura total = $3\text{ m (cono)} + 5\text{ m (cilindro)} = 8\text{ m} \implies z = 8$.
* **b)** Proyección en el plano $xy$: círculo $x^2 + y^2 \le 4$ ($0 \le r \le 2$, $0 \le \theta \le 2\pi$).
  Descripción ordenada en cilíndricas:
  $$E = \left\{(r; \theta; z) : 0 \le \theta \le 2\pi \,;\, 0 \le r \le 2 \,;\, 1.5r \le z \le 8\right\}$$
* **c)** Volumen en coordenadas cilíndricas:
  $$V(E) = \int_0^{2\pi} \int_0^2 \int_{1.5r}^8 r\,dz\,dr\,d\theta = \int_0^{2\pi} \int_0^2 \left(8r - 1.5r^2\right) dr\,d\theta$$
  $$V(E) = 2\pi \left[4r^2 - 0.5r^3\right]_0^2 = 2\pi (16 - 4) = 24\pi \approx 75.40\text{ m}^3$$
  *(Verificación geométrica: $V_{\text{cil}} + V_{\text{cono}} = \pi(2^2)(5) + \frac{1}{3}\pi(2^2)(3) = 20\pi + 4\pi = 24\pi$. ¡Correcto!).*

---

## SECCIÓN G. PREPARACIÓN ESPECÍFICA PARA EL BANCO DE PREGUNTAS (`Resueltos EU2`)

En esta sección conectamos directamente el banco de preguntas de $34\text{ páginas}$ que compartiste con las secciones teóricas de esta guía, incluyendo la **Tabla de Trazabilidad Completa** y la **Auditoría de Correcciones** a los apuntes manuscritos de ese PDF.

---

### G.1. Tabla de Trazabilidad del Banco de Preguntas (`Resueltos EU2`)

| N.º de Ejercicio en el Banco | Tema Evaluado | Habilidad de la Matriz EU2 | Sección de Teoría de esta Guía | Patrón de Resolución Clave |
| :--- | :--- | :--- | :--- | :--- |
| **Ej. 01** y **Ej. 06 (a, d, e, f, g, k, l)** | Integrales dobles en cartesianas (Cambio de orden) | Calcula integrales dobles cambiando el orden de integración y grafica la región. | Tema 1 (C.1) y Ejemplo D.1 | Extraer $D_1$, graficar, despejar la otra variable cuidando el signo de la raíz según el cuadrante, re-escanear para hallar $D_2$ e integrar. |
| **Ej. 02** y **Ej. 11** | Polares con circunferencia desplazada y rectas | Describe regiones polares, calcula área y masa de placa plana. | Tema 2 (C.2) y Tema 3 (C.3) | Pasar $x^2+y^2=4x \to r=4\cos\theta$ (o $4y \to 4\sin\theta$), pasar rectas $y=mx \to \theta=\arctan(m)$, usar $dA = r\,dr\,d\theta$. |
| **Ej. 03, 17, 19, 22, 23** | Integrales triples en coordenadas esféricas | Describe regiones en esféricas, calcula volumen y masa de sólidos. | Tema 6 (C.6) y Ejemplo D.3 | Convertir esfera a $\rho=R$, semicono a $\phi=\alpha$, planos $y=mx$ a $\theta=\beta$, plano $z=c$ a $\rho=c\sec\phi$, usar $dV=\rho^2\sin\phi\,d\rho\,d\phi\,d\theta$. |
| **Ej. 04** y **Ej. 14** | Integrales triples en coordenadas cilíndricas (sólidos puros) | Selecciona coordenadas cilíndricas para calcular integrales triples y volúmenes. | Tema 5 (C.5) | Igualar superficies en función de $r$ para hallar el radio máximo de proyección y mantener $z$ como variable en el integrando. |
| **Ej. 05, 24, 25, 26, 27** | Modelación real con integrales triples en cilíndricas | Aplicaciones de la integral triple en casos reales (tanques, balones, wok). | Tema 5 (C.5) y Ejemplo D.4 | Usar puntos del perfil $(0;0;z_{\text{eje}})$ y $(0;R;z_{\text{borde}})$ para hallar constantes, proyectar el círculo base y plantear $V=\iiint r\,dz\,dr\,d\theta$. |
| **Ej. 07 (a, b, c)** | Transformación de cartesianas a polares | Calcula integrales dobles pasando de cartesianas a polares. | Tema 2 (C.2) y Ejercicio F.5 | Identificar la ecuación de la circunferencia desde la raíz en el límite, determinar el cuadrante y multiplicar por el jacobiano $r$. |
| **Ej. 08 (a, b, c, d)** | Área polar entre circunferencia y cardioide | Calcula el área de una región plana en coordenadas polares. | Tema 2 (C.2), Tema 3 y Ejemplo D.2 | Igualar $r_1(\theta) = r_2(\theta)$ para hallar los ángulos de corte y plantear $\int_\alpha^\beta \int_{r_{\text{in}}}^{r_{\text{ext}}} r\,dr\,d\theta$. |
| **Ej. 09** y **Ej. 10** | Área y masa en cartesianas / Volumen bajo cilindro parabólico | Calcula área, masa en cartesianas y volumen con integral triple rectangular. | Tema 1, Tema 3 y Tema 4 (C.4) | En Ej. 09: $0 \le z \le 16-x^2$ sobre el trapecio 2D. En Ej. 10: usar Tipo II ($dx\,dy$) desde la parábola $x=y^2$ hasta la recta $x=y+2$. |

---

### G.2. Auditoría y Corrección de los Errores en los Apuntes del PDF `Resueltos EU2`
Para que puedas estudiar el PDF de repaso sin confundirte con los errores del cuaderno escaneado, aquí tienes las **correcciones exactas**:

1. **Corrección del Ejercicio $6\text{k}$ (Página 12 del PDF):**
   * **Integral original:** $\int_{-6}^0 \int_{25 - x^2/4}^{25} y e^{y-25}\,dy\,dx$.
   * **Error en el cuaderno del PDF:** Como $-6 \le x \le 0$, la región está en el **Segundo Cuadrante** ($x \le 0$). Al despejar $x$ de $y = 25 - \frac{x^2}{4} \implies x^2 = 4(25 - y)$, la rama izquierda tiene signo negativo: $x = -\sqrt{4(25 - y)} = -2\sqrt{25 - y}$. En el cuaderno pusieron $-6 \le x \le +\sqrt{4(25-y)}$, lo cual es geométricamente falso.
   * **Solución correcta:** En la región sombreada, a la izquierda está la recta vertical $x = -6$ y a la derecha está la curva $x = -2\sqrt{25 - y}$:
     $$D_2 = \left\{(x; y) \in \mathbb{R}^2 : 16 \le y \le 25 \,;\, -6 \le x \le -2\sqrt{25 - y}\right\}$$
     $$I = \int_{16}^{25} \int_{-6}^{-2\sqrt{25-y}} y e^{y-25}\,dx\,dy = \int_{16}^{25} y e^{y-25} \left(-2\sqrt{25-y} - (-6)\right) dy = \int_{16}^{25} y e^{y-25}\left(6 - 2\sqrt{25-y}\right) dy$$

2. **Corrección del Ejercicio $6\text{l}$ (Página 13 del PDF):**
   * Ya lo resolvimos impecablemente en nuestro **Ejemplo Resuelto 1 (Sección D)**: el límite de $x$ es $-3\sqrt{4-y} \le x \le 0$ y el valor correcto es $+0.865$ (no $-0.865$).

3. **Corrección del Ejercicio $14$ (Página 24 del PDF):**
   * **Enunciado:** Sólido $E$ limitado inferiormente por el plano $xy$ ($z=0$), exterior al semicono $S_1: z = \sqrt{2x^2+2y^2} = \sqrt{2}r$ e interior al cilindro $S_2: x^2+y^2 = 8$ ($r = \sqrt{8} = 2\sqrt{2}$). Plantear la integral iterada que permite calcular $\iiint_E z(x^2 + y^2)\,dV$.
   * **Error en el cuaderno del PDF:** El alumno escribió en el integrando $\sqrt{2}r \cdot r^2 \cdot r\,dz\,dr\,d\theta$, reemplazando la variable $z$ del integrando por el límite superior $\sqrt{2}r$.
   * **Solución correcta:** En coordenadas cilíndricas, la coordenada $z$ es una variable independiente ($z = z$) y $x^2 + y^2 = r^2$. Por lo tanto, el integrando es $z \cdot r^2$, que multiplicado por el jacobiano $r$ da $z r^3$:
     $$\iiint_E z(x^2 + y^2)\,dV = \int_0^{2\pi} \int_0^{2\sqrt{2}} \int_0^{\sqrt{2}r} (z r^2) \cdot r\,dz\,dr\,d\theta = \int_0^{2\pi} \int_0^{2\sqrt{2}} \int_0^{\sqrt{2}r} z r^3\,dz\,dr\,d\theta$$

4. **Corrección del Ejercicio $19$ (Página 26 del PDF):**
   * **Enunciado:** Calcular $\iiint_E (x^2+y^2+z^2)\,dV$ donde $E = \left\{(\rho; \theta; \phi) : 0 \le \theta \le \frac{\pi}{2} \,;\, 0 \le \phi \le \frac{\pi}{4} \,;\, 1 \le \rho \le 4\right\}$.
   * **Error en el cuaderno del PDF:** Al integrar respecto a $\theta$, confundieron $\sin\phi$ con $\sin\theta$.
   * **Solución correcta paso a paso:**
     $$I = \int_0^{\pi/2} \int_0^{\pi/4} \int_1^4 (\rho^2) \cdot \rho^2\sin(\phi)\,d\rho\,d\phi\,d\theta = \int_0^{\pi/2} \int_0^{\pi/4} \int_1^4 \rho^4\sin(\phi)\,d\rho\,d\phi\,d\theta$$
     * En $\rho$: $\left[\frac{\rho^5}{5}\right]_1^4 = \frac{1024 - 1}{5} = \frac{1023}{5}$.
     * En $\phi$: $\int_0^{\pi/4} \sin(\phi)\,d\phi = \Big[-\cos(\phi)\Big]_0^{\pi/4} = 1 - \frac{\sqrt{2}}{2}$.
     * En $\theta$: $\int_0^{\pi/2} 1\,d\theta = \frac{\pi}{2}$.
     * Resultado exacto: $I = \frac{1023\pi}{10}\left(1 - \frac{\sqrt{2}}{2}\right) \approx 94.13$.

5. **Corrección del Ejercicio $22\text{b}$ y $22\text{c}$ (Página 27 del PDF — que faltaban en el cuaderno):**
   * **Enunciado:** Sólido $E$ en el primer octante dentro del semicono $z = \sqrt{3x^2+3y^2} = \sqrt{3}r$, debajo de la semiesfera $z = \sqrt{12-x^2-y^2} = \sqrt{12-r^2}$, y entre $y=0$ ($\theta=0$) e $y=(2-\sqrt{3})x$ ($\theta = \frac{\pi}{12}$).
   * **Solución del ítem b (Volumen en coordenadas cilíndricas):**
     Intersección cono-esfera: $(\sqrt{3}r)^2 = 12 - r^2 \implies 3r^2 + r^2 = 12 \implies 4r^2 = 12 \implies r = \sqrt{3}$.
     Como está *dentro* del cono y *debajo* de la esfera, el piso es el cono $z = \sqrt{3}r$ y el techo es la esfera $z = \sqrt{12 - r^2}$:
     $$V(E) = \int_0^{\pi/12} \int_0^{\sqrt{3}} \int_{\sqrt{3}r}^{\sqrt{12-r^2}} r\,dz\,dr\,d\theta$$
   * **Solución del ítem c (Masa con densidad $\delta$ = distancia al origen):**
     En esféricas, $\delta = \sqrt{x^2+y^2+z^2} = \rho$. Multiplicando por $\rho^2\sin\phi$:
     $$m(E) = \int_0^{\pi/12} \int_0^{\pi/6} \int_0^{\sqrt{12}} \rho^3\sin(\phi)\,d\rho\,d\phi\,d\theta$$

6. **Corrección del Ejercicio $25\text{b}$ (Páginas 30 y 31 del PDF — Balón Solgas):**
   * En el balón de gas, el casquete inferior tiene centro en $(0; 0; 221)$ y radio $221$, tocando el piso en $z = 0$. Al despejar $z$ de $(z - 221)^2 = 221^2 - r^2$, como el casquete inferior está **por debajo** de su centro ($z \le 221$), se toma la raíz negativa:
     $$z_{\text{inferior}} = 221 - \sqrt{221^2 - r^2}$$
   * El casquete superior tiene centro en $(0; 0; 854)$ y alcanza la cima en $z = 854 + 221 = 1075$, por lo que está **por encima** de su centro ($z \ge 854$) y toma la raíz positiva:
     $$z_{\text{superior}} = 854 + \sqrt{221^2 - r^2}$$
   * **Descripción e integral correctas:**
     $$E = \left\{(r; \theta; z) : 0 \le \theta \le 2\pi \,;\, 0 \le r \le 140 \,;\, 221 - \sqrt{221^2 - r^2} \le z \le 854 + \sqrt{221^2 - r^2}\right\}$$
     $$V(E) = \int_0^{2\pi} \int_0^{140} \int_{221 - \sqrt{221^2 - r^2}}^{854 + \sqrt{221^2 - r^2}} r\,dz\,dr\,d\theta$$

7. **Solución del Ejercicio $26\text{c}$ (Página 31 del PDF — Tanque GeoTanque lleno hasta los primeros $10\text{ m}$):**
   * Cuando el tanque se llena solo hasta $z = 10\text{ m}$, el agua ocupa únicamente la parte inferior que es el **semicono** desde el vértice $z = 0$ hasta el plano horizontal $z = 10$, donde el radio es $r = 5\sqrt{5}$.
   * Por lo tanto, el piso es el semicono $z = \frac{2}{\sqrt{5}}r$ y el techo es el nivel del agua $z = 10$:
     $$V_{10\text{ m}} = \int_0^{2\pi} \int_0^{5\sqrt{5}} \int_{\frac{2}{\sqrt{5}}r}^{10} r\,dz\,dr\,d\theta = 2\pi \int_0^{5\sqrt{5}} \left(10r - \frac{2}{\sqrt{5}}r^2\right) dr = \frac{1250\pi}{3} \approx 1309.00\text{ m}^3$$

---

## SECCIÓN H. SIMULACRO INTEGRAL DE EXAMEN EU2 (FORMATO OFICIAL UPC)

* **Duración sugerida:** $100\text{ minutos}$
* **Puntaje total:** $20\text{ puntos}$ (Parte 1: $15\text{ puntos}$ | Parte 2: $5\text{ puntos}$)
* **Instrucciones:** Resuelva cada pregunta justificando su procedimiento paso a paso. En la Parte 1, cada ítem tiene calificación **todo o nada** y requiere evidencia analítica y gráfica obligatoria. No consulte el solucionario hasta haber finalizado los $100\text{ minutos}$.

---

### PARTE 1: PARTE OBJETIVA Y DE COMPLETACIÓN ($15\text{ puntos}$)

#### PREGUNTA 1 ($3.75\text{ puntos}$)
Una placa delgada tiene la forma de la región $D$ del plano $xy$, delimitada interiormente por la circunferencia $C_1: x^2 + y^2 = 4$ y exteriormente por el cardioide $C_2: r = 2 + 2\cos(\theta)$.
* **i. ($1.25\text{ ptos}$)** Halle los ángulos de intersección y seleccione la opción que describe a la región $D$ de forma ordenada en coordenadas polares:
  * **A)** $D = \left\{(r; \theta) : -\frac{\pi}{4} \le \theta \le \frac{\pi}{4} \,;\, 2 \le r \le 2 + 2\cos(\theta)\right\}$
  * **B)** $D = \left\{(r; \theta) : -\frac{\pi}{2} \le \theta \le \frac{\pi}{2} \,;\, 2 \le r \le 2 + 2\cos(\theta)\right\}$
  * **C)** $D = \left\{(r; \theta) : -\frac{\pi}{2} \le \theta \le \frac{\pi}{2} \,;\, 4 \le r \le 2 + 2\cos(\theta)\right\}$
  * **D)** $D = \left\{(r; \theta) : 0 \le \theta \le \pi \,;\, 2 \le r \le 2 + 2\cos(\theta)\right\}$
* **ii. ($1.25\text{ ptos}$)** Plantee la integral iterada que permite calcular la masa de la placa delgada, sabiendo que la densidad $\delta$ ($\text{g/cm}^2$) en cualquier punto $(x; y)$ es numéricamente igual al triple de la distancia de dicho punto al eje $y$:
  * **E)** $\int_{-\pi/2}^{\pi/2} \int_2^{2+2\cos(\theta)} 3r\cos(\theta)\,dr\,d\theta$
  * **F)** $\int_{-\pi/2}^{\pi/2} \int_2^{2+2\cos(\theta)} 3r^2\sin(\theta)\,dr\,d\theta$
  * **G)** $\int_{-\pi/2}^{\pi/2} \int_2^{2+2\cos(\theta)} 3r^2\cos(\theta)\,dr\,d\theta$
  * **H)** $\int_{-\pi/2}^{\pi/2} \int_2^{2+2\cos(\theta)} 3r^2\,dr\,d\theta$
* **iii. ($1.25\text{ ptos}$)** Plantee la integral iterada que permite calcular el área de la región $D$ y determine su valor numérico (redondeado a dos decimales).

---

#### PREGUNTA 2 ($3.75\text{ puntos}$)
Dada la siguiente integral iterada:
$$I = \int_0^1 \int_{9y^2}^{9y} f(x; y)\,dx\,dy$$
* **i. ($1.25\text{ ptos}$)** A partir de la integral planteada, describa la región de integración original $D$ y grafíquela en el plano $xy$.
* **ii. ($1.25\text{ ptos}$)** Seleccione la integral iterada que se obtiene al cambiar el orden de integración:
  * **A)** $\int_0^9 \int_{x/9}^{\sqrt{x}/3} f(x; y)\,dy\,dx$
  * **B)** $\int_0^1 \int_{x/9}^{\sqrt{x}/3} f(x; y)\,dy\,dx$
  * **C)** $\int_0^9 \int_{\sqrt{x}/3}^{x/9} f(x; y)\,dy\,dx$
  * **D)** $\int_0^9 \int_{x/9}^{\sqrt{x}/9} f(x; y)\,dy\,dx$
* **iii. ($1.25\text{ ptos}$)** Considerando la función $f(x; y) = 4y$, calcule el valor exacto de la integral iterada obtenida en el ítem ii.

---

#### PREGUNTA 3 ($3.75\text{ puntos}$)
Sea $E$ el sólido que ocupa la región del primer octante delimitada superiormente por la esfera de ecuación $x^2 + y^2 + z^2 = 25$ y por los planos $x = 0$, $y = \sqrt{3}x$ y $z = 0$.
* **i. ($1.25\text{ ptos}$)** Describa el sólido $E$ de forma ordenada en coordenadas esféricas:
  * **A)** $\left\{(\rho; \theta; \phi) : 0 \le \theta \le \frac{\pi}{3} \,;\, 0 \le \phi \le \frac{\pi}{2} \,;\, 0 \le \rho \le 5\right\}$
  * **B)** $\left\{(\rho; \theta; \phi) : \frac{\pi}{3} \le \theta \le \frac{\pi}{2} \,;\, 0 \le \phi \le \frac{\pi}{2} \,;\, 0 \le \rho \le 5\right\}$
  * **C)** $\left\{(\rho; \theta; \phi) : \frac{\pi}{6} \le \theta \le \frac{\pi}{2} \,;\, 0 \le \phi \le \frac{\pi}{2} \,;\, 0 \le \rho \le 25\right\}$
  * **D)** $\left\{(\rho; \theta; \phi) : \frac{\pi}{3} \le \phi \le \frac{\pi}{2} \,;\, 0 \le \theta \le \frac{\pi}{2} \,;\, 0 \le \rho \le 5\right\}$
* **ii. ($1.25\text{ ptos}$)** Determine la función de densidad $\delta(x; y; z)$ del sólido $E$, sabiendo que en cualquier punto $(x; y; z)$ es numéricamente igual a la cuarta parte de la distancia de este punto al eje $z$:
  * **E)** $\delta(x; y; z) = \frac{1}{4}\sqrt{x^2 + y^2 + z^2}$
  * **F)** $\delta(x; y; z) = \frac{1}{4}z$
  * **G)** $\delta(x; y; z) = \frac{1}{4}\sqrt{x^2 + y^2}$
  * **H)** $\delta(x; y; z) = 4\sqrt{x^2 + y^2}$
* **iii. ($1.25\text{ ptos}$)** Considerando una nueva función de densidad $\rho(x; y; z) = x$, plantee la integral iterada en coordenadas esféricas que permite calcular la masa del sólido $E$.

---

#### PREGUNTA 4 ($3.75\text{ puntos}$)
Sea $E$ el sólido en el primer octante que se encuentra delimitado por la superficie cilíndrica $S_1: y^2 + z = 9$ y los planos $S_2: x + y + z = 10$, $S_3: x = 0$, $S_4: y = 0$ y $S_5: z = 0$.
* **i. ($1.25\text{ ptos}$)** Describa de forma ordenada el sólido $E$ proyectándolo sobre el **plano $yz$**.
* **ii. ($1.25\text{ ptos}$)** Si la densidad $\delta$ del sólido $E$ en cualquier punto $(x; y; z)$ es numéricamente igual a la distancia de dicho punto al plano $xz$, plantee la integral iterada que permite calcular la masa del sólido.
* **iii. ($1.25\text{ ptos}$)** Considerando la descripción del sólido:
  $$H = \left\{(x; y; z) \in \mathbb{R}^3 : 0 \le x \le 2 \,;\, 0 \le z \le 4 - x^2 \,;\, 0 \le y \le 5 - z\right\}$$
  Calcule el volumen exacto del sólido $H$.

---

### PARTE 2: PREGUNTA DE DESARROLLO ($5\text{ puntos}$)

#### PREGUNTA 5 ($5\text{ puntos}$)
En una planta procesadora de alimentos se utiliza un tanque reactor vertical cuyo diseño consta de tres partes acopladas simétricamente alrededor del eje $z$:
* Una base inferior en forma de semicono invertido de $2\text{ metros}$ de altura, con su vértice apoyado en el origen de coordenadas $(0; 0; 0)$, modelado mediante la ecuación $z = k\sqrt{x^2 + y^2}$.
* Un cuerpo central en forma de cilindro circular recto de $4\text{ metros}$ de diámetro y $3\text{ metros}$ de altura (que va desde $z = 2\text{ m}$ hasta $z = 5\text{ m}$).
* Una cúpula superior en forma de paraboloide circular de $1\text{ metro}$ de altura adicional (alcanzando el tanque una altura máxima de $z = 6\text{ m}$ en el eje central), modelada por la ecuación $z = a + b(x^2 + y^2)$.

Responda justificadamente cada uno de los siguientes ítems:
* **a) ($1.5\text{ puntos}$)** Determine las ecuaciones cartesianas del cilindro ($S_1$), del semicono inferior ($S_2$) y del paraboloide superior ($S_3$).
* **b) ($1.5\text{ puntos}$)** Mostrando la gráfica de la proyección sobre el plano $xy$, describa de manera ordenada la región sólida $E$ que encierra el tanque completo utilizando coordenadas cilíndricas.
* **c) ($2.0\text{ puntos}$)** Use coordenadas cilíndricas para plantear la integral triple iterada y calcular el volumen total encerrado por el tanque.

---

### SOLUCIONARIO DESARROLLADO Y CALIFICADO DEL SIMULACRO (SECCIÓN H)

#### Solución de la Pregunta 1 ($3.75\text{ ptos}$)
* **Ítem i ($1.25\text{ ptos}$):**
  * La circunferencia $C_1: x^2 + y^2 = 4$ en polares es $r^2 = 4 \implies r = 2$.
  * Igualamos con el cardioide $r = 2 + 2\cos(\theta)$:
    $$2 + 2\cos(\theta) = 2 \implies 2\cos(\theta) = 0 \implies \cos(\theta) = 0 \implies \theta = -\frac{\pi}{2} \quad \text{y} \quad \theta = \frac{\pi}{2}$$
  * El radio va desde la circunferencia interior $r = 2$ hasta el cardioide exterior $r = 2 + 2\cos(\theta)$:
    $$D = \left\{(r; \theta) : -\frac{\pi}{2} \le \theta \le \frac{\pi}{2} \,;\, 2 \le r \le 2 + 2\cos(\theta)\right\}$$
  * **Respuesta correcta:** **B**.
* **Ítem ii ($1.25\text{ ptos}$):**
  * La distancia al eje $y$ en el semiplano derecho ($x \ge 0$) es $x = r\cos(\theta)$.
  * El triple de la distancia al eje $y$ es $\delta(x; y) = 3x = 3r\cos(\theta)$.
  * Multiplicando por el diferencial de área polar $dA = r\,dr\,d\theta$:
    $$m(D) = \int_{-\pi/2}^{\pi/2} \int_2^{2+2\cos(\theta)} \left(3r\cos\theta\right) r\,dr\,d\theta = \int_{-\pi/2}^{\pi/2} \int_2^{2+2\cos(\theta)} 3r^2\cos(\theta)\,dr\,d\theta$$
  * **Respuesta correcta:** **G**.
* **Ítem iii ($1.25\text{ ptos}$):**
  $$A(D) = \int_{-\pi/2}^{\pi/2} \int_2^{2+2\cos(\theta)} r\,dr\,d\theta = \frac{1}{2} \int_{-\pi/2}^{\pi/2} \left((2+2\cos\theta)^2 - 2^2\right) d\theta = \frac{1}{2} \int_{-\pi/2}^{\pi/2} (8\cos\theta + 4\cos^2\theta)\,d\theta = 8 + \pi \approx 11.14\text{ u}^2$$

---

#### Solución de la Pregunta 2 ($3.75\text{ ptos}$)
* **Ítem i ($1.25\text{ ptos}$):**
  $$D = \left\{(x; y) \in \mathbb{R}^2 : 0 \le y \le 1 \,;\, 9y^2 \le x \le 9y\right\}$$
  En la gráfica, las curvas $x = 9y^2$ (parábola) y $x = 9y$ (recta) se cortan en $(0; 0)$ y en $(9; 1)$.
* **Ítem ii ($1.25\text{ ptos}$):**
  * Despejamos $y$ en el primer cuadrante:
    * De la recta $x = 9y \implies y = \frac{x}{9}$ (piso).
    * De la parábola $x = 9y^2 \implies y^2 = \frac{x}{9} \implies y = \frac{\sqrt{x}}{3}$ (techo).
  * La variable $x$ barre de $0$ a $9$:
    $$I = \int_0^9 \int_{x/9}^{\sqrt{x}/3} f(x; y)\,dy\,dx$$
  * **Respuesta correcta:** **A**.
* **Ítem iii ($1.25\text{ ptos}$):**
  Reemplazando $f(x; y) = 4y$:
  $$I = \int_0^9 \int_{x/9}^{\sqrt{x}/3} 4y\,dy\,dx = \int_0^9 \Big[ 2y^2 \Big]_{x/9}^{\sqrt{x}/3} dx = \int_0^9 2\left(\frac{x}{9} - \frac{x^2}{81}\right) dx$$
  $$I = 2 \left[ \frac{x^2}{18} - \frac{x^3}{243} \right]_0^9 = 2 \left( \frac{81}{18} - \frac{729}{243} \right) = 2 (4.5 - 3) = 3$$

---

#### Solución de la Pregunta 3 ($3.75\text{ ptos}$)
* **Ítem i ($1.25\text{ ptos}$):**
  * Esfera: $x^2 + y^2 + z^2 = 25 \implies \rho = 5$ ($0 \le \rho \le 5$).
  * Primer octante arriba de $z = 0$: $0 \le \phi \le \frac{\pi}{2}$.
  * Planos verticales: $y = \sqrt{3}x \implies \tan\theta = \sqrt{3} \implies \theta = \frac{\pi}{3}$, y el plano $x = 0$ es el semieje positivo $y$, donde $\theta = \frac{\pi}{2}$. Por tanto, $\frac{\pi}{3} \le \theta \le \frac{\pi}{2}$.
  * **Respuesta correcta:** **B**.
* **Ítem ii ($1.25\text{ ptos}$):**
  * La distancia al eje $z$ es $\sqrt{x^2 + y^2}$. Su cuarta parte es $\delta(x; y; z) = \frac{1}{4}\sqrt{x^2 + y^2}$.
  * **Respuesta correcta:** **G**.
* **Ítem iii ($1.25\text{ ptos}$):**
  * Para $\rho(x; y; z) = x = \rho\sin(\phi)\cos(\theta)$, multiplicamos por $dV = \rho^2\sin(\phi)\,d\rho\,d\phi\,d\theta$:
    $$m(E) = \int_{\pi/3}^{\pi/2} \int_0^{\pi/2} \int_0^5 \rho^3\sin^2(\phi)\cos(\theta)\,d\rho\,d\phi\,d\theta$$

---

#### Solución de la Pregunta 4 ($3.75\text{ ptos}$)
* **Ítem i ($1.25\text{ ptos}$):**
  * En el plano $yz$ ($x = 0$), el cilindro parabólico $z = 9 - y^2$ en el primer octante corta al eje $y$ en $y = 3$ y al eje $z$ en $z = 9$: $0 \le y \le 3$ y $0 \le z \le 9 - y^2$.
  * La variable perpendicular $x$ va desde el plano $x = 0$ hasta el plano $x + y + z = 10 \implies x = 10 - y - z$:
    $$E = \left\{(x; y; z) \in \mathbb{R}^3 : 0 \le y \le 3 \,;\, 0 \le z \le 9 - y^2 \,;\, 0 \le x \le 10 - y - z\right\}$$
* **Ítem ii ($1.25\text{ ptos}$):**
  * Distancia al plano $xz$ ($y = 0$) en el primer octante: $\delta(x; y; z) = y$.
  * Integral iterada de la masa (con orden $dx\,dz\,dy$):
    $$m(E) = \int_0^3 \int_0^{9-y^2} \int_0^{10-y-z} y\,dx\,dz\,dy$$
* **Ítem iii ($1.25\text{ ptos}$):**
  $$V(H) = \int_0^2 \int_0^{4-x^2} \int_0^{5-z} 1\,dy\,dz\,dx = \int_0^2 \int_0^{4-x^2} (5 - z)\,dz\,dx = \int_0^2 \left[ 5z - \frac{z^2}{2} \right]_0^{4-x^2} dx$$
  $$V(H) = \int_0^2 \left( 5(4 - x^2) - \frac{(4 - x^2)^2}{2} \right) dx = \int_0^2 \left( 12 - x^2 - \frac{x^4}{2} \right) dx = \left[ 12x - \frac{x^3}{3} - \frac{x^5}{10} \right]_0^2 = 24 - \frac{8}{3} - \frac{32}{10} = \frac{272}{15} \approx 18.13\text{ u}^3$$

---

#### Solución de la Pregunta 5 ($5.0\text{ ptos}$)
* **a) Ecuaciones de las tres superficies ($1.5\text{ ptos}$):**
  1. **Cilindro ($S_1$):** Diámetro $D = 4\text{ m} \implies \text{Radio } R = 2\text{ m}$.
     $$S_1: x^2 + y^2 = 4$$
  2. **Semicono inferior ($S_2$):** Pasa por el borde de unión con el cilindro a altura $z = 2\text{ m}$, es decir, el punto $(0; 2; 2)$. Sustituyendo en $z = k\sqrt{x^2 + y^2}$:
     $$2 = k\sqrt{0^2 + 2^2} \implies 2 = 2k \implies k = 1 \implies S_2: z = \sqrt{x^2 + y^2}$$
  3. **Paraboloide superior ($S_3$):**
     * Cúspide central en $(0; 0; 6) \implies 6 = a + b(0) \implies a = 6$.
     * Borde de unión superior con el cilindro en $(0; 2; 5) \implies 5 = 6 + b(0^2 + 2^2) \implies -1 = 4b \implies b = -\frac{1}{4} = -0.25$.
     $$S_3: z = 6 - \frac{1}{4}(x^2 + y^2)$$
* **b) Proyección y descripción ordenada en coordenadas cilíndricas ($1.5\text{ ptos}$):**
  * Dibujamos en el plano $xy$ el círculo sombreado de radio $R = 2$ ($x^2 + y^2 \le 4$).
  * En cilíndricas, el piso del tanque es el semicono $z = r$ y el techo es el paraboloide $z = 6 - \frac{1}{4}r^2$:
    $$E = \left\{(r; \theta; z) : 0 \le \theta \le 2\pi \,;\, 0 \le r \le 2 \,;\, r \le z \le 6 - \frac{1}{4}r^2\right\}$$
* **c) Planteamiento y cálculo del volumen ($2.0\text{ ptos}$):**
  $$V(E) = \iiint_E 1\,dV = \int_0^{2\pi} \int_0^2 \int_r^{6 - \frac{1}{4}r^2} r\,dz\,dr\,d\theta$$
  $$V(E) = \int_0^{2\pi} \int_0^2 r \left( 6 - \frac{1}{4}r^2 - r \right) dr\,d\theta = \int_0^{2\pi} \int_0^2 \left( 6r - r^2 - \frac{1}{4}r^3 \right) dr\,d\theta$$
  $$V(E) = 2\pi \left[ 3r^2 - \frac{r^3}{3} - \frac{r^4}{16} \right]_0^2 = 2\pi \left( 12 - \frac{8}{3} - 1 \right) = 2\pi \left(\frac{25}{3}\right) = \frac{50\pi}{3}\text{ m}^3 \approx 52.36\text{ m}^3$$
  *(Comprobación geométrica rápida: $V_{\text{cono}} + V_{\text{cil}} + V_{\text{parab}} = \frac{1}{3}\pi(2^2)(2) + \pi(2^2)(3) + \frac{1}{2}\pi(2^2)(1) = \frac{8\pi}{3} + 12\pi + 2\pi = \frac{50\pi}{3}$. ¡Exacto!).*

---

## SECCIÓN I. RESUMEN FINAL DE ALTO RENDIMIENTO (HOJA DE REPASO RÁPIDO)

### I.1. Cuadro Comparativo de los Sistemas de Coordenadas en 2D y 3D

| Sistema | Coordenadas | Ecuaciones de Transformación | Diferencial ($dA$ o $dV$) | ¿Cuándo usarlo en el examen? |
| :--- | :--- | :--- | :--- | :--- |
| **Cartesianas 2D** | $(x; y)$ | $x = x$, $y = y$ | $dy\,dx$ o $dx\,dy$ (Jacobiano $= 1$) | Regiones limitadas por rectas y parábolas, o problemas de cambio de orden de integración. |
| **Polares 2D** | $(r; \theta)$ | $x = r\cos\theta$, $y = r\sin\theta$, $x^2+y^2 = r^2$ | $\mathbf{r}\,dr\,d\theta$ (Jacobiano $= r$) | Circunferencias centradas o desplazadas, cardioides, o integrandos con $x^2+y^2$. |
| **Cartesianas 3D** | $(x; y; z)$ | $x = x$, $y = y$, $z = z$ | $dz\,dy\,dx$, $dy\,dz\,dx$, $dx\,dz\,dy$ | Sólidos limitados por cilindros parabólicos ($x^2+z=4$, $x^2+y=4$) y planos inclinados. |
| **Cilíndricas 3D** | $(r; \theta; z)$ | $x = r\cos\theta$, $y = r\sin\theta$, $z = z$ | $\mathbf{r}\,dz\,dr\,d\theta$ (Jacobiano $= r$) | Tanques reales (Pregunta 5), cilindros circulares, paraboloides ($z=a+br^2$) y semiconos ($z=a+br$). |
| **Esféricas 3D** | $(\rho; \theta; \phi)$ | $x=\rho\sin\phi\cos\theta$, $y=\rho\sin\phi\sin\theta$, $z=\rho\cos\phi$, $\rho^2=x^2+y^2+z^2$ | $\mathbf{\rho^2\sin\phi}\,d\rho\,d\phi\,d\theta$ (Jacobiano $= \rho^2\sin\phi$) | Esferas centradas en el origen combinadas con semiconos y planos en el primer octante. |

---

### I.2. Reconocimiento Instantáneo de Métodos según el Enunciado
* **Si ves:** *«Evalúe invirtiendo el orden de integración»* $\implies$ Dibuja la región, despeja la otra variable y cambia $dy\,dx \leftrightarrow dx\,dy$.
* **Si ves:** *«...delimitado por $C_1: x^2+y^2 = a^2$ y $C_2: r = b \pm b\cos\theta$»* $\implies$ Coordenadas polares, iguala $r_1 = r_2$ para hallar $\theta$ y no olvides el jacobiano $r$.
* **Si ves:** *«...esfera $x^2+y^2+z^2=R^2$ y planos $y=mx, z=0$ en el primer octante»* $\implies$ Coordenadas esféricas con $0 \le \phi \le \frac{\pi}{2}$ y $0 \le \rho \le R$.
* **Si ves:** *«...proyectándolo sobre el plano $xz$ (o $yz$)»* $\implies$ Coordenadas cartesianas 3D: la variable que NO está en el nombre del plano va en la integral más interna.
* **Si ves:** *«Un tanque / tolva / balón está conformado por un cilindro y un semicono/paraboloide...»* $\implies$ Coordenadas cilíndricas, usa el radio $R = \frac{\text{diámetro}}{2}$ y dibuja siempre el círculo proyectado en el plano $xy$.

---

### I.3. Los 7 Errores Mortales que Debes Evitar antes de Entregar tu Examen
1. **Dejar en blanco la columna derecha de evidencia** en la Parte 1 (recuerda que vale $0\text{ puntos}$ si no muestras el procedimiento).
2. **Olvidar el Jacobiano** ($r$ en polares/cilíndricas; $\rho^2\sin\phi$ en esféricas).
3. **Usar el diámetro en lugar del radio** al escribir la ecuación del cilindro $x^2+y^2 = R^2$ en la Pregunta 5.
4. **Olvidar dibujar el círculo de la proyección en el plano $xy$** en la Pregunta 5b (cuesta hasta $0.5\text{ puntos}$).
5. **Confundir distancia a un eje con distancia a un plano o al origen** (usa siempre la regla mnemotécnica de cuántas letras faltan).
6. **Olvidar el signo negativo de la raíz ($x = -\sqrt{\dots}$)** cuando despejas en el segundo cuadrante ($x \le 0$).
7. **Tener la calculadora en modo Grados `[DEG]`** en vez de **Radianes `[RAD]`** al evaluar integrales con funciones trigonométricas.

---

### I.4. Lista de Comprobación Final (Checklist Pre-Examen)
Marca cada casilla cuando puedas realizar la tarea sin mirar apuntes:
* [ ] Sé cambiar el orden de integración en regiones con parábolas y rectas, tanto en el primer como en el segundo cuadrante.
* [ ] Sé hallar los ángulos de intersección entre una circunferencia y un cardioide, y plantear tanto el área como la masa en polares.
* [ ] Domino de memoria la tabla de distancias (al origen, a los ejes $x, y, z$ y a los planos $xy, xz, yz$) y sé pasarlas a polares, cilíndricas y esféricas.
* [ ] Sé describir un sólido en coordenadas cartesianas proyectándolo sobre el plano $xy$, sobre el plano $xz$ y sobre el plano $yz$.
* [ ] Sé distinguir cuándo el ángulo $\phi$ en esféricas va de $0$ a $\alpha$ (dentro del cono) y cuándo va de $\alpha$ a $\frac{\pi}{2}$ (fuera del cono).
* [ ] Puedo hallar sin ayuda las constantes de cualquier semicono $z = a + b\sqrt{x^2+y^2}$ o paraboloide $z = a + b(x^2+y^2)$ de un tanque, dibujar su proyección y calcular su volumen en coordenadas cilíndricas.