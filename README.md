# Snake-java

This is a game made by **Shaikh Ifaz Aiman (2019831031)** and **Sadia Islam Hridi (2019831081)** for *SWE 223 - Object Oriented Programming* course.
---

We have planned to develop the classic Snake Game using *Java Swing*. All of us have played this game in our childhood. 
Snake game is a computer action game, whose goal is to control a snake to move and collect food in a map. The foods are generated randomly within the game window. We developped a controller based on movement rating functions considering smoothness, space, and food. To find a set of good weight values, we apply an evolutionary algorithm. We examine several algorithm variants of different crossover and environmental selection operators. Experimental results show that our design method is able to generate smart controllers.

---

So to build this game we are programing 3 java classes that are:-
1. Snake Game    Main Class
2. GameFrame    For creating Java Swing Application window
3. GamePanel     This class is used for updating the length of the snake and randomly painting food on the screen and also moving the snake according to the keyboard inputs.
There is another sub class inside the  GamePanel class MyKeyAdapter Class that class is used to handle keyboard inputs.
