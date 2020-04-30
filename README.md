# Containerize-a-.NET-Core-app
Containerize a .NET Core app using docker

# build an image from docker file
	docker build -t imageName -f Dockerfile .

# create container
	docker create --name containerName imageName
  
