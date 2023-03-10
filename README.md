# Masterpidgey-examen
## Primera parte
Lo primero despues de crear el repositorio hay que hacer una copia en local con el comando git clone y el nombre del repositorio, en este caso seria git clone https://github.com/ToniRiutort/masterpidgey-examen.git

![image](https://user-images.githubusercontent.com/104781981/224254758-99171e4f-9673-47f5-b477-a2762bcf8333.png)

Ahora tenemos que entrar en el repositorio creado en local, que lo hacemos con el uso del comando cd en este caso seria cd Masterpidgey-examen/

![image](https://user-images.githubusercontent.com/104781981/224254958-ed332c23-42ad-4c04-9160-d20ec97f76e5.png)

Ahora tenemos que crear el README desde la consola, que se hace utilizando el comando nano el nombre del archivo que queremos crear y su extensión, en este caso seria nano README.md

![image](https://user-images.githubusercontent.com/104781981/224255488-34f08bd9-5a2c-4ee3-b941-e9de31632eea.png)

Dentro del nano ponemos lo que queramos, en este caso seria la explicación del git clone y su comando

![image](https://user-images.githubusercontent.com/104781981/224255757-1cc76c02-6c28-4626-9ae0-38086dac3238.png)

Ahora utilizamos el comando add para poder preparar el archivo README para el commit para subirlo con el push más tarde, que lo explico despues, el comando seria git add README.md

![image](https://user-images.githubusercontent.com/104781981/224255991-a99a6d67-c3d3-4e29-9934-877b06bb0b85.png)

Ahora usamos el comando git commit -m "commit inicial" para tener preparado el archivo README para hacer el push

![image](https://user-images.githubusercontent.com/104781981/224256722-e9b745d5-7ba2-4612-b445-5ce3dbbda3a1.png)

Ahora para comprobar que el add y el commit estan bien hechos utilizamos el comando git status

![image](https://user-images.githubusercontent.com/104781981/224256956-1e89ea19-7728-4589-a54a-6ec933b8a9a3.png)

Sabiendo que lo anterior esta bien hecho ahora podemos utilizar el comando push para subirlo al repositorio online, seria git push --all

![image](https://user-images.githubusercontent.com/104781981/224257380-66025947-9c87-49c5-9c24-5ac29618394f.png)

Gracias al push anterior ya he subido al repositorio del github el README

![image](https://user-images.githubusercontent.com/104781981/224254483-55e48997-8e2a-4c03-abee-98e91f38349e.png)

Si ahora usamos el comando git status nos saldra que ya no hay nada para hacerle commit, que también es otra forma de comprobar que el push a funcionado bien

![image](https://user-images.githubusercontent.com/104781981/224258702-bc49add3-5fee-4476-b4d8-c7515fe2c3e5.png)

Para crear una carpeta en un directorio utilizamos el comando mkdir y el nombre, en este caso seria mkdir privada

![image](https://user-images.githubusercontent.com/104781981/224259951-abd5fb2f-d6c6-4c54-abba-d6a05a506fd7.png)

Para entrar dentro de la carpeta es igual que cuando quieres entrar dentro del repositorio con un cd, en este caso cd privada

![image](https://user-images.githubusercontent.com/104781981/224260113-ca5693ac-0ce9-4853-8a6e-585828e717d6.png)

Ahora creamos el archivo privado.txt con el nano, en este caso seria nano privado.txt

![image](https://user-images.githubusercontent.com/104781981/224261222-4173bc57-8eb5-4cc9-8320-1efc0a0348b8.png)

Dentro del archivo privado.txt, yo he puesto como seria imprimir por pantalla Hola mundo en Java

![image](https://user-images.githubusercontent.com/104781981/224260908-1951cc8a-aa6c-469f-b5e6-10da750f87c0.png)

Ahora para poder hacer que el github ignore la carpeta privada, primero tenemos que salir de la carpeta usando cd ..

![image](https://user-images.githubusercontent.com/104781981/224261943-ad4e3fb0-5263-4b1e-839d-fff47422a796.png)

Lo siguiente es crear el gitignore con un touch, el comando seria touch .gitignore

![image](https://user-images.githubusercontent.com/104781981/224262470-df44e7d7-045d-4b0a-b745-bee28f4031b0.png)

Para indicarle lo que tiene que ignorar utilizaremos un nano, para entrar dentro y ya dentro se lo indicamos, que el comando seria nano .gitignore

![image](https://user-images.githubusercontent.com/104781981/224263779-8aa298be-f803-4d00-a077-e819444f513b.png)

Dentro del nano del .gitignore tenemos que poner /nombrecarpeta, en este caso es /privada

![image](https://user-images.githubusercontent.com/104781981/224263259-60b4696b-529e-4a33-bb95-ac0ac59f5eb2.png)

Lo siguiente es crear un fichero llamado 1.txt, asi que utilizamos el comando touch 1.txt

![image](https://user-images.githubusercontent.com/104781981/224265295-fa6d1cce-3cb6-468c-aa13-f5e2c36f3bae.png)

Para añadir algo de texto dentro utilizaremos el comando nano, en este caso seria nano 1.txt

![image](https://user-images.githubusercontent.com/104781981/224265380-63998cb5-faf9-4e65-a4bf-2a226e1ac2f7.png)

Dentro del nano yo he puesto como es un print en Python

![image](https://user-images.githubusercontent.com/104781981/224266291-f9816be1-871a-4497-be80-efe597bc5a8c.png)

Comandos usador hasta ahora, hay un par de push, ya que no me aclaraba de como ponerlo

![image](https://user-images.githubusercontent.com/104781981/224266900-375fcd6c-f70a-4d1d-b2aa-b2543df3b61d.png)

![image](https://user-images.githubusercontent.com/104781981/224267074-1ad92cd4-a2c3-4e35-9a1f-b5b7a8f06eb9.png)

Ahora voy a subir lo que llevo hecho hasta ahora al repositorio online, asi que primero hay que hacer el add de todo lo anterior, de la carpeta privada, del .gitignore y del fichero 1.txt

![image](https://user-images.githubusercontent.com/104781981/224269974-135dbd12-d25c-46c9-9a0c-722ff95a649c.png)

![image](https://user-images.githubusercontent.com/104781981/224270101-502133b5-5407-4c22-9c82-014745d8c3ff.png)

![image](https://user-images.githubusercontent.com/104781981/224270176-24814045-e455-415d-8657-127231a74a45.png)

![image](https://user-images.githubusercontent.com/104781981/224270256-8c50cdf2-5954-4425-9a5c-24289b603d34.png)

![image](https://user-images.githubusercontent.com/104781981/224270328-2b686618-42e4-48dd-a161-fed857d6a253.png)

![image](https://user-images.githubusercontent.com/104781981/224270382-a482544f-6823-4fa8-9dde-24abf43f5d0c.png)

Ahora toca hacer el commit de todo lo anterior y el comando seria git commit -m "Segundo commit"

![image](https://user-images.githubusercontent.com/104781981/224271288-245db36a-8bd9-4f71-942c-87f10b3570d4.png)

Despues de una par de contratiempos que explico más adelante, lo siguiente es usar el push para subirlos al repositorio online

![image](https://user-images.githubusercontent.com/104781981/224279187-ed68d566-a274-4707-bb6f-95ed24550229.png)

Ahora tenemos que hacer un tag llamado v0.1, asi que utilizamos el comando git tag v0.1

![image](https://user-images.githubusercontent.com/104781981/224279648-fae9013f-5ed5-40ce-a0a6-f2aa50a78809.png)

Para subir el tag al repositorio online utilizaremos el comando git push origin v0.1

![image](https://user-images.githubusercontent.com/104781981/224279724-e1c54df7-42a7-4e67-871f-13f2dc59aeb1.png)

Segunda visualización de los commits hechos hasta ahora, que las capturas empiezan el con el ultimo que se ve en el anterior apartado de visualización de commits, aunque al intentar hacer el push de la carpeta privada, del .gitignore y del 1.txt, he tenido unos problemas ya que el README del repositorio online no coincidia con el del local asi que he tenido que hacer un remote, un fetch y el merge

![image](https://user-images.githubusercontent.com/104781981/224278627-f63afa68-c8e0-49b3-81a7-16e50723bf6a.png)

![image](https://user-images.githubusercontent.com/104781981/224278725-cc7bab02-bd3c-42a9-afc9-88823ee59f19.png)

|        NOMBRE          |                       LINK                        |
|------------------------|---------------------------------------------------|
| Máximo Fernández Riera | [link a su github](https://github.com/maximofernandezriera) |

## Segunda parte
Lo primero de todo hay que hacer fork del repositorio

![image](https://user-images.githubusercontent.com/104781981/224283349-3f12f11a-71d0-4061-8fc9-555f87d517fb.png)

Ahora copiamos el link de nuestro fork y lo clonamos en la consola y entramos al clonado, eso lo hacemos utilizando los siguientes comando, git clone y link de lo que queremos clonar, en este caso seria git clone https://github.com/ToniRiutort/first-contributions.git y cd y el nombre de lo que acabamos de clonar, en este caso seria cd first-contributions/, para clonar y entrar respectivamente

![image](https://user-images.githubusercontent.com/104781981/224284007-a060eee5-00db-4738-8f8e-297059e495ea.png)

Ya dentro del repositorio clonado creamos un branch, si utilizamos el comando git switch -c branchTR, creamos y entramos al mismo tiempo al branch, para hacer nuestros cambios hay para luego subirlos al original

![image](https://user-images.githubusercontent.com/104781981/224284825-74a18b4a-cb81-48cc-b6c7-2ab56e3078c9.png)


Dentro del branch creamos un txt gracias al nano, para poder hacer una contribución

![image](https://user-images.githubusercontent.com/104781981/224286041-86005a86-c81c-4c16-a41a-1f353438655c.png)

Dentro del nano ponemos nuestra contribución

![image](https://user-images.githubusercontent.com/104781981/224285842-5709c556-5324-4442-807b-4198956a9af8.png)

Ahora si utilizamos un git status nos va a indicar que hay un cambio respecto al original

![image](https://user-images.githubusercontent.com/104781981/224286532-a0a3180b-cc0f-4b1b-88c1-212db54209ee.png)

Para poder subir los cambios al original primero tenemos que usar el comando git add y lo que queremos añadir en este caso seria git add ToniRiutort_examenpullrequest.txt

![image](https://user-images.githubusercontent.com/104781981/224286994-39fcaed7-60fb-44fb-b915-b19768a9921b.png)

Lo siguiente es utilizar el coamndo git commit -m "Un mensaje para el propietario para que lo acepte nuestros cambios", que en este caso seria git commit -m "Contribución para el examen"

![image](https://user-images.githubusercontent.com/104781981/224287307-756d3342-e31a-4933-9137-4a95d820a2d8.png)

Por ultimo para subir los cambios al repositorio online tenemos que hacer un git push origin "el nombre del branch" en este caso es git push origin branchTR

![image](https://user-images.githubusercontent.com/104781981/224288005-2631b478-fdf5-46d9-b5a9-f6e6b72a05ab.png)

Para completar la pull request vamos al repositorio online del fork que hemos hecho y nos tiene que salir este mensaje 

![image](https://user-images.githubusercontent.com/104781981/224293008-83bdcf82-d6ce-4c5d-a496-8d79188d6606.png)

Al pulsar en compare and pull reuqest tiene que salir esta pagina y le tenemos que dar al boton de abajo de create pull request

![image](https://user-images.githubusercontent.com/104781981/224293393-43a11933-d7ef-468f-bba4-a90278605563.png)

Al pulsar pulsar el boton de create pull request nos tiene que llevar a esta pagina donde la cual te indica si se puede hacer o no la pull request 

![image](https://user-images.githubusercontent.com/104781981/224293813-8a4e8ad7-d3e6-4d66-983f-8af6181616f7.png)

Y si el propietario lo permite nos saldra lo siguiente, que significa que se ha completa el merge

![image](https://user-images.githubusercontent.com/104781981/224293974-fab0df60-fd2d-44ba-9141-00a218a51e86.png)

## Conclusión
Este examen me ha obligado a demostrar todo los que sabia, ya sea por el problema planteado o por los problemas que me han ido surgiendo miestras lo hacia, lo que me ha ayudado a consolidar y confiar más en lo aprendido. 
