# 📚 Proyecto Académico – Introducción a Bases de Datos (UNLa, 2025)

Diseño de un sistema académico universitario utilizando **modelo entidad-relación (MER)** y normalización de datos.  
El proyecto fue desarrollado como parte de la materia *Introducción a Bases de Datos* en la Licenciatura en Sistemas (UNLa).

---

## 🎯 Objetivos del proyecto
- Representar la estructura de un sistema académico universitario mediante un **diagrama entidad-relación**.  
- Aplicar **normalización** para garantizar consistencia y evitar redundancia en los datos.  
- Implementar relaciones complejas entre entidades: estudiantes, profesores, materias, carreras, departamentos y exámenes.  
- Utilizar **MySQL Workbench** para el diseño visual y la generación del esquema.

---

## 🛠️ Entidades principales
- **Personas**: nombre, apellido, DNI, edad.  
- **Estudiantes**: matrícula, legajo, historial académico.  
- **Profesores**: identificación y relación con materias.  
- **Materias**: nombre, promoción, relación con carreras.  
- **Carreras**: vinculadas a departamentos.  
- **Exámenes**: descripción de temas y asociación con materias.  
- **Departamentos**: organización académica.  

---

## 🔗 Relaciones destacadas
- **materias_has_carreras** → relación muchos-a-muchos entre materias y carreras.  
- **profesor_encargado** → asignación de profesores a materias.  
- **examenes_materia** → asociación de exámenes con materias.  
- **cursada_materias** → registro de cursadas con fechas y notas.  

---

## 📂 Herramientas utilizadas
- **MySQL Workbench** → modelado visual y exportación de esquema.  
- **SQL** → definición de tablas, claves primarias y foráneas.  

---

## ▶️ Cómo visualizar
1. Abrir el archivo `final.txt` para ver la definición del esquema.  
2. Importar el modelo en **MySQL Workbench** para explorar las relaciones.  
3. Revisar el diagrama entidad-relación incluido en el repositorio.  

---

## 📌 Autor
**Elias Nahuel Ricarte**  
Estudiante de Licenciatura en Sistemas – Universidad Nacional de Lanús (UNLa)  
Primera experiencia académica en modelado y normalización de bases de datos.
