# Servidor de live streaming
Servidor de LiveStreaming feito a partir do tutorial no Youtube da Lais Lima.

[Link para o tutorial](https://www.youtube.com/watch?v=CrEzeBwLZPU&t=1s)

## Como utilizar

Tenha o Docker e o Docker Compose instalado e execute o seguinte comando no terminal:

```sh
docker-compose up
```

Aponte o seu software de transmissão(Nesse caso foi utilizado o OBS estúdio) para o servidor RTMP na seguinte url:
```rtmp://localhost:1935/live```


Para visualizar, acesse a seguinte url com um visualizador de hls:

http://localhost:8081/live/.m3u8

