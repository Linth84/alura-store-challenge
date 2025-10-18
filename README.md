# Alura Store – Análisis de ventas y desempeño

## Estado del proyecto
**Finalizado.**  
Este proyecto fue desarrollado como parte del programa **Oracle Next Education – Alura Latam (Data Science)**.

---

## Índice
1. [Propósito del proyecto](#propósito-del-proyecto)  
2. [Estructura del proyecto](#estructura-del-proyecto)  
3. [Tecnologías utilizadas](#tecnologías-utilizadas)  
4. [Ejemplos de gráficos e insights](#ejemplos-de-gráficos-e-insights)  
5. [Principales resultados e insights](#principales-resultados-e-insights)  
6. [Instrucciones para ejecutar el notebook](#instrucciones-para-ejecutar-el-notebook)  
7. [Autor](#autor)  
8. [Licencia](#licencia)

---

## Propósito del proyecto
El objetivo de este análisis es evaluar el rendimiento de las cuatro tiendas de la cadena **Alura Store** con el fin de determinar **cuál presenta menor rentabilidad** y debería ser vendida por el Sr. Juan para financiar un nuevo emprendimiento.  

El estudio se basa en datos reales de ventas, calificaciones y costos logísticos, aplicando técnicas de análisis exploratorio con Python.  
Se buscó **identificar patrones de comportamiento, comparar métricas de desempeño y generar conclusiones respaldadas por visualizaciones**.

---

## Estructura del proyecto
El análisis se desarrolló utilizando **Python**, principalmente con las bibliotecas **Pandas** y **Matplotlib**, siguiendo un enfoque exploratorio y descriptivo.

**Estructura del repositorio:**
```text
AluraStoreChallenge/
│
├── AluraStoreLatamChallenge.ipynb   
└── README.md                        
```
## Tecnologías utilizadas

    Python 3

    Pandas – manejo y análisis de datos

    Matplotlib – visualización de datos

    Google Colab / Jupyter Notebook

## Ejemplos de gráficos e insights

Durante el desarrollo se generaron distintas visualizaciones para apoyar los resultados del análisis:
1. Gráfico de barras – Ingresos totales

Mostró que la Tienda 1 alcanzó la mayor facturación, mientras que la Tienda 4 obtuvo los ingresos más bajos.
2. Gráfico de barras horizontales – Costo de envío promedio

Reveló que la Tienda 4 tiene los costos logísticos más bajos, aunque esto no se traduce en un mejor desempeño general.
3. Gráfico de dispersión – Análisis geográfico

Usando las columnas de latitud y longitud, se representaron las ubicaciones de las ventas.
Se observó una concentración en grandes centros urbanos como Bogotá, Medellín y Cali, sin diferencias regionales relevantes en las métricas de desempeño.

## Principales resultados e insights

    Tienda 1: Mayor nivel de ingresos, pero menor calificación promedio.

    Tiendas 2 y 3: Buen balance entre ventas y satisfacción del cliente.

    Tienda 4: Bajos ingresos y ventas, a pesar de tener costos logísticos reducidos.

## Conclusión final

De acuerdo con los resultados del análisis y el índice de desempeño calculado, se recomienda vender la Tienda 4, ya que presenta el menor rendimiento global entre las cuatro tiendas analizadas.

## Instrucciones para ejecutar el notebook

    Clonar o descargar el repositorio:

git clone https://github.com/tuusuario/alura-store-challenge.git

Abrir el notebook:

    En Google Colab (recomendado)

    O en Jupyter Notebook / VS Code

Instalar las dependencias necesarias (si es local):

    pip install pandas matplotlib

    Ejecutar las celdas en orden.

## Autor

Alberto Edgardo Villalba

Programa Oracle + Alura Latam – Data Science

## Licencia

Este proyecto se distribuye con fines educativos y no comerciales.
Puede ser utilizado libremente como referencia de análisis exploratorio de datos en Python.
