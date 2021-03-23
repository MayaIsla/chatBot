# chatBot

Hello! Welcome to my Discord chatBot. This chatbot allows you to communicate what kind of games you like to play. And recommends what game to play based on the genre you give it. 

This bot can run on both Discord client or just on terminal if you don't want to set Discord up. 

On the Python main file, there will be a comment with "#chat(). Simply uncomment the statment. And comment out anything Discord related below it. If you wish to use the discord client, please run the python file while using the bot. Otherwise, the bot will not talk. :(

chatBot creates a knowledge base and picks the best possible game based on the database in the JSON file that is embedded on the library. Using tools such as Tensorflow, TFlearn, Numpy Sci-Kit, and more packages to create training. Probabilistic models such as softmax and regression. 

![Knowledge Base](https://user-images.githubusercontent.com/43270477/112089665-57ffef00-8b4f-11eb-99cc-757bfbf17952.png)

## System Description

The software prompts you to give descriptions of genre that the user would like to play. Genres such as FPS, Rhythm and simulation will work. However, the only implemented descriptions are going to be the most popular game genres. The database is a work in progress.

Once you have entered the genres. It will prompt you to ask "What game should I play?" Based on softMax and epoch techniques for giving the highest probablistic value of the most recommended game in the slot to begin with. A game will be presented for you to play. 

![TrainingData](https://user-images.githubusercontent.com/43270477/112183808-d72b0c80-8bbb-11eb-8003-f165dab81d3f.png)

The chatbot can have very limited conversation such as "How is your day?" or giving it a simple "Hello" or "Goodbye." One of the weaknesses are it's limited conversation. Again, this is a work in progress. 

Another issue with the Discord API, is that there is no real way to quit until the runtime python system is turned off. This is not an issue with terminal however, as "QUIT" and "EXIT" are options. Discord API will only run while Python runtime is turned on and compiling. 

![bot](https://user-images.githubusercontent.com/43270477/112089686-63ebb100-8b4f-11eb-8d16-7ed25db40b60.png)

## Contributions 

Thank you so much for taking the time for reading this. Any tips and pull requests are welcome! 
