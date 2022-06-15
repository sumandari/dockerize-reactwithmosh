## dockerize-reactwithmosh
dockerfile and docker-compose files for dockerizing react with mosh tutorial

- Copy the source codes into three different folder same level with the docker folder
  ```
  root_folder/
    |- docker/
    |- http-app/
    |- vidly/
    |- vidly-api-node/
  ```  
- change the directory to docker: `mkdir docker`
- build the images: `docker-compose build .`
- spin the containers: `docker-compose up` or add -d parameter to run containers on the background `docker-compose up -d`
