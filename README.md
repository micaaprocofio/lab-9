# lab-9
Abrir configuracion con el comando "sudo nano /etc/mysql/mysql.conf.d/mysqld.cnf"

<img width="1440" alt="Captura de pantalla 2024-05-27 a la(s) 9 31 07 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/16df0a09-01f1-47bf-a353-9f899c9120d7">

Cambio de ip a 0.0.0.0 en el bind-address para permitir que cualquier ip se pueda conectar

<img width="1440" alt="Captura de pantalla 2024-05-27 a la(s) 9 09 01 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/45b7c57e-fa67-46a8-b871-6d5c872975c2">

Se reinicia el mysql con el comando "sudo systemctl restart mysql" para que tome la nueva configuracion

<img width="1440" alt="Captura de pantalla 2024-05-27 a la(s) 9 31 07 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/16df0a09-01f1-47bf-a353-9f899c9120d7">

Creacion de la regla de entrada al puerto 3306 en la maquina virtual para que cualquiera pueda acceder

<img width="1440" alt="Captura de pantalla 2024-05-27 a la(s) 9 35 52 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/c56bce9b-3bef-4016-88bd-6d6fe0967dc1">

Puerto de entrada creado satisfactoriamente

<img width="1440" alt="Captura de pantalla 2024-05-27 a la(s) 9 36 26 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/e6367e12-b715-4c6f-96e3-4c9eed8167b1">

Logueo en mysql

<img width="777" alt="Captura de pantalla 2024-05-17 a la(s) 10 13 09 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/4b03b8c0-158a-4d6d-aab8-e15f2123699c">

Creacion de la base de datos

<img width="334" alt="Captura de pantalla 2024-05-17 a la(s) 10 16 13 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/fd0c752a-21a9-4861-ba31-013c63d9147c">

Nos paramos sobre esa base de datos para poder crear luego la tabla

<img width="320" alt="Captura de pantalla 2024-05-17 a la(s) 10 16 23 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/99b4cc79-79cc-469a-982a-c01c72af0042">

Creacion de la tabla usuarios

<img width="820" alt="Captura de pantalla 2024-05-17 a la(s) 10 16 36 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/b73273e0-e3ad-46fc-b83d-d99fb16bf7ee">

Se realizo un SELECT para ver que se haya creado la tabla

<img width="291" alt="Captura de pantalla 2024-05-17 a la(s) 10 16 52 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/cae3dad6-78d0-4bd4-a556-e8fb72587ec4">

Se le insertaron 3 registros a la tabla

<img width="475" alt="Captura de pantalla 2024-05-17 a la(s) 10 17 04 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/53750f6f-43db-4592-b9c0-f13b8d193b91">

Se realizo una consulta a la tabla para ver que se hayan insertado los registros correctamente

<img width="385" alt="Captura de pantalla 2024-05-17 a la(s) 10 17 16 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/5d86e544-d6d9-47dc-9874-ae48ce109f82">

Creacion de usuario, donde se le da todos los privilegios y solo se le permite acceder a la base de datos ejemplo

<img width="549" alt="Captura de pantalla 2024-05-27 a la(s) 11 34 51 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/cd875991-6b01-4db1-b1c8-24c978f34225">
<img width="604" alt="Captura de pantalla 2024-05-27 a la(s) 11 35 04 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/acd27f3e-9916-4f69-aca9-221c5097dea1">
<img width="604" alt="Captura de pantalla 2024-05-27 a la(s) 11 35 19 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/ebf9219b-dd80-4572-8f6e-58f6b6252035">

Conexion satisfactoria desde el MySQLWorkBench

<img width="1028" alt="Captura de pantalla 2024-05-27 a la(s) 11 35 53 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/410432dc-1041-4368-bc97-c313d04d0d74">

Query con multiples consultas

<img width="1434" alt="Captura de pantalla 2024-05-27 a la(s) 11 50 01 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/eb8149fb-054b-458d-9098-42cf077ff79e">

Resultado de "SELECT * FROM usuarios;"

<img width="999" alt="Captura de pantalla 2024-05-27 a la(s) 11 50 20 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/86f138aa-aa21-4c21-8d13-88bc4dc127c5">

Resultado del INSERT a la tabla usuarios

<img width="999" alt="Captura de pantalla 2024-05-27 a la(s) 11 50 24 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/3ac0e3e4-6607-4857-b25a-e043491b579d">

Resultado de "SELECT * FROM usuarios WHERE email like '%mail.com%';"

<img width="999" alt="Captura de pantalla 2024-05-27 a la(s) 11 50 28 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/b1d0a3a8-4dfc-4e9a-be3e-a64f2768f72d">

Resultado del DELETE del usuario con el id 3

<img width="999" alt="Captura de pantalla 2024-05-27 a la(s) 11 50 32 a  m" src="https://github.com/micaaprocofio/lab-9/assets/163476050/7e79aa02-fb93-4fe4-be88-53ba1104d1ea">
