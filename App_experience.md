# Running a sample application
To run the sample application, I complted the below steps:
1. Download the ZIP file folder using the [Download the App contents](https://github.com/docker/getting-started/tree/master/app) link.
2. Unzip the folder and extract all the files.
3. Open the project in any code editor. The project contains Package.json file with src and spec as sub files.
## Creating container image for the application
To build an application, we need to have a dockerfile. To create a docker file:
1. Create a file Dockerfile in the same folder where package.json is stored
2. Use the docker build command to build the container image for the app.
## Running the application
After the image is created, we can run the application. To run the application:
1. Use the docker run command to start the container and specify the name of the image.
2. Open the web browser and go to [http://localhost:3000](http://localhost:3000). You can see the app.

