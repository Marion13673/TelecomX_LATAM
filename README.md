## **INTRODUCCIÓN** 🚀

## La empresa Telecom X requiere análizar los datos para su proyecto "Churn de Clientes". La empresa enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.

**Características** ✨

Se extrae información de un archivo JSON, donde los datos están estructurado en forma de diccionario.

Los principales desafíos:
- recopilar
- procesar
- analizar los datos

## **DESCRIPCIÓN** 🖌️
  
Para ello se realiza los siguientes pasos para su extracción, transformación, análisis y conclusión:

-  ✅ Importar y manipular datos desde una API de manera eficiente.
-  ✅ Cargar los datos directamente desde la API utilizando Python.
-  ✅ Convertir los datos a un DataFrame de Pandas para facilitar su manipulación.
-  ✅ Aplicar los conceptos de ETL (Extracción, Transformación y Carga) en la preparación de los datos.
-  ✅ Crear visualizaciones estratégicas para identificar patrones y tendencias.
-  ✅ Realizar un "Análisis Exploratorio de Datos (EDA)" y generar un informe con insights relevantes.
-  ✅ Comprobación de incoherencias en los datos.
-  ✅ Aplicar las correcciones necesarias. Ajustar los datos para asegurar que estén completos y coherentes.
-  ✅ Crear la columna "Cuentas Diarias". Se utiliza la facturación mensual para calcular el valor diario, proporcionando una visión más detallada del comportamiento de los clientes a lo largo del tiempo.
-  ✅ La estandarización y transformación de datos es una etapa opcional, pero altamente recomendada, ya que busca hacer que la información sea más consistente, comprensible y adecuada para el análisis.
  durante esta fase, por ejemplo, se convertió los valores textuales como "Sí" y "No" en valores binarios (1 y 0), lo que facilita el procesamiento matemático y la aplicación de modelos analíticos.
-  ✅ Traducir o renombrar las columnas y los datos para hacer que la información sea más accesible y fácil de entender, especialmente cuando se trabaja con fuentes externas o términos técnicos. Aunque
  no es un paso obligatorio, puede mejorar significativamente la claridad y comunicación de los resultados, facilitando la interpretación y evitando confusiones, especialmente al compartir información
  con stakeholders no técnicos.
-  ✅ Realizar un análisis descriptivo de los datos, calculando métricas como media, mediana, desviación estándar y otras medidas que ayuden a comprender mejor la distribución y el comportamiento de los
   clientes.
-  ✅ Explorar variables numéricas, como "total gastado" o "tiempo de contrato", se distribuyen entre los clientes que cancelaron (evasión) y los que no cancelaron.
Este análisis ayuda a entender si ciertos valores numéricos están más asociados con la evasión, proporcionando insights sobre los factores que influyen en el comportamiento de los clientes.
-  ✅ Explorar cómo se distribuye la evasión según variables categóricas, como género, tipo de contrato, método de pago, entre otras.
Este análisis puede revelar patrones interesantes, por ejemplo, si los clientes de ciertos perfiles tienen una mayor tendencia a cancelar el servicio, lo que ayudará a orientar acciones estratégicas.
-  ✅ Utiliza gráficos para visualizar la proporción de clientes que permanecieron y los que se dieron de baja.
-  ✅ La relación entre la cuenta diaria y la evasión.
-  ✅ Cómo la cantidad de servicios contratados afecta la probabilidad de churn.

## **CONCLUSIÓN** 💿

Se finaliza el desafío elaborando un informe dentro del mismo notebook que resume todo el trabajo realizado. El informe incluiye:

🔹 Introducción: Explica el objetivo del análisis y el problema de evasión de clientes (Churn).

🔹 Limpieza y Tratamiento de Datos: Describe los pasos realizados para importar, limpiar y procesar los datos.

🔹 Análisis Exploratorio de Datos: Presenta los análisis realizados, incluyendo gráficos y visualizaciones para identificar patrones.

🔹 Conclusiones e Insights: Resume los principales hallazgos y cómo estos datos pueden ayudar a reducir la evasión.

🔹 Se ofrece sugerencias estratégicas basadas en el análisis.

## **Archivos del Proyecto** 📂

JSON: (JavaScript Object Notation) es un formato ligero para intercambiar datos de manera estructurada y fácil de leer. Utiliza pares clave-valor y estructuras anidadas como listas y objetos. Se emplea en APIs, almacenamiento de datos y configuración debido a su simplicidad y compatibilidad con múltiples lenguajes de programación.
El archivo contiene las bases de datos de un conjunto de clientes separados por aquellos que abandonaron la empresa y otros que permanecen en la empresa para el análisis.

Jupyter Notebook: Proyecto desarrollado en Google Colaboratory, utilizando Python y bibliotecas como Pandas para realizar el análisis de datos.

**Lenguaje y Bibliotecas Utilizadas:** 💻

Python

Bibliotecas Principales:
* Pandas: Manipulación y análisis de datos estructurados.
* NumPy: Trabajo con arrays multidimensionales y cálculos matemáticos.
* Matplotlib: Creación de gráficos y visualizaciones de datos.
* Seaborn: Biblioteca avanzada para visualizaciones estadísticas y estilizadas, ideal para explorar datos y destacar relaciones entre variables.
* Instalación 💽

Ejecuta el siguiente comando para instalar las bibliotecas necesarias:

pip install pandas numpy matplotlib

## **Instrucciones para Ejecutar** 🚀

Clona este repositorio en tu máquina local: ´´´bash
git clone https://github.com/Marion13673/TelecomX_LATAM.git
Abre el archivo index.html en tu navegador para ver y usar la aplicación.

## **Contribuciones** 🤝

💡 ¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, por favor sigue estos pasos:

 **Haz un fork del repositorio.**

- Crea una rama con tu nueva característica (git checkout -b feature/nueva-caracteristica).
- Realiza tus cambios y haz un commit (git commit -m 'Añadir nueva característica').
- Envía tu rama al repositorio remoto (git push origin feature/nueva-caracteristica).
- Abre una Pull Request.

## **Licencia** 📜

📄 Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más información.



