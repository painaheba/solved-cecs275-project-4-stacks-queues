Download Link: https://assignmentchef.com/product/solved-cecs275-project-4-stacks-queues
<br>
<span class="kksr-muted">Rate this product</span>

Project 4 –

Maze Solver – Create a program to solve a maze using a stack and a queue (also known as Depth First Search and Breadth First Search). Allow the user to choose from 4 (or more if you’d like to create your own) different mazes that are read in from a text file, and then allow them to choose how to solve the maze. At the top of the text file are two numbers, they are the height and width of the maze. The possible characters in the maze are: ‘*’ – represents a wall, ‘ ‘ – represents a movable space, ‘s’ – represents the starting location, ‘f’ – represents the finish.

Point Class – Create a class point that has an x and y location. Set the values through the constructor, create methods to get the values.

STL Stack and Queue – Use the STL stack and queue for the DFS and BFS. These should store type Point.

MazeSolver – Your main function should do the following:

<ol>

 <li>Allow the user to choose which level maze to use (1-4). Error check input.</li>

 <li>Dynamically allocate a 2D array of characters, the size of the array is read in fromthe first two values in the file.</li>

 <li>Read in the rest of the file and store it in the array.</li>

 <li>Allow the user to solve using DFS or BFS.</li>

 <li>Create an empty stack/queue.</li>

 <li>Search the array for the starting location.</li>

 <li>Push the starting point onto the stack/queue.</li>

 <li>Repeat the following Maze Solving Algorithm until the finish is found

  <ol>

   <li>Pop a point from the stack/queue</li>

   <li>Test to see if this point is the finish</li>

  </ol></li>

</ol>

i. If it is, end the loop ii. Otherwise:

<ol>

 <li>Mark the spot in the maze as evaluated (add a ‘.’ in the array). This will show the evaluated points when printed (note: this does not create a final path, this shows all points that were evaluated).</li>

 <li>Check the spots in the maze that are neighboring the current location (up, down, left, right). If they are not a wall, and haven’t already been evaluated, then add those points to the stack/queue to be other locations to evaluate.</li>

</ol>

<ol start="9">

 <li>Print out the maze.</li>

 <li>Repeat the program until the user quits.</li>

</ol>