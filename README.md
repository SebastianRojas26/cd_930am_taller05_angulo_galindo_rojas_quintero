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
Sebastian Rojas - 202612021
<br/>
Juan Manuel Quintero - 202610465 
<br/>
Robinson Javier Galindo - (agregar código)
</p>

## 📃 Tabla de contenidos
- [Descripción](#-desc)
- [Base de datos a analizar](#-basedatos)
- [Herramientas tecnológicas utilizadas](#-herramientas)
- [Metodología](#-metodologia)
- [Resultados esperados](#-resultados)

  
## 🗣️ Descripción
En este proyecto se utilizara [**machine learning**](https://www.ibm.com/mx-es/think/topics/machine-learning) para identificar clientes con una alta probabilidad de cancelar su servicio. El objetivo de este trabajo es avisarle al equipo de marketing con anticipacion para que se pueda prevenir el retiro de los clientes.

## 🔎 Base de datos a analizar: 
Se analizara una base de datos que contenga la totalidad de clientes de la compañia (aprox. 20000) En esta base de datos se analizaran las siguientes variables:
| Variable a analizar | Medida |
|---------------------|--------|
| Antiguedad del contrato    | meses  |
| Monto de la factura    | COP   |
| Quejas al soporte tecnico   | Cantidad discreta   |
| Uso de datos | GB   |

##  Herramientas tecnologicas utlizadas
Para este proyecto se utilizara python. En consecuencia, se hara uso diferentes librerias de python para la manipulation de los datos, como lo son:
1. Pandas (limpieza)
2. Scikit-learn (modelado)
3. Matplotlib y seaborn (visualization de datos).

## 🖥️Metodologia
Antes de inicar el analisis se hara la debida limpieza de datos haciendo uso de la herramienta **pandas**. Seguido a esto se revisara que clientes poseen mas de dos caracterisitcas no deseadas. Dichas caracteristicas no deseadas son:

- Mas de tres quejas a servicio al cliente
- Inconsistencias notables entre el uso de datos y el costo de la factura. Por ejemplo, cuando el uso de datos es menor a 100 GB y la factura cuesta 200.000COP

Luego de esto se alimentara esta información a un modelo de aprendizaje que nos arroje una clasificación de usuarios. Por ultimo, se evaluara dicho modelo para encontrar que tan preciso es. Si este modelo no alcanza una precision del 90% se reevaluaran los tipos de datos que se estan usando para entrenarlo y el acercamiento al problema.

## :bulb: Resultados Esperados
<details>
    <summary> Teniendo en cuenta que el objetivo va dirijido hacia el equipo de marketing, nuestros resultados seran presentados de la siguiente manera: </summary>

1. Exposición del problema
2. Metodología
   Breve explicación de la metodologia empleada
4. Resultados/Gráficos
   Para una optima visualizacion los resultados del modelo seran presentados en graficos similares a los siguientes en donde se muestre la dispersion de clientes      en las cuatro categorias.

|Categoria |  No probable | Poco probable | Probable |Altamente probable |
|-----------|-----------|-----------|-----------|-----------|
| Porcentaje | 0-25  | 25-50  |50-75 |75-100|
Varias imágenes en fila
<p align="center">
    <img src="WhatsApp Image 2026-03-25 at 6.57.41 PM.jpeg" width="400"/>
    <img src="img2.png" width="400"/>
</p>


4. Analísis de los resultados
   Se hara un analisis en donde se expongan los clientes que se encuentran en las ultimas dos categorias al equipo de marketing.
5. Conclusión

</details>

