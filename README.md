# Proyecto: Estación Meteorológica 2026
## Especialidad / 5to Año
Este repositorio contiene el desarrollo integral de una estación meteorológica, integrando hardware con Arduino UNO, Programación en el Visual Studio Code en Python y Análisis de datos con MySQL.
----------------------------------------------------------------------------------------------------------------------------------------------
### Datos del Estudiante
| Apellido y Nombre | E-mail | GitHub |
| :--- | :--- | :--- |
| Vergara sofia| smvergara@escuelasproa.edu.ar | [ver perfil](https://github.com/sofii54/-estacion-meteorologica)|

----------------------------------------------------------------------------------------------------------------------------------------------
## 📂 Estructura del Proyecto

📁 **analisis_ipynb/**: Prototipado de datos y notebooks en Google Colab.
📁 **arduino_ino/**: Código fuente (.ino) para el microcontrolador Arduino UNO R3.
📁 **dashboard_pbix/**: Reportes interactivos en Power BI.
📁 **database_sql/**: Scripts de creación y gestión de base de datos en MySQL Workbench.
📁 **docs/**: Documentación técnica y marcos legales del software.
📁 **python_app/**: Aplicación de escritorio desarrollada en Python (POO).

----------------------------------------------------------------------------------------------------------------------------------------------
## 🛠️ Tecnologías Utilizadas


En este proyecto integramos diversas herramientas distribuidas en tres áreas clave:

### 🔬 Club de Ciencias (Análisis y Datos)
[Google Colab](https://colab.research.google.com/) - Prototipado de datos y uso de librerías científicas.
[MySQL Workbench](https://www.mysql.com/products/workbench/) - Diseño y gestión de la base de datos relacional.
[Power BI](https://powerbi.microsoft.com/) - Creación de dashboards interactivos para la visualización del clima.

### 🐍 Programación III (Software)
[Visual Studio Code](https://code.visualstudio.com/) - Entorno de desarrollo (IDE) principal.
[Python](https://www.python.org/) - Lenguaje de programación con enfoque en **POO** (Programación Orientada a Objetos).
**Librerías de Conexión**: Uso de conectores para vincular la lógica de Python con la base de datos.

### 🤖 Robótica (Hardware y Simulación)
[Arduino IDE](https://www.arduino.cc/en/software) - Programación del microcontrolador en **C++**.
[Tinkercad](https://www.tinkercad.com/) - Simulación del circuito electrónico y sensores.
**Componentes**: Arduino UNO R3, sensores de temperatura, humedad y presión para el prototipo físico.

----------------------------------------------------------------------------------------------------------------------------------------------



## 🚀 Estado del Arte y Funcionalidades Logradas

El proyecto actual implementa un sistema iterativo que resuelve de forma integral la captura, procesamiento y visualización de variables ambientales:

**Modelado de Datos:** Dataset inicial normalizado, libre de registros duplicados y estructurado de forma óptima para su exportación a la base de datos.
**Controlador de Estados Físico:** Simulación funcional en Tinkercad que clasifica rangos térmicos, activa alarmas sonoras y reporta diagnósticos en tiempo real mediante una pantalla LCD de forma autónoma.
**Backend Modular:** Arquitectura de software en Python que abstrae el comportamiento del hardware en código mediante el paradigma de Programación Orientada a Objetos (POO).

---

## 🛡️ Buenas Prácticas de Desarrollo Incorporadas

Para garantizar la escalabilidad y el orden del repositorio, se aplicaron los siguientes estándares profesionales:

**Gestión de Entorno:** Uso estricto de .gitignore para omitir archivos temporales del sistema y del lenguaje (como __pycache__/ y .pyc).
**Historial Limpio:** Implementación de commits semánticos y estructurados para un control de versiones claro en Git.
**Modularidad:** Separación de responsabilidades clara entre el firmware del microcontrolador, la lógica de negocio en Python y el motor de base de datos.
