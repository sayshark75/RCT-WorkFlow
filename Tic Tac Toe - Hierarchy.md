TocTacToe Hierarchy 
![image](https://user-images.githubusercontent.com/112304655/203317136-6b182d65-1743-4866-8767-6f142d2ded30.png)


```
=> We Create a Component called Button,
=> we need a toggler so we use useState hook for that, so it toggle x and o
=> button containes events which handled by toggler
=> According to toggler we change text on buttons.
=> we need to somehow check for patterns in an 9 sized array
=> we can use an array hook and a function to check
    Patterns like 
    		[0, 1, 2],
		[3, 4, 5],
		[6, 7, 8],
		[0, 3, 6],
		[1, 4, 7],
		[2, 5, 8],
		[0, 4, 8],
		[2, 4, 6],
=> These patterns must be X or O.
=> for that we must be using a function as handleWinner.
=> If any of the patterns True, we will show the winner as X or O on a Result Component
=> we disable all buttons
=> we Create a component for Reset the array hook
=> if user press reset, then we reset the button array with null.
```

