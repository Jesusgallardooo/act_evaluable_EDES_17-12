[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ggNrffAq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17367078&assignment_repo_type=AssignmentRepo)



# Práctica 17-12-24 presencial

---

- **ID de la Actividad:** Práctica presencial evaluable
- **Módulo:** PROG
- **Unidad de Trabajo:** UD5: Diagramas estructurales, diagramas de clases.
- **Fecha de Creación:** 17/12/2024
- **Fecha de Entrega:** ?/12/2024
- **Alumno(s):**
    - **Nombre y Apellidos:** Jesús Gallardo Domínguez
    - **Correo electrónico:** jgaldom070@g.educaand.es
    - **Iniciales del Alumno/Grupo:** JGD
---

### 1 . Interpreta el significado del diagrama de clases.

#### **a)** Relación entre clases; significado, tipo, multiplicidad... 

La relación entre estas dos clases es de agregación. Se irán 'agregando' alumnos a los cursos deseados.

La clase Estudiante se relaciona con la clase Curso de manera que sus métodos permitirán ir desarrollando 
un sistema que almacene datos sobre un curso, y permita a cada estudiante inscribirse en algún curso e ir almacenándolos en
dicho curso concreto. 

En un curso podrá haber 1 o muchos alumnos, y un alumno  puede pertenecer a varios cursos, por el método de estudiante de mostrarInscritos(). 


#### **b)** Elementos de las clases; Tipos y propósito.

En este diagrama de clases, existen 2 clases, Curso y Estudiante. La clase Curso tiene los atributos 'nombre' y 'código'
ambas de tipo str, y un solo método 'agregarAlumno(alumno)', el cual asumo que irá almacenando alumnos en el curso. Mientras
que la clase Estudiante tiene los atributos 'nombre' y 'dni', ambas de tipo str, y 2 métodos 'inscribirse(curso)' y
'mostrarInscritos()'.

El propósito de estos elementos es crear un sistema funcional para gestionar los datos de los alumnos que estén inscritos en 
algún curso.

#### **c)** Significado de agregarAlumno; Funcionamiento.

Este método añadirá el alumno que se le pase por parámetro al curso que deseemos. creando poco a poco un curso con más y más
alumnos 

### 2 . Generación de código a partir del diagrama de clases.

#### **a)** Crea clases.

#### **b)** Crea relaciones.

#### **c)** Crea un 'main' para probar el sistema.

(Respuestas en src en el archivo de código)