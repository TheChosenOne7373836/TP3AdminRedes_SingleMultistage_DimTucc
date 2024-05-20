# TP3AdminRedes_SingleMultistage_DimTucc
![funny image](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*d4l9rmmtG0H9EVZlYNaZLQ.png)
Hecho por [@Peanut](https://github.com/PeanutSouth) y [@Chosen](https://github.com/TheChosenOne7373836)

> [!Warning]
*Esto solo es una demostracion sobre dockers singlestage & multistage. No es un projecto que será mantenido en el futuro. Gracias por entender!

1) Entrar a la carpeta e ingresar a svelte-docker:
   Windows:  
```sh
cd .\svelte-docker\
```
   Linux:
```sh
cd express-gen-ts/
```

2) Una vez en svelte-docker ejecutar el siguiente comando: 
```sh
npm install
```

3) Luego ejecutar el siguiente comando dentro de la carpeta: 
```sh 
docker build -t dockerfile .
```

4) Correr la imagen con el siguiente comando:
```sh 
docker run --rm --name=TESTING -p 5000:80 -d dockerfile
```

5) Por ultimo, entrar al puerto 5000 para encontrar la app. 
    - Acceso puerto 5000: [http://localhost:5000/](http://localhost:5000/)