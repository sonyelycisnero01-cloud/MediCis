 **-Descripción del proyecto**
MediCis es un sistema digital propuesto para el Centro Integral de Manejo de Heridas y Pie Diabético. Su finalidad es organizar la información relacionada con pacientes, médicos, citas, historias clínicas, tratamientos, recetas y referimientos médicos.


**-Objetivo**
Facilitar la gestión de la información clínica y administrativa mediante una solución organizada que permita mejorar el seguimiento de pacientes y las actividades de la clínica.


**-Problema que busca resolver**
La administración de información médica mediante procedimientos dispersos puede dificultar la consulta de datos, la organización de citas y el seguimiento de tratamientos. MediCis propone centralizar estos procesos y establecer controles para proteger la información.


**-Funcionalidades principales**

_Gestión de pacientes._

_Gestión de citas médicas._

_Registro y consulta de historias clínicas._

_Gestión de tratamientos y recetas._

_Gestión de referimientos médicos._

_Gestión de médicos._


**-Arquitectura seleccionada**
Se propone una arquitectura en capas con separación cliente-servidor, organizada en cuatro componentes principales:

_**Frontend:**_ interfaz con la que interactúan los usuarios.

_**Backend:**_ procesamiento de solicitudes y aplicación de las reglas de negocio.

_**Autenticación y autorización:**_ verificación de identidad y control de permisos.

_**Base de datos:**_ almacenamiento organizado de la información.


**-Organización de frontend y backend**

_**Frontend**_ Será responsable de mostrar las pantallas, formularios y opciones de navegación. Permitirá registrar y consultar información según los permisos del usuario.

_**Backend**_ Procesará las solicitudes del frontend, validará los datos, aplicará las reglas de negocio y gestionará las consultas y actualizaciones en la base de datos.

**Comunicación entre componentes** Se propone utilizar una API con solicitudes HTTP o HTTPS e intercambio de datos en formato JSON. El backend se comunicará con la base de datos y aplicará los controles de autenticación y autorización correspondientes.


**-Seguridad**
Se deberán considerar el control de acceso por roles, la protección de las comunicaciones, las copias de seguridad y la confidencialidad de la información médica.


**-Herramientas utilizadas**

_**GitHub:**_ alojamiento y control de versiones del proyecto.

_**GitHub Issues:**_ registro y seguimiento de tareas y requisitos.

_**GitHub Projects:**_ organización visual del avance.

_**Visual Paradigm Online:**_ diseño de diagramas y modelos.

_**Microsoft Word:**_ elaboración de documentación técnica.


**Estado actual del proyecto**
El proyecto cuenta con requisitos y funcionalidades identificados, tareas organizadas en GitHub Projects y GitHub Issues, un diseño inicial de arquitectura en Visual Paradigm Online y avances en la documentación del modelo de datos.

El sistema se encuentra en una etapa de planificación y diseño. La implementación funcional, la integración de los componentes y las pruebas permanecen como actividades pendientes.


**-Próximos pasos**

- Revisar y validar los requisitos.

- Completar el diseño del modelo de datos.

- Definir los controles de seguridad.

- Implementar las funcionalidades prioritarias.

- Realizar pruebas funcionales y de seguridad.

- Mantener actualizados la documentación y el historial de cambios.
