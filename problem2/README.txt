Hi, 
I completed problem 2: Sales taxes using an online java compiler (http://www.compileonline.com/compile_java_online.php). You can copy and paste the code from the text document and place in the editor window. You can also copy and paste the assignment input information into the "input.txt" tab.

The program was designed using two classes- cart and item. The calculating tax functionality was implemented in the item class. In hindsight, this design solution was not the best because it violates the single responsibility rule.

This program rounds tax to the nearest 0.05. Thus if the tax is $0.56, it will be rounded down to $0.55. $0.43 would be rounded to $0.45. In the 3rd example input, "1 box of imported chocolates at 11.25", the tax is $0.56. The output suggests that the tax would round up to $0.60, however I round it down to $0.55. 

Assumptions
- input text format will always be the same, so no error handling has been implemented.
- input is always from input.txt.
- only 1 amount of each item is allowed per line. Can have multiple lines of the same item.
- goods that are tax exempt must be specified in the code. There is no implementation for identifying whether a good is book, food or medical product.
- price input should be to 2 decimal places