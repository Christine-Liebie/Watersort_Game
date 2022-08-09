# Development
# Watersort_Game
Watersort_Game is a university project I did in my second year.

# In the MyArrayList class:
In order to check if a game is completed one needs to check if all the colours in a bottle are the same. 
A generic version of this method should be added to the MyArrayList class. The method should return true if all the filled entries are identical. There is also a accessor for the instance variable.

# In the StackAsMyArrayList class:
I created a Peek method to return the value of the top element without removing it.
I also added 2 non-typical stack methods:  
			- public int getStackSize()  which calls the getSize() method of the MyArrayList class
			- public boolean checkStackUniform() which calls the checkUniform() method of the MyArrayList class
			
# In the test class called WaterSort:
It creates a bottle (StackAsArrayList). It also creates objects of the character glass.
Put ink in the bottles through pushing character objects onto the stack. There is an array of 5 bottles named bottles.
You can add ink to your bottles but have to take care not to spill ink.

# Mix-up ink:
Start with three sorted bottles. In the strategy the idea is to load three bottles with uniform colour and then move ink around for a number of moves until the bottles are mixed up.

There is rules such as that one that if there is enough space  in the target bottle and the source bottle has 2 adjacent similar colour spots, both will be poured.
