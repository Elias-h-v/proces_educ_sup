## Paso 1: Redirigir a la carpeta proyecto

## Paso 2: Crear el ambiente virtual (Carpeta donde se guradan las librerias)
python -m venv myenv
myenv -> es el nombre del ambiente virtula creado

## Paso 3: Activacion del entorno virtual
myenv\Scripts\activate

## Paso 4: Instalar las librerias del arcivo requerimientos.txt 

## Paso 5: Descargar el CSV mas reciente de la siguiente url
 https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## Paso 6: Ejecutar la aplicacion
python get_excel_resumen_es.py