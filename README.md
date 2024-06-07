# infra

I built the images to the Github Container Registry. 

However, I think you can build the images locally from each repo without having to pull them:
* To do so, on each repo, ```run docker build -t {image as it appears on the infra's docker compose}```

Otherwise, retrieve them from:
* ```docker pull {image}```
  e.g. ```docker pull ghcr.io/tps-ingenieria-de-sistemas/snippet-service:latest```





