# Plataforma de Ludificación Educativa - Ludik
Una aplicación web Full-Stack diseñada para transformar la experiencia de aprendizaje en la educación secundaria, aumentando la motivación y el compromiso de los estudiantes a través de la ludificación.

Nota: El código fuente de este proyecto es privado. Este repositorio sirve como un "escaparate" técnico y funcional, detallando la arquitectura, características y proceso de desarrollo del proyecto.

## El Problema: La Desconexión en el Aula
Los modelos educativos tradicionales a menudo luchan por mantener un alto nivel de compromiso en los estudiantes de secundaria. La falta de feedback inmediato, la dificultad para visualizar el progreso a largo plazo y la monotonía pueden llevar a una disminución de la motivación, afectando directamente el rendimiento académico y la percepción del aprendizaje.

## La Solución
Nuestra plataforma aborda este desafío de frente, convirtiendo el proceso educativo en una experiencia interactiva y gratificante. A través de un sistema robusto de ludificación, los estudiantes pueden:

* Visualizar su progreso de manera clara e intuitiva, como si estuvieran avanzando en un juego.

* Ganar medallas y recompensas por alcanzar hitos académicos y participar en clase.

* Competir sanamente a través de rankings y tablas de liderazgo.

* Personalizar su perfil y sentirse parte de una comunidad de aprendizaje activa.

## Características Principales
* Gestión de Perfiles Personalizables: Cuentas separadas para alumnos y profesores, con perfiles que incluyen avatares, medallas ganadas y estadísticas de progreso.

* Sistema de Grupos y Cursos: Los profesores pueden crear grupos para sus materias y generar códigos de invitación únicos para que los alumnos se unan fácilmente.

## Motor de Ludificación Avanzado:

* Medallas y Logros: Creación y asignación de medallas personalizadas por parte de los profesores para reconocer el esfuerzo y los logros.

* Tienda de Recompensas: Los estudiantes pueden canjear las monedas ganadas por recompensas virtuales.

* Metas Personales: Los alumnos pueden establecer sus propias metas y seguir su progreso para alcanzarlas.

* Rankings y Tablas de Liderazgo: Fomenta una competencia sana mostrando rankings basados en medallas obtenidas.

* Sistema de "Kudos": Una funcionalidad social que permite a los estudiantes otorgar reconocimientos a sus pares, aumentando la interacción positiva.

* Proyectos de Aula Colaborativos (PAC): Herramientas para gestionar y dar seguimiento a desafíos al grupo, fomentando la colaboración.

* Autenticación Segura: Implementación de JSON Web Tokens (JWT) para proteger las rutas y asegurar el acceso a la información.

## Stack Tecnológico y Arquitectura
Este proyecto fue construido utilizando tecnologías modernas y siguiendo las mejores prácticas de la industria para garantizar un producto escalable, mantenible y robusto.

| Área  | Tecnología / Práctica|
| ------------- |:-------------:|
| Backend      | ASP.NET Core 8 (Web API), C#    |
| Frontend      | React     |
|Base de Datos     | SQL Server     |
|Arquitectura     | Arquitectura Limpia (Clean Architecture), Patrón RESTful   |
|Autenticación     | JSON Web Tokens (JWT)     |
|Pruebas Unitarias     | xUnit (lógica de negocio) y Moq (para mocks   |
|Entorno de Dev     | Visual Studio 2022, VS Code, Git & GitHub |  

## Un Proyecto Ágil: Adaptación y Crecimiento del Alcance
El proyecto se gestionó bajo un marco de trabajo Scrum, lo que permitió una notable adaptabilidad y crecimiento. Partiendo de un Product Backlog de 28 requerimientos funcionales, el producto final entregó un total de 45, demostrando la capacidad para responder a nuevas ideas y necesidades técnicas que surgieron durante el desarrollo.

## Decisiones Estratégicas
Durante el desarrollo, se tomaron decisiones clave para maximizar el impacto del producto. Por ejemplo, se postergó la implementación de la "recuperación de contraseña para profesores" y la "asignación de medallas entre alumnos" para priorizar funcionalidades emergentes de mayor valor, como el innovador sistema de "Kudos".

## Funcionalidades Emergentes de Alto Valor
El alcance se expandió para incluir 19 nuevos requerimientos. Mientras que algunos fueron de soporte técnico para la arquitectura, otros añadieron un valor inmenso a la experiencia del usuario, entre ellos:

* Gestión de Recompensas del Perfil: Enriqueció la personalización del estudiante.

* Sistema de "Kudos" Semanales: Aumentó la interacción social y el reconocimiento positivo.

* Proyectos de Aula Colaborativos (PAC): Introdujo una dimensión de trabajo en equipo directamente en la plataforma.

Esta evolución del alcance refleja un proceso de desarrollo realista y centrado en el cliente, donde la retroalimentación y la ideación continua son fundamentales para construir el mejor producto posible.
## Screenshots de la Aplicación

<img width="1911" height="877" alt="autenticacion" src="https://github.com/user-attachments/assets/4cd2954c-7b02-497d-a26b-fea51a1936be" />

### Vista Profesor

<img width="2037" height="879" alt="creacionDeRecompensaVistaProfesor" src="https://github.com/user-attachments/assets/65694d13-11db-443b-aef4-174e519f880f" />
<img width="1903" height="873" alt="crearUnRankingVistaProfesor" src="https://github.com/user-attachments/assets/0943ef0f-b3a9-40de-a74f-60eda8ef2834" /><img width="1895" height="867" alt="detallesDeUnGrupoVistaProfesor" src="https://github.com/user-attachments/assets/58820681-000c-4b4c-91ae-361610f795e8" />
<img width="1892" height="866" alt="estudiantesQueTieneUnCursoVistaProfesor" src="https://github.com/user-attachments/assets/ded6af81-711b-4cb7-83ca-1929835b8a09" />
<img width="1917" height="872" alt="menuHamburguesaDesplegadoVistaProfesor" src="https://github.com/user-attachments/assets/cdae9488-61de-481f-8483-ccf8b093bde1" />
<img width="1910" height="878" alt="pantallaInicioVistaProfesor" src="https://github.com/user-attachments/assets/14fabd12-8ffe-4fb5-aed7-6e0f3a5c40b9" />
<img width="1905" height="879" alt="verDetallaDeRankingVistaProfesor" src="https://github.com/user-attachments/assets/1acf1c9a-ed22-4dc0-81ff-a28d625c1557" />

### Vista Estudiante
<img width="1864" height="863" alt="companierosCursoVistaEstudiante" src="https://github.com/user-attachments/assets/3070873a-eb14-4ffe-a5a4-1e22d5b7a839" />
<img width="1888" height="865" alt="personalizarAvatarVistaEstudiante" src="https://github.com/user-attachments/assets/b785a009-cfed-4ece-8176-b73f83b2b923" />
<img width="1889" height="841" alt="rankingVistaDetalladaVistaEstudiante" src="https://github.com/user-attachments/assets/73f722a3-bd58-43d0-9a6c-c17a17150177" />
<img width="1907" height="861" alt="rankingVistaEstudiante" src="https://github.com/user-attachments/assets/930baa8c-f09e-40a6-bcb2-c37aa796ba42" />
<img width="1895" height="875" alt="tiendaDelGrupoVistaEstudiante" src="https://github.com/user-attachments/assets/697af6c5-fb6b-459c-8462-c2417735ba0d" />
<img width="1885" height="885" alt="vistaGeneralDelPerfilDelEstudianteEnUnGrupoVistaEstudiante" src="https://github.com/user-attachments/assets/2d2e6c7e-8ad1-446c-ab8d-2a55fd42c339" />

## Videos de la Aplicación
* https://youtu.be/2DTUCDe3Gtc
* https://youtu.be/kBxWB5np4ZE
* https://youtu.be/c0EYGpbdIzo

## 👨‍💻 Contacto
Renato Ríos Seguí

* LinkedIn: https://www.linkedin.com/in/renato-ríos/
* Email: contacto@riosrenato.com
* Celular: +598 919 651 98
