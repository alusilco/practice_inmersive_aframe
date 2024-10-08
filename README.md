## Third Project: A-Frame Interactive Blood Boxes

Este proyecto es una escena interactiva de realidad virtual (VR) creada con [A-Frame](https://aframe.io/), una biblioteca de código abierto para crear experiencias de WebVR usando HTML. La escena incluye dos entidades (cajas) con un componente personalizado llamado `blood`, que representa características como el tipo de sangre y los niveles de oxígeno.

## Descripción del Proyecto

El proyecto incluye dos cajas, llamadas `Box1` y `Julian`. Ambas entidades tienen un componente personalizado `blood` con propiedades que permiten definir el tipo de sangre (`blood_type`) y los niveles de oxígeno (`oxygen_level`). Las cajas pueden rotar lentamente y responder a eventos de clic, actualizando su posición y cambiando los atributos del tipo de sangre y el nivel de oxígeno.

### Características principales:
- **Componente personalizado `blood`**:
  - Atributos:
    - `blood_type`: Define el tipo de sangre (por defecto es `O-type`).
    - `oxygen_level`: Define el nivel de oxígeno (por defecto es `normal`).
  - **Eventos interactivos**: Al hacer clic en una entidad con el componente `blood`, su posición Y se incrementa y se actualizan los atributos de sangre.
  - **Rotación**: Las entidades giran lentamente sobre el eje Y.

## Archivos importantes

- **HTML**: Define la estructura de la escena en A-Frame.
- **JavaScript**: Implementa la lógica del componente personalizado `blood`.

## Estructura del proyecto

