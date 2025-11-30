# Whisper-API-in-Docker-Container
Whisper is an AI for transcribing audio to text. This project adds an API-Server built using FastAPI inside a Docker container.

# local run 
docker run -dit --name=whisper-api -p 8000:8000 whisper-api:1.0

# test-use 
call localhost:8000/docs 
its a swagger api - testupload your mp3-file there and get a transcibed result

