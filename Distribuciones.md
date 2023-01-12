# Estadística descriptiva aplicada: distribuciones

## ¿Cómo visualizar una distribución?

- Histograma
- Función de probabilidad de masas (PMF)
- Función de distribución acumulada (CDF)
- Función de probabilidad de densidad (PDF)

### _Función de probabilidad de masas (PMF)_
Nos dice la probabilidad de que una variable aleatoria discreta tome un valor determinado.  Por ejemplo, la probabilidad de que en un salón haya personas que tengan 16 años.

La función de masa de probabilidad depende de los valores de cualquier número real. No va al valor de X que es igual a cero y en el caso de x, el valor de PMF es positivo.

El PMF juega un papel importante en la definición de una distribución de probabilidad discreta y produce resultados distintos. La fórmula de PMF es p (x) = P (X = x) es decir, la probabilidad de (x) = la probabilidad (X = una x específica)

### _Función de distribución acumulada (CDF)_
Devuelve la probabilidad de que una variable sea igual o menor que un valor determinado. Por ejemplo, cual es la probabilidad de que en un salón haya personas que tengan 16 o menos años.

En la teoría de la probabilidad y en estadística, la función de distribución acumulada  o función de probabilidad acumulada asociada a una variable aleatoria real $$X$$ sujeta a cierta ley de distribución de probabilidad, es una función matemática de la variable real $$x$$ que describe la probabilidad de que $$X$$ tenga un valor menor o igual que $$x$$.

Intuitivamente, asumiendo la función $$f$$ como la ley de distribución de probabilidad, la CFD sería la función con la recta real como dominio, con imagen del área hasta aquí de la función $$f$$, siendo aquí el valor $$x$$ para la variable aleatoria real $$X$$.
La CDF asocia a cada valor $$x$$, la probabilidad del evento: **_«la variable $$X$$ toma valores menores o iguales a $$x$$»_**.

### _Función de probabilidad de densidad (PDF)_
Determina la probabilidad de que una variable continua tome un valor determinado. Por ejemplo, la estatura de un grupo de personas.

En la teoría de la probabilidad, la función de densidad de probabilidad, función de densidad, o simplemente densidad de una variable aleatoria continua describe la probabilidad relativa según la cual dicha variable aleatoria tomará determinado valor.

La probabilidad de que la variable aleatoria caiga en una región específica del espacio de posibilidades estará dada por la integral de la densidad de esta variable entre uno y otro límite de dicha región.
La función de densidad de probabilidad  es positiva a lo largo de todo su dominio y su integral sobre todo el espacio es de valor unitario.

Una función de densidad de probabilidad caracteriza el comportamiento probable,  de una población, en tanto especifica la posibilidad relativa de que una variable aleatoria continua $$X$$ tome un valor cercano a $$x$$.

Una variable aleatoria $$X$$ tiene función de densidad $$f_{X}$$, siendo $$f_{X}$$ una función no-negativa integrable de Lebesgue, si:
$${\displaystyle \operatorname {P} [a\leq X\leq b]=\int _{a}^{b}f_{X}(x)\,dx}$$

si $$F_{X}$$ es la función de distribución de $$X$$, entonces

$${\displaystyle F_{X}(x)=\int _{-\infty }^{x}f_{X}(u)\,du}$$

### Parámetro de comparación PDF PMF

|Forma completa|Función de densidad de probabilidad|Función de probabilidad|
|--------------|-----------------------------------|-----------------------|
|Utilizar|El PDF se utiliza cuando es necesario encontrar una solución en un rango de variables aleatorias continuas.|PMF se utiliza cuando existe la necesidad de encontrar una solución en un rango de variables aleatorias discretas.|
|Variables aleatorias|PDF utiliza variables aleatorias continuas.|PMF utiliza variables aleatorias discretas.|
|Fórmula|$$F (x) = P (a X )$$|$$p (x) = P (X = x)$$|
|Solución|La solución cae en el rango de radio de variables aleatorias continuas.|Las soluciones se encuentran en el radio entre números de variables aleatorias discretas.|




