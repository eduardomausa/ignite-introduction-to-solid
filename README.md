# Node.js Study

## Express
In this project, I've created a Node.js server using the Express framework which makes a lot easier to build the services endpoints mainly because of a function express.json() which returns a middleware that only parses json and only looks at requests where the Content-Type header matches the type option.

## SOLID
In this project, I've also study some introduction to SOLID principles aiming to maintain the code as clean as possible and respect the five principles. As it's a simple project, the single single responsibility principle was the most used one.

## Project Structure
I've created a model folder which contains a User class. A repositories folder which has an IUsersRepository interface with the methods avaiables and a folder called implementations with the respective UserRepository methods implementations. And a useCases folder alongside with a folder for each scenario containing an UseCase and a Controller file.
Besides that, I've also created a routes folder where I declare all the application routes calling its controller.handle().

## Swagger
In this project I've also managed to study the Swagger documentation which I really liked because it was easy to create and very helpful and intuitive to use.

![image](https://user-images.githubusercontent.com/68240977/227396150-26680a08-fdce-4c1e-a705-78ea02e33982.png)

## Jest
Finally, I also studied and applied unit tests for the whole application, making sure it's all working fine!
