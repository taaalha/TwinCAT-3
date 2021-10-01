# Pizza Oven State Machine 
This was a fun TwinCAT 3 project I did to brush up my knowledge about the software. It uses state machine based control and depicts a simple Pizza making process.

The user can insert pizza's, which are then moved to the oven. After a certain amount of time, the pizza's are cooked and are moved to the output conveyer. The user can then press "package pizza" button to remove it from the output conveyer.

When a pizza is not removed from the output conveyer, the cooked pizza cannot get out of the oven. When that happens, a buzzer is lighted up to notify the user that the pizza is burning. It is also displayed on the status monitor.

The status displays the current situation of the pizza making process.

There can be a pizza inside the oven, and a pizza at the input tray. But if you try to put insert more pizza's, it won't happen. The input tray needs to be empty to receive a pizza.


# Some screenshots
![image](https://user-images.githubusercontent.com/87899535/135580071-e6d0463e-91bf-49fb-9958-436e235afd26.png)
![image](https://user-images.githubusercontent.com/87899535/135580261-cdbd23ca-f160-4d20-b560-a96b8c2424a3.png)
![image](https://user-images.githubusercontent.com/87899535/135580124-6d046c6b-5c06-4f2a-b220-33ae9997a6fc.png)
![image](https://user-images.githubusercontent.com/87899535/135580164-7efb03a9-5a47-4de3-ab74-2b6b3811324e.png)
