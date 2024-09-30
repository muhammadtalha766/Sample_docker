git pull origin main
docker-compose -f docker-compose-file.yaml down
docker-compose -f docker-compose-file.yaml up --build -d

these are 3 commands in jenkins script for running deployment
