# DrDoctor
To build a docker image:
Run the following command to build the docker image with tag the name as "drdoctor-app".

docker build . -t drdoctor-app:latest

Run the Docker image:

Step 1: Make sure that required port 3000 is free and not listening or used by any other application

Step 2: Run the following command to run the container
        docker run -it -d -p 3000:3000 drdoctor-app

Manual steps to run the app:

Step1: git clone the project directory

Step2: Run npm install

Step3: Run npm run start
