# What you think is going on with Docker vs the box that you installed it on (my pc)?
## Generally speaking, Docker is seperating the file system from my PC to the guest (container that was created). Additionally, it's seperating how much network, IO access, memory, as well as the interface for Docker to utilize for the application that it wants to run. During installation, I had to download Ubuntu (OS) but it ran through Docker. The only thing that my pc is doing is running the Kernal (Docker in this case) and providing the resources and it's unaware of the applications that Docker is running.

### The following are a few examples of when Docker was using the copy code and using my pc memory:
![Image of First Line of Docker Code](https://github.com/tui54142/CIS-4330/blob/main/Copy_P1.PNG)
![Image of Second Line of Docker Code](https://github.com/tui54142/CIS-4330/blob/main/Copy_P2.PNG)
As you can see from both images, while Docker is running the lines of code, my PC's memory is being use but the lines of code aren't directly affecting what's happening on my pc and rather my pc isn't aware that any lines of code is being run. Only Docker knows what lines are being executed as is shown in the following image.
![Image of Commands In Docker](https://github.com/tui54142/CIS-4330/blob/main/Last_Line.PNG)

## Some things I found playing with docker
So admittedly, I was very lost but I figured that through Ubuntu I can manipulate the way docker runs and I can see in real time what images I was creating as well as running through Ubuntu command. I tested a simple command that makes sure that docker is installed correctly which was $docker run hello-world. At first it wasn't working since the image wasn't created yet, but once it was created the following was displayed on the Ubuntu command.
I used the following link as a beginner's guide since I got lost pretty quickly but it get's you started and familiar with what codes to put into the kernel: https://docker-curriculum.com/
![Image of Commands Using Docker using Ubuntu](https://github.com/tui54142/CIS-4330/blob/main/docker_run_hello-world.PNG)
![Images in Docker](https://github.com/tui54142/CIS-4330/blob/main/images_docker.PNG)



