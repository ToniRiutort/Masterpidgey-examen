# Masterpidgey-examen
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

