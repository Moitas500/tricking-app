# 🌀 Tricking Progress RPG – Database & System Design

Tricking Progress RPG es una aplicación diseñada para que los atletas de *tricking* puedan registrar su progreso, aprender trucos, crear combos y recibir recomendaciones personalizadas.  
La app funciona como un **RPG**, donde el usuario obtiene experiencia, sube de nivel y mejora estadísticas a medida que entrena.

---

## 📌 Características principales

- Registro de trucos aprendidos por el usuario.
- Dominio y nivel de maestría para cada truco.
- Sistema de experiencia y niveles estilo RPG.
- Creación de combos y secuencias de trucos.
- Recomendación de combos según habilidades del usuario.
- Registro detallado de sesiones de práctica.
- Tracking de intentos, éxitos y variaciones.
- Clasificación por categoría, dificultad y variaciones.
- Estadísticas por usuario (trucos aprendidos, variaciones dominadas, combos, etc).

---

## 🗂️ Modelo de Base de Datos

El proyecto utiliza un modelo relacional con enfoque en:

- **Entidades principales:** User, Trick, Combo  
- **Tablas puente:** UserTrick, ComboTrick, UserCombo  
- **Sistema de práctica:** Practice, PracticeDetails  
- **Clasificación:** Category, Difficulty, Variation  

### 📎 Diagrama ER
<img width="1275" height="723" alt="image" src="https://github.com/user-attachments/assets/b8a2dd5e-0646-4f8b-89f3-5697dbdc97c4" />
