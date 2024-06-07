# infra

I built the images to the Github Container Registry. 

However, I think you can build the images locally from each repo without having to pull them:
* To do so, on each repo, ```run docker build -t {image as it appears on the infra's docker compose}```
  
  e.g. ```run docker build -t ghcr.io/tps-ingenieria-de-sistemas/snippet-service:latest```


Otherwise, retrieve them from:
* ```docker pull {image}```

  e.g. ```docker pull ghcr.io/tps-ingenieria-de-sistemas/snippet-service:latest```

I'd recomend doing the first option first and, if it doesn't work, the second one. However, I'm almost certain the second one works fine.





