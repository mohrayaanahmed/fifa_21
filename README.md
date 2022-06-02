# fifa_21

# **FIFA 21**

### **Business Objective:** 
Procuring young talent in FIFA 21 by using Machine Learning to optimally scout players in the FIFA 21 Manager Mode.
The project delves in the intricate attributes of all FIFA players by identifying which attributes define a position and which of them are imperative that make a footballer shine above the rest. The project aims in tackling this and procuring the players that have the potential to be the very best and making sure they reach it. 

### **Project aims:**
The project aims in finding the young players with incredible potentials that can help the managers (users) win trophies, or build a franchise by cashing in (selling after making them a star). FIFA itself helps a lot in acquiring these young players with unlimited potential, but with the help of this project, the manager can know which attributes to look for when signing a young player in their academy, and extend his growth by training him on those particular attributes

### **Impact of the project:**
This project helps in buying the player at low cost, turning him into a star and selling before his apex submits. Although, the game itself has a ‘Potential Overall’ for every player, that is not always apparent as the range vary tremendously. A new dynamic potential for every player has been introduced in the new versions of the FIFA (from FIFA 20 onwards), and players having potential of over 90 may never reach it due to inability of focus from the manager.

### **Machine Learning used:**
To know the ranked order of attributes for a position, multiple linear regression is used to predict the overall of the players in one particular position. Having an accuracy rate better than any other models, it was ideal to choose attributes after being trained and tested by regression. 

### **Data Source:**
https://www.kaggle.com/datasets/stefanoleone992/fifa-21-complete-player-dataset


### **Order of ipynb files:**
Each position has its own ipynb file, and the positions (after grouping) are:

1. Goalkeeper
2. Centre-back
3. Full-back
4. Defensive Midfielder
5. Centre Midfielder
6. Central Attacking Midfielder
7. Winger/Wide Midfielder
8. Striker

There are total 9 ipynb files, one csv file, one png file and one README file. The csv file is the dataset used and the png file is the final output. Each of the positions defined above has their own ipynb file. The first ipynb file is 'fifa_introduction'. The rest are the positions ideally in an order defefined above.

### **Results and Conclusion:**
The final result is in a .png file, 'Attributes_for_all_positions'. It includes a table consisting of the most important attributes for each position. Therefore, when procuring a young talent on FIFA 21 without scouting, one can simply identify if a player will be potentially great or not by looking at their attribute stats. Furthermore, they can train them on specic attributes to ensure that the player reaches their dynamic potential. 
