# Instalacion de JDK en el SO
Raúl Glez Martín | 1º DAM | 23/09/2021

![image](https://user-images.githubusercontent.com/91153605/136655770-7b38afc5-ac40-4858-9dc7-2e5195835f40.png)

# 1.	¿Qué es JDK y como instalarlo?

JDK cuyas siglas significan Java Development Kit se caracteriza por ser un software usado para desarrollar programas en Java. Y los pasos a seguir para su instalación en Ubuntu son los siguientes: 
# 2.	Pasos para instalarlo

### 1º PASO
Abriremos la interfaz de mostrar aplicaciones y buscaremos la aplicación llamada terminal.

 ![image](https://user-images.githubusercontent.com/91153605/136655837-dccbf6f2-ff13-4cf2-9438-8e1cf917680b.png)

### 2º PASO
Una vez abierta la terminal procedermos a intoducir el comando “sudo apt-get update”.

 ![image](https://user-images.githubusercontent.com/91153605/136655828-792a11be-f58a-423d-b66f-c228bedb8f94.png)

### 3º PASO
Una vez introducido el comando anterior y finalizido su proccedimiento, introduciremos el comando “ sudo apt-get install default-jdk” y si llegara a preguntarnos “¿desea continuar?” precionaremos enter.

 ![image](https://user-images.githubusercontent.com/91153605/136655849-edf074b7-b0bc-4384-8dad-01e6f9259c93.png)

### 4º PASO
Tras instalar Java comprobaremos de que versión se trata con el comando “java –version” ya que la que nos interesa es la 8. 

 ![image](https://user-images.githubusercontent.com/91153605/136655816-b28db691-5e1d-41c3-ad50-d279279ddc0e.png)

### 5º PASO
Tras comprobar que nuestra versión de Java que no es la 8 procederemos a instalarla con el comando “sudo apt install openjdk-8-jdk”.

 ![image](https://user-images.githubusercontent.com/91153605/136655812-47cbfd7f-5953-4edb-80d2-8612e92379f7.png)

### 6º PASO
Una vez terminado el proceso volveremos a comprobar nuestra versión de java con el comando “java –version” para así verificar que definitivamente tenemos instalada la 8, en caso de no tenerla deberemos contniuar con el paso 7. 

 ![image](https://user-images.githubusercontent.com/91153605/136655809-176edfcc-5ad5-465f-ab3c-b9bf7890a9a2.png)

### 7º PASO
Para definitivamente poder instalar la versión número 8 tenemos que configurar la variable de entorno y encontrar la ubicación del archivo para así poder ejecutarlo. 
El primer paso será ejecutar el comando “ls /usr/lib/jvm” para verificar las versiones que tenemos descargadas de OpenJDK.

 ![image](https://user-images.githubusercontent.com/91153605/136655807-3f84fd2e-f359-4a46-a052-20526c8686f4.png)

### 8º PASO
Actualizaremos las variables de entorno con el comando “nano /etc/profile”
(a partir de aquí no sé cómo continuar pues llevo horas intentando cosas y no sé cómo seguir)


