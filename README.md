# How to start a project
## Connection JavaFX Windows SDK
---
1.Download JavaFX Windows SDK(javafx-sdk-17.0.2)
![alt text](1/webp "Описание будет тут")​

2.In IDEA go to menu File -> Project Structure

3.Select the Libraries tab and click +

Specify the path to the unpacked javafx-sdk folder and select the lib folder

Then click OK and in the new window add JavaFX to the module (I have Games)

Now a new library should appear, click Apply -> OK.

---
## Create Edit Configurations for the project
---
1.Menu Run-> Edit Configuration and write the command in the VM options field

2.Need to add Application. To do this, click + -> Application

3.
    Select Games module
    
    Write the path to the main class (in this case, SnakeGame)
    
    Add VM options field
    
---
