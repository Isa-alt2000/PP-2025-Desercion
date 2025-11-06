# Proyecto Prototípico de Deserción estudiantil
Este pequeño proyecto forma parte de la evidencia para el Proyecto Prototípico "Deserción escolar" realizado por alumnos de tercer semestre de la Universidad Nacional Rosaio Castellanos.

Para la realización de este proyecto, se optó por utilizar django debido a su modularidad y manejo más ordenado de los archivos e información.

## Contenidos
- [x] Sistema de login simple que NO requiere correo dada la simplicidad del proyecto.
- [x] App calculadora de balance personal (login necesario).
- [ ] Formulario de deserciones y posterior desglose de estadísticas en un dashboard.
- [ ] Dashboard de resultados de investigación.
- [ ] PDF de presentación con reporte ejecutivo anexado.

## Herramientas utilizadas
 - Django
 - Postgres

## Guia de instalación
1. Configuración de motor de base de datos (postgres por el momento)  
    Configuración automática para despliegue con script. **UNICAMENTE SI NO EXISTE USUARIO O DB PREVIOS CON LOS MISMOS NOMBRES. EN TODO CASO, SERÁ NECESARIO HACERLO MANUALMENTE**
    - **script NO incluye la instalación de postgres por lo que deberá hacerse manualmente**  

    **Linux**
    ```bash
    chmod +x setup_postgres.sh
    ```

    ```bash
    ./setup_postgres.sh
    ```

2. Creación de entorno virtual

3. Configuración de variables de entorno

4. Migraciones django

5. Levantar el proyecto

## Uso
La apliación cuenta con # apartados

## Extras
Para este proyecto se buscó seguir las mejores prácticas posibles de python y de desarrollo web indicadas a continuación.
 - Versionado git
 - PEP8 (Haciendo uso de Flake8)
 - Manejo de variables de entorno

**Sin embargo no se implementaron prácticas REST debido a la naturaleza pequeña del proyecto.**  

**La funcionalidad de usuarios fue reciclada de un proyecto anterior y adaptada a este proyecto por lo cual puede haber ligeras discrepancias que serán removidas poco a poco.**  

**El proyecto utiliza postgres como motor de base de datos, será migrado a mysql en la posterioridad.**
