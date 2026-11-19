# Diseño de Bases de Datos

Teorías, prácticas resueltas, un parcial de SQL y finales anteriores de Diseño de Bases de Datos (cursada 2025).

## [Teorías](2025/Teorías/)

Diapositivas de la cátedra en PDF, convertidas de las presentaciones originales sin el audio narrado. La cátedra recomienda seguirlas en orden numérico ([instructivo](2025/Teorías/INSTRUCTIVO.pdf)).

| Clase | Tema |
| --- | --- |
| [1_1](2025/Teorías/1_1%20presentacion.pdf) | Presentación de la materia y conceptos básicos: base de datos, DBMS, DDL y DML |
| [2_1](2025/Teorías/2_1%20Conceptual%20primera%20parte.pdf) | Modelo conceptual: entidades, relaciones, atributos y cardinalidad |
| [2_2](2025/Teorías/clase2_2.pdf) | Modelo conceptual: atributos compuestos, identificadores, jerarquías y derivados |
| [3_1](2025/Teorías/3_1%20conceptual%20segunda%20parte.pdf) | Revisión del modelo conceptual y modelo lógico |
| [4_1](2025/Teorías/4_1%20móndelofisicorelacional.pdf) | Modelo físico relacional: claves, conversión de relaciones e integridad referencial |
| [4_2](2025/Teorías/4_2%20Normalizacion.pdf) | Dependencias funcionales y formas normales |
| [5_1](2025/Teorías/5_1%20A%20R.pdf) | Álgebra relacional |
| [6_1](2025/Teorías/6_1%20SQL%20parte%201.pdf) | SQL: DDL, consultas, agregación, subconsultas y joins |
| [6_2](2025/Teorías/6_2%20SQL%20parte%202.pdf) | SQL: ejercicios resueltos |
| [7](2025/Teorías/7%20Optimizacion.pdf) | Optimización de consultas |
| [8_1](2025/Teorías/8_1%20transacciones%20primera%20parte.pdf) | Transacciones: propiedades ACID, estados, bitácora y doble paginación |
| [8_2](2025/Teorías/8%20_2%20transacciones%20segunda%20parte.pdf) | Transacciones concurrentes: seriabilidad, bloqueos y hora de entrada |

[CaSER 2.0.zip](2025/Teorías/CaSER%202.0.zip) es la herramienta de la cátedra para dibujar modelos conceptuales. Los ejemplos de CaSER (`.csr`) y los videos de los ejemplos de teoría no están en el repo; están en la [carpeta de Drive de la cátedra](https://drive.google.com/drive/folders/1_HfE-FjhlwMInBQoSAdSqrKD944sVSvj).

## [Prácticas](2025/Práctica/)

| Práctica | Enunciado | Resolución |
| --- | --- | --- |
| 1: modelado entidad-relación | [PDF](2025/Práctica/Práctica%201%20-%20Modelado%20Entidad%20Relación/Enunciado.pdf) | Un PDF por ejercicio en [Ejercicio N/](2025/Práctica/Práctica%201%20-%20Modelado%20Entidad%20Relación/) (1 a 9) |
| 2: modelado conceptual, lógico y físico | [PDF](2025/Práctica/Práctica%202%20-%20Modelado%20Conceptual%2C%20Lógico%20y%20Físico/Enunciado.pdf) | [Conceptuales](2025/Práctica/Práctica%202%20-%20Modelado%20Conceptual%2C%20Lógico%20y%20Físico/Conceptuales/) (ej. 1 a 6), [lógicos](2025/Práctica/Práctica%202%20-%20Modelado%20Conceptual%2C%20Lógico%20y%20Físico/Lógicos/) y [físicos](2025/Práctica/Práctica%202%20-%20Modelado%20Conceptual%2C%20Lógico%20y%20Físico/Físicos/) (ej. 1 y 2) |
| 3: álgebra relacional | [PDF](2025/Práctica/Práctica%203%20-%20Álgebra%20relacional/Enunciado.pdf) | [PDF](2025/Práctica/Práctica%203%20-%20Álgebra%20relacional/Resolución.pdf) |
| 4: SQL | [PDF](2025/Práctica/Práctica%204%20-%20SQL/Enunciado.pdf) | Un `.sql` por inciso en [Ejercicio N/](2025/Práctica/Práctica%204%20-%20SQL/) (1, 6 y 10 a 13) y un [repaso](2025/Práctica/Práctica%204%20-%20SQL/Repaso/Ejercicio-1/) con sus [consignas](2025/Práctica/Práctica%204%20-%20SQL/Repaso/Ejercicio-1/Consignas.txt) |

### Entorno para la práctica 4

[entorno-docker/](2025/Práctica/Práctica%204%20-%20SQL/entorno-docker/) levanta MySQL 8 y Adminer con [docker-compose.yaml](2025/Práctica/Práctica%204%20-%20SQL/entorno-docker/docker-compose.yaml). Los scripts de [initdb/](2025/Práctica/Práctica%204%20-%20SQL/entorno-docker/initdb/) crean y cargan una base por ejercicio (`tp4_ejercicio1` a `tp4_ejercicio13`).

## [Parciales](2025/Parciales/)

- [SQL, 11/11/2025](2025/Parciales/%5BSQL%5D%2011-11-2025/): [consignas](2025/Parciales/%5BSQL%5D%2011-11-2025/Consignas.txt) y una consulta por punto ([1.sql](2025/Parciales/%5BSQL%5D%2011-11-2025/1.sql) a [5.sql](2025/Parciales/%5BSQL%5D%2011-11-2025/5.sql)), sobre clientes, pedidos e ítems.

## [Finales](2025/Finales/)

[Todos los finales.pdf](2025/Finales/Todos%20los%20finales.pdf) reúne fotos de finales tomados entre 2017 y 2025. La mayoría son de multiple choice (10 preguntas: +1 la correcta, −0,5 la incorrecta) y dos mesas de 2024 fueron de preguntas para desarrollar. Algunas fotos tienen respuestas marcadas: unas son correcciones de la cátedra y otras, respuestas de alumnos, así que no conviene tomarlas como solución. La última página incluye un final de otra materia.
