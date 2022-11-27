
## Queue
Queues are a Data structure that excels in keeping a lot of bits of information in the order that they were added to the queue. When an item is added to a queue it is added to the end or back of the queue. When an item is removed from the queue it is removed from the start or front of the queue.
## Adding to the queue
To add data to the queue you use the function ".Enqueue()" with the data you want to add in the parenthesis. That value will be added to the back of the queue
## Removing from the queue
When removing data from the queue you use the ".Dequeue()" function. This function doesn't need any value in the parenthesis because it doesn't matter what value is in the first spot it will remove it because it is in the first spot. There is another function called  ".clear()" that will remove all the items in the queue that you use it on.
## Operation efficiency
All of the above functions have an efficiency of O(1). Adding to the queue is O(1) because it doesn't need to iterate through itself to find where to put the data you are trying to add because it keeps track of the count of items in the queue and adds it to the end. Dequeue and clear are also O(1) because they don't look for any certain data they just remove the data at the beginning for dequeue or remove all the data for clear.
## Runescape example
I play a game called RuneScape that has an endless series of tasks that you can complete. One set of these tasks are the quests which are the story portion of the game. To complete some quests there are a large number of requirements that you must do first. These requirements include; training skills or other quests that have their own requirements that you must complete first. A queue can be set up with the steps needed to complete a quest with possibly hundreds of prerequisites in the order that you need to complete them and removed once they are completed. That would organize your path you need to take nicely to completing an endgame quest with many requirements.
## Problem

