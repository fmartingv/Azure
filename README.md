# Azure

Azure
Lo primero creamos una máquina virtual, en Azure con nuestra cuenta de estudiantes. En este caso la mía es de Ubuntu 22.04 y está en la zona 2 de East US 2. La configuramos para que se pueda ver añadiéndole los puertos necesarios de entrada y una vez todo guardamos la ip y la clave para entrar.
 
![image](https://github.com/fmartingv/Azure/assets/120713266/cdaf8ce7-d637-46a4-8a39-605289544256)

Una vez lo tenemos abrimos una terminal y ahí entramos con el SSH poniendo nuestro usuario (el default es azureuser) y la clave de mi maquina es myVm_key.pem que tengo guardada y así accedemos a ella.

 ![image](https://github.com/fmartingv/Azure/assets/120713266/06832e1e-1283-43dc-ae54-88654619ad66)

Una vez dentro vamos a hacer una prueba donde ejecutaremos una página con nginx, para eso hacemos los updates necesarios y descargamos lo que necesitemos como por ejemplo nano y nginx. Hacemos el index.html para nuestra página y en este caso haremos una muy simple.
 
![image](https://github.com/fmartingv/Azure/assets/120713266/d6e840a8-9e94-437d-8450-13eea3a954ac)

Tras comprobar que nuestro directorio donde ejecutamos la página, el mío es myweb, y que dentro este el index ejecutamos el nginx para así y hacemos el curl para ver la página y si va correctamente.

 ![image](https://github.com/fmartingv/Azure/assets/120713266/6ad945d5-d87c-4ce0-8dac-1c7a79c0d86b)

Así se vería en el navegador poniendo la ip publica de nuestra máquina virtual.
 
![image](https://github.com/fmartingv/Azure/assets/120713266/ee30990d-5580-42da-ad8e-0b9cddf8389f)
