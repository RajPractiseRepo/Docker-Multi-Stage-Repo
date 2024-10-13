# Reducing Docker Image Size by 96% for a Portfolio application from 1.55GB to 58.7MB using multi-stages build.
 
 
 ## Docker multistage build Architecture Diagram

 ![gifgit](https://github.com/user-attachments/assets/4faa8704-6cfc-48b4-866b-897006dfdfb2)

 ################################################################################################

 # Initial docker image size (1.55GB):

 ![docker_1 55GB](https://github.com/user-attachments/assets/c2765a2d-2163-40f4-9ad0-d120fcae95b1)




 ################################################################################################

 ## Docker image using Slim as base image(655 MB):

 ![docker-slim-655mb](https://github.com/user-attachments/assets/2d334570-c614-4e00-b030-d8eec171ed63)


  ################################################################################################


  ## Docker image using Alpine as base image(592 MB):

  ![docker-alpine-588mb](https://github.com/user-attachments/assets/6027d67e-3008-45f1-858f-4b3dc788657e)


  ################################################################################################


  ## Docker image using Multi-stage serve (177 MB):

  ![docker-multistage-serve-177mb](https://github.com/user-attachments/assets/483bc211-19cb-44e8-adf9-3b225dded60d)


    ################################################################################################


 ## Docker image using Multi-stage as NGINX base image(58.7 MB):

 ![docker-multistage-nginx-58mb](https://github.com/user-attachments/assets/32da5c66-2ada-4514-9861-eb33feb9e557)


 ################################################################################################


 ## Finally Docker image size reduced from 1.5GB to 58.7MB (96% Reduction):

 ![dokcer-all-stages-image-size](https://github.com/user-attachments/assets/eccfb1f8-b534-40ab-9af8-6b65dd129f09)






 


 
