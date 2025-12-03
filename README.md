# AldComputerService
Aplicación de escritorio en Java (Swing) para ayudar a la gestión de un taller de reparación de equipos.

---

## Descripción
Se trata de una aplicación simple hecha con Swing para un taller de administración y reparación de equipos con la finalidad de practicar diferentes conceptos.

Este proyecto ha servido como práctica para aplicar conceptos de:
- Programación orientada a objetos  
- Arquitectura MVC  
- Patrones como Singleton  
- Desarrollo de interfaces gráficas con Swing  
- Gestión modular de aplicaciones

---

## Características principales
- Gestión de la información del establecimiento
- Gestión de equipos informáticos y de sus respectivas reparaciones
- Configuración de alarma
- Generación de informes
- Documentación incluida (Manual de usuario, Tutorial y Guía de referencia

---

## Tecnologías utilizadas
- Java 8
- Java Swing
- JasperReports
- MariaDB
- JUnit
- NSIS

---

## Instalación y ejecución

### Requisitos
- Sistema operativo: Windows, Linux o MacOS
- Java Runtime Environment (JRE): Versión 8 o superior
- Base de datos: Configurada, accesible y de MariaDB.
- Memoria RAM: Mínimo 2GB recomendado.

### Clonar el repositorio
```bash
git clone https://github.com/RubenAC1999/AldComputerService.git
cd AldComputerService
```

### Ejecutar el instalador
En el repositorio viene incluido un instalador. Lo único que hay que hacer es ejecutarlo y seguir los pasos para generar el .JAR.

![instalacion](https://github.com/RubenAC1999/AldComputerService/blob/main/assets/instalacion.JPG)


## Estructura del proyecto

```text
Ald_rac/
│
├── src/
│   ├── controller/   # Controladores (lógica que conecta modelo y vista)
│   ├── model/        # Clases de negocio (Cliente, Equipo, Reparacion...)
│   ├── view/         # Formularios y ventanas Swing
│   └── Main.java     # Clase principal de la aplicación
│
├── Guia de referencia_ALDRAC.pdf
├── Manual de usuario_ALDRAC.pdf
├── ALDComputerService.exe
└── README.md
```

---

## Ejemplos de uso

### Ventana para añadir, editar o eliminar un equipo.
![gestion_equipos](https://github.com/RubenAC1999/AldComputerService/blob/main/assets/gestion_equipos.png)

### Ventana para añadir, editar o eliminar un servicio
![anhadir_reparacion](https://github.com/RubenAC1999/AldComputerService/blob/main/assets/gestion_reparaciones.png)

* Para mucha más información consultar los manuales del repositorio.*

## Licencia
Esta aplicación está bajo la licencia *MIT.*

## Autor
Rubén Agra Casal

Gmail: rubenagra99@gmail.com

LinkedIn: [rubenagradev](https://www.linkedin.com/in/rubenagradev/)

















