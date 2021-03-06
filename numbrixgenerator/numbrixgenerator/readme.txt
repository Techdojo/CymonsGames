Numbrix Solver and Generator
----------------------------
ver22Nov2008
by Joseph Larson for Cymon's Games based on the Numbrix puzzle created by Maryln Vos Savant


If you enjoy Maryln Vos Savant's Numbrix puzzles but aren't satisfied with a measly one a day then this program is for you. Generate unique numbrix puzzles on the fly for a moment�s distraction or generate a whole book of them to take with you. If you're stuck on a puzzle in the paper and can't wait for the solution to be printed the next day you can also solve puzzles with this.

If you've never played a Numbrix now's your chance to play this simple puzzle that is sure to make you feel like a genius.

What is a Numbrix? Numbrix is a new puzzle created by Maryln Vos Savant and run weekly in the Parade magazine. Numbrix are simple and satisfying and require no arithmetic skills beyond needing to count.

In a numbrix the numbers starting at 1 count upward making a winding path through the grid, touching every square until they entire grid is filled. So for a 9x9 numbrix the numbers go from 1 to 81. From a square you can go 1 step in only the coordinal directions; up, down, left, or right. Diagonals are not allowed. At the start you only see only some of the squares have numbers. It is your job to fill in the rest.

With this program you can either type in your options with the keyboard or click with the mouse on any screen.

At the main menu you are given 3 options:
o Play a random puzzle: With this option the computer will create a randomly generated numbrix for you to solve interactively. You will be timed so be as fast as you can. If you liked a particular puzzle you can get it by going to the directory where this program is run from and getting the last.txt file. Move it or rename it to prevent it from being overwritten the next time you play.
o Solve a Numbrix: With this option you can type in a numbrix that you find in the paper or one generated in a batch with option 3 and then either solve it yourself or the computer can solve it for you.
o Make a batch of puzzles: With this option you can generate a book full of numbrix puzzles at once. The initial settings will be the same for all, but keep in mind that a �random� type puzzle will be different with every one. Since time to generate varies and can take quite a while it may be a good idea to let the program run for a while. Files will be named by taking the base name you specify and adding a number after it. You can retrieve generated puzzles in the directory where this program is run.
o At the time of this writing this program can make puzzles that are exactly like the numbrix puzzles in print, but allows for some significant departures from the traditional formula:
o Traditional numbrix puzzles are either 8x8 or 9x9. This program allows the creation of puzzles sized from 5x5 to 12x12 (for puzzles play in the game) or 30x30 (for puzzles generated in the batch command) and allows rectangular dimensions.
o Numbrix layout types in print have only so far been the "traditional", donut, strawberry, and strawberry donut. This program adds an option for random layout. The random layout does maintain a quad symmetry for aesthetic purposes. (This is no longer true, tho these are the most common layout still.)
o Occasionally a generated puzzle will have more than one solution. In that case a square will be moved to give it a unique solution, and quad symmetry will also be maintained. This technically breaks the layout rules and make Numbrix�s that stick to their original layout somewhat rare, but usually doesn't look too bad.
o Of course puzzles generated by this program are different because they are not made by hand.
At the moment there is no functionality for determining the challenge level of a puzzle.

Technical note:

Occasionally generation of a puzzle will happen instantly, other times it may take considerably longer. The reason for this is that the path generator will occasionally get stuck. While technically it will eventually succeed if allowed to run this program tried to reduce generation time by timing the path generation and if it's taking too long stop it and start over. It's not the most robust solution, but generally speaking it works.

Numbrix Solver and Generator was written by Joe Larson.

For programming resources source code and a free game every week please visit:
http://WWW.CYMONSGAMES.COM
