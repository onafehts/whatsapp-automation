# whatsapp automation

docker-compose file for a ready-to-go local whatsapp automation setup with n8n and Evolution API


1. Install Docker: https://www.docker.com/products/docker-desktop/

2. Create a folder and copy the 'docker-compose.yaml' file into it
![image](https://github.com/user-attachments/assets/ce25bf94-6fa5-44f8-a302-aec06bd4d09d)

3. Open the terminal or powershell from the folder (ex.: 'File'> 'Open Powershel' on windows 10)
![image](https://github.com/user-attachments/assets/0e53fee0-0529-4945-8b9c-05fbcf406874)

4. Start Docker (if not already) and in the opened terminal type 'docker compose up -d' and press enter

5. Once it's done, close the terminal and go to Docker.


Done. 

Now you can access n8n on http://localhost:5678/ to create your local account
and the evolution API http://localhost:8080/manager with the password '429683C4C977415CAAFCCE10F7D57E11' which is also in the docker-compose.yaml file as 'AUTHENTICATION_API_KEY'.

Reference youtube video: tbd

