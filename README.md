# 3. MySQL

# Instrucciones para ejecutar la consulta MySQL

Este documento describe cómo ejecutar el ejercicio de consulta de MySQL

## Instrucciones SQL

### 1. Crear base de datos

        ```sql
        CREATE DATABASE Usuario;
        ```


### 2. Seleccionar la base de datos

        ```sql
                USE Usuario;
        ```


### 3. Crear la tabla Usuarios

        ```sql

        CREATE TABLE Usuarios (
                id INT AUTO_INCREMENT PRIMARY KEY, 
                nombre VARCHAR(50) NOT NULL,
                email VARCHAR(50) NOT NULL, 
                fecha_de_registro DATE NOT NULL);
        ```


### 4. Insertar registros a la  Usuarios

        ```sql
                INSERT INTO Usuarios (nombre, email, fecha_de_registro)
                VALUES
                ('Daniel Fragoso', 'danifrag07@gmail.com', '2024-03-11'),
                ('Luis Gonzalo Hernandez', 'luisgonher@gmail.com', '2024-07-23'),
                ('Gael Reyes', 'gael1108@gmail.com', '2024-10-10');
        ```


### 5. Consultar los registros 

        ```sql
               SELECT * FROM Usuarios;
        ```

