# 🤖 Recomendador de Cine y Series – Microsoft Copilot Studio

Este proyecto es una actividad académica para la clase de **Inteligencia Artificial**, donde se diseñó un **agente conversacional** en [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/) capaz de **recomendar películas y series** según las preferencias del usuario.  
El objetivo fue aprender a crear **agentes inteligentes** que no solo respondan preguntas, sino que también **ejecuten acciones automáticas**.

---

## 🎯 Objetivo del Proyecto
- Diseñar un **agente de IA** que interactúe de forma amigable con los usuarios.
- Permitir que el agente realice **recomendaciones personalizadas** de películas y series.
- Integrar **acciones automáticas** como enviar un correo con las recomendaciones o guardar la lista en un archivo Excel.

---

## ⚙️ Funcionalidades del Agente
- **Preguntas dinámicas**: El agente solicita géneros favoritos, géneros a excluir, actores preferidos, duración y año de estreno.
- **Generación de recomendaciones**: Ofrece estrenos recientes, clásicos destacados y sugerencias basadas en las respuestas del usuario.
- **Gestión de favoritos**: Permite guardar y compartir la lista de recomendaciones favoritas.
- **Acciones automáticas (Flujo)**:  
  - Enviar un **correo electrónico** al usuario.  
---

## 📂 Estructura del Proyecto
| Carpeta/Archivo             | Descripción                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `tema_agente.txt`             | Descripción del tema para generar el agente en Copilot Studio.              |
| `peliculas.txt`               | Base de conocimiento con películas y series para enriquecer las respuestas. |
| `README.md`                   | Documento de este repositorio.                                              |

---

## 🚀 Pasos para la Creación

1. **Creación del Agente**  
   - Se usó Copilot Studio para crear el agente **“Recomendador de Cine y Series”**.  
   - Se configuraron las intenciones para reconocer solicitudes como “recomiéndame una película” o “qué puedo ver hoy”.

     <img width="1127" height="609" alt="image" src="https://github.com/user-attachments/assets/8d5e3e6f-64a6-4ce1-a159-02d3c1338937" />

2. **Diseño del Tema**  
   - Se definió el tema con preguntas guiadas: géneros favoritos, exclusiones, actor/actriz, duración y año de estreno.
     <img width="1033" height="296" alt="image" src="https://github.com/user-attachments/assets/dd10060d-9397-4794-a6d8-c2a240f43578" />


3. **Base de Conocimiento**  
   - Se creó el archivo [`peliculas.txt`] con un catálogo de películas y series de distintos géneros (acción, comedia, drama, ciencia ficción, terror, clásicos y estrenos recientes).

     <img width="1198" height="397" alt="image" src="https://github.com/user-attachments/assets/43af825d-891f-4142-90d9-e04699a6a536" />


4. **Flujos (Acciones Automáticas)**  
   - Se diseñó un flujo para **enviar un correo** por el agente.
     <img width="1199" height="427" alt="image" src="https://github.com/user-attachments/assets/ccdea180-62ed-41f4-8b39-b51fc82a8c81" />

5. **Temas**  
     <img width="1210" height="811" alt="image" src="https://github.com/user-attachments/assets/70d222cc-8919-4837-9163-94255f5f0d9e" />



---

## 🧩 Tecnologías y Herramientas
- **Microsoft Copilot Studio** – Creación del agente conversacional.
- **Power Automate (Flujos)** – Automatización de envío de correos y generación de archivos.
- **GitHub** – Documentación del proyecto.

---

## 💡 Lecciones Aprendidas
- Cómo estructurar un **agente conversacional** con temas, entidades y preguntas personalizadas.
- Uso de **bases de conocimiento** en texto plano para enriquecer las respuestas.
- Integración de **flujos automáticos** para pasar de simples respuestas a **acciones reales**.

---

## 🔗 Próximos Pasos
- Integrar APIs externas para obtener datos actualizados.  
- Mejorar la personalización de las recomendaciones con filtros más avanzados.  
- Añadir autenticación para que cada usuario guarde su propia lista de favoritos.

---

## 👨‍💻 Autor
**Daniel Montezuma**  
Estudiante de Ingeniería de Sistemas – Universidad Icesi  
Actividad para el curso de **Inteligencia Artificial**
