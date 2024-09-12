## Create repo 

- with workflow file in .github/workflows/deploy.yml
- Dockerfile exposing port 3001
- secrets variables in github repo : 
    -VPS_IP
    -VPS_PORT
    -VPS_USER
    -VPS_PASSWORD
    -REPO_GIT (example: https://github.com/rider974/dockerhub_test.git)

## tag version 

use  command: 

```sh
git tag 
``` 

## 