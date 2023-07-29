//this it insatll nginx image
/// from imageName     
FROM nginx COPY . /usr/share/nginx/html 

//to build image go to terminal 
// type : docker build -t giveNametoTheImage locationOfDockerFile
//in project folder the locationOfDockerFile will be . 


//to run the image build as docker contaier go to terminal in project folder where the docker Sitting file is
//type :  docker run -p 80:80 dockerImageName

//to run it in the background as service 
//type : docker run -p 80:80 -d dockerImageName

//to check the if you build the Image 
//type : docker image ls

//the dockerfile name must be all small also the image name

>>command 1
//docker container ls 
//check the container runing after runng in the background

//i can the contaier in any where
//thats why it called contaier
//i can take the contaier any where and run it
// no need to type the whole contaier id just the first 3 or 4 numbers

//to stop the contaier 
type : docker stop idOfContier
id get From  command 1 

to show all the docker contiers runing 
type : docker container ls -a

to delete the contaier 
type : docker container rm idOfContier/or the name  