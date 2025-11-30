The beginning lines 4-9 show constants that I placed as they should not be changed. This allows the rules to stay present throughout the program.

Lines 11-16 are the amount of symbols that are in the program for example there are only 2 letter A's within the pool of all the other letters which makes it the hardest to get. This leads to lines 18-23 which are the payout amounts for the combination of 3 of the same letters within that row.

Now in order for this program to start running lines 72 - 83 is where the user is asked a prompt to deposit money, after the user inputs the amount they want to deposit it then collects that data and saves it as it's initial starting point.

Lines 85-96 is where the program collects the amount of lines the user wants to play with the minimum being 1 and max being 3. In order for this portion to run as well the lines 99-110 is where the program collects the amount of money the user wants to bet for each individual line.

As we collect this data from the user inputs we then have to get the slot machine to run, for this we use the function def_get_slot_machine_spin() in lines 40-44 where it creates the amount of rows, columns, and finally symbols (letters).

The funcitoin in lines 60-67 is where the user finally is able to see the columns and displays the slot machine with the columns.

As we get towards the winnings the function in lines 25-38 is where it saves the amount the user wins within each column, line and bet mutiplier. It also will continue to save the amount they won with the balance they had before.

The program has to remember the user's balance as he spins the slot machine again so lines 113-122 saves the balance of the user and collects the amount the user inputs as a bet. 

Finally the program eventually has to end for the user and give them their amount in winnings, this is created with 136-145 where the main program prints out the amount the user has won as well as if they want to play again, if not the program will finally break out and give them their last balance.

