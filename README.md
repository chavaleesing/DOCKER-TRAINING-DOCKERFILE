# docker-training-dockerfile


![alt text](dd.png)

## Hello-World/ 

Build image name `hello-world`
```
docker build -t hello-world . 
```

Run container with `hello-world` image
```
docker run hello-world
```
---

## PieDock/

Build image name `pie-dock`
```
docker build -t pie-dock .
```

Run container with `pie-dock` image
```
docker run -d --name python-app -p 5000:5000 pie-dock
```

credit : \
https://medium.com/@ponggun/%E0%B8%9D%E0%B8%B6%E0%B8%81%E0%B8%A7%E0%B8%B4%E0%B8%8A%E0%B8%B2-docker-image-container-8765a513f2b4
https://medium.com/i-gear-geek/%E0%B9%80%E0%B8%82%E0%B8%B5%E0%B8%A2%E0%B8%99-docker-file-%E0%B9%83%E0%B8%AB%E0%B9%89%E0%B9%84%E0%B8%94%E0%B9%89-docker-image-d2dedd10361e
