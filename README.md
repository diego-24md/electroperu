# Procedimientos

1. Clonar repositorio
git clone https://...

2. Restaurar la BD
```sql
CREATE DATABASE electrop Peru;
USE electrop Peru;

CREATE TABLE productos
(
  id INT AUTO_INCREMENT PRIMARY KEY,
  descripcion VARCHAR(50) NOT NULL,
  garantia TINYINT NOT NULL,
  precio DECIMAL(7,2) NOT NULL
) ENGINE = INNODB;
```

3. Abrir proyecto electrop Peru en VSCode.

4. Abrir la terminal CTRL + Ñ escribir:
```
npm install
```

5. Se ejecutará la instalación de todas las dependencias definidas en package.json

6. Crear e ingresar los parámetros en el archivo .env