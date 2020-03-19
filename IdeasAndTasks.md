# ugs200h-complex-systems

## Ideas:

- Changing personality/strategy

- Shuffling position

- Creating a timeout period for some agents when they cannot interact(ie disease, travel attitude etc.)

- Perhaps consider a probabilistic way of deciding interactions (ie as of now agents are binary in whether they cooperate with others
 of same or other color that is set at beginning)

- Running multiple cells as different "teams"

## To Do List:
Meeting 02/23 (Ben, Gian, Hanshi, Ashok)
- [x] Fix wealth transaction
- [x] Fix color assignmnent
- [ ] Find data to analyze
- [x] Mutating personality
- [ ] Remove unnecessary code

Meeting 02/28 (Ben, Gian, Ashok, Prof.Nair)
- [x] Identify the interaction mechanism (understand the Von Neumann interaction order) (Ben)
- [x] Bring back the score to base 100 after every tick (normalizing) (HanshiZ)
- [ ] Probability of co-operating behavior will not be random (Red may not be willing to interact with red as much as blue would like to interact with blue). Rethink the co-operating behavior generation at spawn (Gian)
- [x] Recode the colors to White, Green, Yellow and Red (Hanshi)
- [x] Split exchange rate as two values (Cost of giving and Gain of receiving). Make them slider variables (Ben)
- [ ] Capturing the color and wealth of neighbors of each turtle (Add accounting variables for color and wealth of each neighbor) (Ashok)
- [ ] Plan the variables to be collected in Behavior Space (current wealth, new wealth, current color, new color, exchange rate, mutuation rate). What are the x and y variables?
- [ ] Tracking grid level and turtle level wealth change in every tick (Gian)
- [x] (Future) Add mutation rate as a variable
- [ ] (Future) Add personality change options based on triggers (e.g. 5 continous ticks as red will force a non-cooperating person to co-operate with others)
- [ ] (Future) Segregating the interactions to limit to teams

Meeting 03/01 (Ben, Gian, Hanshi, Ashok)
- [ ] The transaction is currently based on one-way interaction. Make it a two-way interaction (Ashok)
- [ ] Policy variables - Capability of the teacher to shuffle students, Control over limiting interactions, Changing group sizes.

Meeting 03/05 (Ben, Gian, Hanshi, Ashok)
- [ ] Dropout rate (Ben)
- [ ] Leave of absence (Hanshi)
- [ ] Randomizing the interaction pattern (Hanshi)
- [ ] Cleaning the code (Gian)
- [ ] Behavior Space (Ashok)
- [ ] Study the link function to find its capabilities (Gian)

Meeting 03/08 (Ben, Gian, Hanshi, Ashok)
- [ ] Fixing the 'to interact' section (Hanshi)
- [ ] Exploring the link function to set up teams (Gian & Ben)
- [ ] Developing a funtion to generate lists to collect data in behavior space (Ashok)


Meeting 03/11 (Ben, Gian, Hanshi, Ashok, Dr.Nair)
- [ ] Coronavirus update - UURAF suspended (Plan to continue with model building)       

Meeting 03/18 (Ben, Gian, Hanshi, Ashok, Dr.Nair)
- [ ] Self-study variable for turtles that are not interacting in a tick (Hanshi)
- [ ] Adding link function (Start a separate model) (Ben & Gian)
- [ ] Change the names from Circle, Square etc. to altruist, egoist etc. (Ben)
- [ ] Generating excel files based on Behavior Space experiments (Ashok)
