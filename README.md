# DotNetFrameworkUpWithDocker

1. Navigate to the root of your project folder that contains your Dockerfile at the command prompt or terminal.
2. Build the Docker image: docker build -t karinakuroda/dotnetframeworkupwithdocker .
3. Run the application in the container: docker run -d -p 80:80 karinakuroda/dotnetframeworkupwithdocker

OBS. You must ensure that you are running Docker with Windows containers, not Linux containers.
