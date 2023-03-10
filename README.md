Lo primero despues de crear el repositorio hay que hacer una copia en local con el comando git clone y el nombre del repositorio, en este caso seria git clone https://github.com/ToniRiutort/masterpidgey-examen.git
![image](https://user-images.githubusercontent.com/104781981/224254758-99171e4f-9673-47f5-b477-a2762bcf8333.png)

Ahora tenemos que entrar en el repositorio creado en local, que lo hacemos con el uso del comando cd en este caso seria cd Masterpidgey-examen/
![image](https://user-images.githubusercontent.com/104781981/224254958-ed332c23-42ad-4c04-9160-d20ec97f76e5.png)

Ahora tenemos que crear el README desde la consola, que se hace utilizando el comando nano el nombre del archivo que queremos crear y su extensión, en este caso seria nano README.md
![image](https://user-images.githubusercontent.com/104781981/224255488-34f08bd9-5a2c-4ee3-b941-e9de31632eea.png)

Dentro del nano ponemos lo que queramos dentro en este caso seria la explicación del git clone y su comando
![image](https://user-images.githubusercontent.com/104781981/224255757-1cc76c02-6c28-4626-9ae0-38086dac3238.png)

Ahora utilizamos el comando add para poder añadir el archivo README al commit para subirlo con el push más tarde, que lo explico despues, el comando seria git add README.md
![image](https://user-images.githubusercontent.com/104781981/224255991-a99a6d67-c3d3-4e29-9934-877b06bb0b85.png)

Ahora usamos el comando git commit -m "commit inicial" para tener preparado el archivo README para hacer el push
![image](https://user-images.githubusercontent.com/104781981/224256722-e9b745d5-7ba2-4612-b445-5ce3dbbda3a1.png)

Ahora para comprobar que el add y el commit estan bien hechos utilizamos el comando git status
![image](https://user-images.githubusercontent.com/104781981/224256956-1e89ea19-7728-4589-a54a-6ec933b8a9a3.png)

Sabiendo que lo anterior esta bien hecho ahora podemos utilizar el comando push para subirlo al repositorio online, seria git push --all
![image](https://user-images.githubusercontent.com/104781981/224257380-66025947-9c87-49c5-9c24-5ac29618394f.png)

Gracias al push anterior ya he subido al repositorio del github el README
![image](https://user-images.githubusercontent.com/104781981/224254483-55e48997-8e2a-4c03-abee-98e91f38349e.png)
