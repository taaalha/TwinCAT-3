# Pizza Oven State Machine 
This was a fun TwinCAT 3 project I did to brush up my knowledge about the software. It uses state machine based control and depicts a simple Pizza making process.

The user can insert pizza's, which are then moved to the oven. After a certain amount of time, the pizza's are cooked and are moved to the output conveyer. The user can then press "package pizza" button to remove it from the output conveyer.

When a pizza is not removed from the output conveyer, the cooked pizza cannot get out of the oven. When that happens, a buzzer is lighted up to notify the user that the pizza is burning. It is also displayed on the status monitor.

The status displays the current situation of the pizza making process.

There can be a pizza inside the oven, and a pizza at the input tray. But if you try to put insert more pizza's, it won't happen. The input tray needs to be empty to receive a pizza.
