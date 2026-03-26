<p align="center">
  <img src="banner.png" alt="Banner del Proyecto">
</p>

# Análisis de fuga de clientes en [**Movistar**](https://www.movistar.com.co/)
<p align="center">
    <img src="movistar.png" alt="Movistar Logo" width="500"/>
</p>

## ⭐ Integrantes del Equipo
<p align="center">
Ana Sofía Angulo - 202611661  
<br/>
Sebastián Rojas - 202612021  
<br/>
Juan Manuel Quintero - 202610465  
<br/>
Robinson Javier Galindo - (agregar código)
</p>

## 📃 Tabla de contenidos
- [Descripción](#️-descripción)
- [Base de datos a analizar](#-base-de-datos-a-analizar)
- [Herramientas tecnológicas utilizadas](#-herramientas-tecnológicas-utilizadas)
- [Metodología](#️metodología)
- [Resultados esperados](#bulb-resultados-esperados)

## 🧑 Descripción
En este proyecto se utilizará [**machine learning**](https://www.ibm.com/mx-es/think/topics/machine-learning) para identificar clientes con una alta probabilidad de cancelar su servicio. El objetivo de este trabajo es avisarle al equipo de marketing con anticipación para que se pueda prevenir el retiro de los clientes.

## 🔎 Base de datos a analizar
Se analizará una base de datos que contenga la totalidad de clientes de la compañía (aprox. 20.000). En esta base de datos se estudiarán las siguientes variables:

| Variable a analizar | Medida |
|---------------------|--------|
| Antigüedad del contrato | Meses |
| Monto de la factura | COP |
| Quejas al soporte técnico | Cantidad discreta |
| Uso de datos | GB |

## 🐍 Herramientas tecnológicas utilizadas
Para este proyecto se utilizará Python. En consecuencia, se hará uso de diferentes librerías para la manipulación de los datos, como lo son:
1. Pandas (limpieza)
2. Scikit-learn (modelado)
3. Matplotlib y Seaborn (visualización de datos)

## 🖥️ Metodología
Antes de iniciar el análisis se hará la debida limpieza de datos haciendo uso de la herramienta **Pandas**. Seguido a esto, se revisará qué clientes poseen más de dos características no deseadas. Dichas características no deseadas son:

- Más de tres quejas a servicio al cliente  
- Inconsistencias notables entre el uso de datos y el costo de la factura. Por ejemplo, cuando el uso de datos es menor a 100 GB y la factura cuesta 200.000 COP

Luego de esto, se alimentará esta información a un modelo de aprendizaje que nos arroje una clasificación de usuarios. Por último, se evaluará dicho modelo para encontrar qué tan preciso es. Si este modelo no alcanza una precisión del 90%, se reevaluarán los tipos de datos que se están usando para entrenarlo y el acercamiento al problema.

## :bulb: Resultados Esperados
<details>
    <summary> Teniendo en cuenta que el objetivo va dirigido hacia el equipo de marketing, nuestros resultados serán presentados de la siguiente manera: </summary>

1. Exposición del problema  
2. Metodología  
   Breve explicación de la metodología empleada  
3. Resultados/Gráficos  
   Para una óptima visualización, los resultados del modelo serán presentados en gráficos similares a los siguientes, en donde se muestre la dispersión de clientes en las cuatro categorías.

| Categoría | No probable | Poco probable | Probable | Altamente probable |
|-----------|-------------|---------------|----------|---------------------|
| Porcentaje | 0–25 | 25–50 | 50–75 | 75–100 |

Varias imágenes en fila  
<p align="center">
    <img src="WhatsApp Image 2026-03-25 at 6.57.41 PM.jpeg" width="400"/>
    <img src="img2.png" width="400"/>
</p>

4. Análisis de los resultados  
   Se hará un análisis en donde se expongan los clientes que se encuentran en las últimas dos categorías al equipo de marketing.  
5. Conclusión

</details>


