## This application has been containerized

## Commands Used

 - ``` sudo docker ps ``` to list the containers running
- ``` sudo docker images ``` to list images
- ``` sudo docker rmi image_id --force ``` to remove image id
- ``` sudo docker stop container_id ``` to stop container
- ``` sudo docker start container_name ```  to started previously run or stopped container!


## To Build
- ```sudo docker build -t prateektl/python-flask:0.1.DEV . ```

## To Run
- ```sudo docker run -p 3000:3000 prateektl/python-flask:0.1.DEV```
