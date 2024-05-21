Spawns user in random location on board along with four coins (to add more, you can create more instances in the main function and add them to the coins list).
Change the board length by editing the BOARD_LEN variable, everything is built to scale so there is no need to worry about editing anythin else
The sorting algorithm used to sort the coins according to distance is bubble sort

Works by first making a multi dimensional array and adding the player and the coins in random locations.
The coins are then sorted in accordance to their distance from the player.
The "move_p" function checks where the coins are and moves the player to the coin.
After the player reaches the designated coin from the list, the coin is removed from the list and the list is then reorganized according to the new distances between the player and the remaining coins.
Code runs until all coins are collected.


Finished on 2024-5-21
