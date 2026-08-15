# Proyecto de Matemáticas discretas aplicadas a las finanzas (Tablas de amortización y expandido a clases de Matemáticas financieras) 

Calculadora de cuotas a pagar en base a préstamos crediticios. Proyecto desarrollado para la materia de Matemáticas Discretas (ESPOL).

La fórmula central de este proyecto se compone de 4 elementos de la ecuación de **Anualidades Vencidas a Valor Presente**:

$$ C = \frac{VA \cdot i}{1 - (1+i)^{-n}} $$

### 1) VA o VP (Valor Presente o Actual)
Es el valor que ingresa al cliente que quiere calcular las cuotas con una tasa porcentual específica.
> **Nota de la versión:** En primera instancia la elaboraremos con tasa efectiva, cuya capitalización tiene la misma unidad de medida temporal que la tasa de interés, es decir TASA ANUAL, SEMESTRAL, TRIMESTRAL, MENSUAL, SEMANAL, DIARIA, ETC.

### 2) C o P (Cuotas o Pagos)
Valores periódicos a cancelar para cubrir el interés generado en el saldo y una pequeña parte del mismo.
> **El peligro del pago mínimo:** Estos son los valores que solemos pagar al final del mes en el caso de las tarjetas de crédito. Valores como el "pago mínimo" se concretan en el pago del interés y la cobertura minúscula del saldo de la deuda real; al ser un valor pequeño en comparación, se aconseja el pago mínimo solamente como última opción.

### 3) i% (Tasa de interés)
Valor porcentual que aumenta nuestro saldo. Dependiendo de la unidad de tiempo aplicada a la misma, su incremento se puede dar de manera MENSUAL, ANUAL, TRIMESTRAL, SEMESTRAL, ETC.
> **Nota de la versión:** La tasa que aplicaremos en la versión uno del programa solo será tasa efectiva, cuya capitalización es 1 (o en mejores palabras, que la capitalización es de la misma unidad temporal que la tasa de interés). Se tiene en consideración que a futuro se aplicará capitalización de distintos periodos por ejemplo: Tasa efectiva anual con capitalización mensual.

### 4) n (Periodos)
La cantidad de cuotas a pagar, acordadas entre el prestador y el prestatario.
> **El coste de oportunidad:** A menudo al realizar compras, podemos optar por diferir nuestros pagos a 3, 6, 12 o 24 meses. Estos periodos son los que estamos acordando a pagar; en sí, a mayor tiempo, por el coste de oportunidad, causará que estemos pagando una cantidad superior al valor en el tiempo actual que estamos recibiendo.

---

## ✨ Características Principales de la App

*   **Interés Simple vs. Compuesto:** Visualiza la diferencia entre el crecimiento de tu dinero.
*   **Conversor de Tasas:** Calcula Tasas Efectivas Anuales (TEA) y sus tasas nominales equivalentes en distintas capitalizaciones.
*   **Sistemas de Amortización:** Compara cómo se comporta un mismo préstamo bajo los sistemas Francés (cuota fija), Alemán (capital fijo) y Americano (bullet).
*   **Simulador de Destinos:** Evalúa distintos escenarios financieros e incluye simulaciones con pagos extraordinarios.
*   **Quizzes y ejercicios:** 10 niveles de dificultad con problemas generados al azar, desde cálculos básicos hasta problemas de destino con enunciados verbales.

---

## ⚠️ Descargo de Responsabilidad

Este cuaderno fue desarrollado con fines estrictamente **académicos y educativos**. Las cifras, tasas y resultados son ilustrativos y se calculan con fórmulas matemáticas simplificadas. **No constituyen asesoría financiera, legal, ni una oferta de productos financieros reales.** 

Verifica siempre las condiciones y tasas con una institución financiera antes de tomar decisiones con dinero real.
