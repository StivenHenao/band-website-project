
# 🎵 Band Website - IBM Back-End Development Capstone Project

Este proyecto es el resultado del curso **IBM Back-End Development Professional Certificate** en Coursera. El objetivo fue construir un sitio web completo para una banda musical, siguiendo una arquitectura basada en microservicios y desplegando cada componente en diferentes plataformas en la nube.

![Capstone Architecture](https://i.imgur.com/cZZLT8e.png)

## 🧩 Arquitectura del Proyecto

El sistema está compuesto por tres servicios principales:

1. **Main Site (Django)**  
   - Manejo de usuarios, conciertos y reservas.
   - Desplegado en IBM Kubernetes Service.
   - CRUD de conciertos.
   - Autenticación y registro de eventos.

2. **Get Songs Service (Flask)**  
   - Proporciona letras de canciones.
   - Usa MongoDB como base de datos.
   - Desplegado en Red Hat OpenShift.

3. **Get Pictures Service (Flask)**  
   - Muestra fotos de eventos pasados.
   - Usa IBM Cloud Object Storage.
   - Desplegado en IBM Cloud Code Engine.

---

## ⚙️ Funcionalidades

- 📸 Ver fotos de conciertos pasados
- 🎶 Ver letras populares de canciones
- 📅 Ver eventos próximos
- 🧾 Registrarse y reservar eventos
- 👤 Iniciar sesión para ver eventos registrados
- 🛠️ CRUD de conciertos (admin)

---

## 📂 Repositorios

| Servicio | Descripción | Enlace |
|---------|-------------|--------|
| 🎸 Main App (Django) | Aplicación central para usuarios, eventos y reservas | [Repositorio](https://github.com/StivenHenao/Back-end-Development-Capstone) |
| 🎼 Get Songs (Flask + MongoDB) | Servicio de letras de canciones | [Repositorio](https://github.com/StivenHenao/Back-End-Development-Songs) |
| 🖼️ Get Pictures (Flask + IBM COS) | Servicio de imágenes de conciertos | [Repositorio](https://github.com/StivenHenao/Back-End-Development-Pictures) |

---

## 🚀 Despliegue

- **Main App**: IBM Kubernetes Service  
- **Get Songs**: Red Hat OpenShift + MongoDB  
- **Get Pictures**: IBM Cloud Code Engine + Object Storage  

---

## 🧠 Tecnologías Utilizadas

- Python / Flask / Django  
- MongoDB, MySQL  
- IBM Cloud, Red Hat OpenShift, Kubernetes  
- Docker  
- GitHub

---

## 🏁 Resultado Final

¡Una plataforma web funcional con múltiples servicios desplegados profesionalmente en la nube, utilizando buenas prácticas de back-end y microservicios!

