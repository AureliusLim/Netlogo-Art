#Red and Black Crosshair Art

##About the Respository
The project was inspired by Conway's Game of Life. It is a Cellular Automata model that simulates birth, living, and death of a cell.
Its rules are as follows:
  If a dead cell is surrounded by 3 live cells, it is given life which simulates birth
  If a live cell is surrounded by less than 2 live cells, it dies which simulates underpopulation
  If a live cell is surrounded by 2 or 3 cells, it continues to live on
  If a live cell is surrounded by more than 3 cells, it dies which simulates overpopulation
  
In the case of the program, modification had to be made in order to create a nice pattern. At the beginning, live cells are generated within 8px from the center of the screen.
Red cells signifies live cells while black and white cells signifies death. The rest of the patches are dark. This finishes the setup of the program. Once the Go function is called, it checks the whole plane of patches and their respective neighbours.
Their colors are updated depending on the conditions. For the project, an additional condition was added for the sake of aesthetics in which when a dead cell does not have enough live cells surrounding it and at the same time is surrounded by atleast 3 black cells using Von-Neummann neighborhood, its color is set to white to reduce the number of dark cells. 
##Contents of Repository
- [asyncArt.nlogo3d] - this is the actual Netlogo program to be ran
- [newasyncArt.PNG] - this is a screenshot of the generated art
##Setup
- Install Netlogo
- Open asyncArt.nlogo3d which will run Netlogo 3D
- Click Setup and then press first "go"
- Continuously pressing "go" or pressing the second "go" will constantly change the crosshair's pattern


