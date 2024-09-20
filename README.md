# Absurdle
This is one of the projects I worked on as part of the coursework for CSE 122 at the University of Washington. 

Here is how the game works --
Absurdle is a variant of Wordle developed by qntm:
  Wordle picks a single secret word at the beginning of the game, and then you have to guess it. Absurdle gives the impression of picking a   
  single secret word, but instead what it actually does is consider the entire list of all possible secret words which conform to your 
  guesses so far. Each time you guess, Absurdle prunes its internal list as little as possible, attempting to intentionally prolong the game 
  as much as possible.
