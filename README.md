# FreeTAKHub Forms SALUTE

![image](https://user-images.githubusercontent.com/60719165/139068106-becaad95-6d8c-466d-aba2-e90b5f862b7e.png)


this integration connects to FreeTAKServer 1.9 or better and post a SALUTE report to all the connected clients. 

## S: Size
In this section of the report, the size of the enemy or unknown force will be relayed. 

##  A: Activity
The activity section is used to give a detailed overview of the actions the enemy is taking. Such necessary information would be things such as developing fighting positions, patrolling, and direction of travel the enemy is taking.

## L: Location
This is simply the geographic location of the observed unit activity. FTS will solve the location from huma readible name into lat and long

## U: Unit ID
This is where the unit isID. If the enemy’s unit is unknown or cannot be identified, use easily discernible features such as color of their uniforms, design of patches if worn by personnel.

## T: Time
This is where the time the enemy activity was observed. 

##  E: Equipment
This final portion of the report is meant to be quite detailed and is identifying the equipment associated with the enemy and their respective activity. Take note, there is a difference between detailed and long-winded. 



The integration works using the ManageKML/postKML [API](https://freetakteam.github.io/FreeTAKServer-User-Docs/API/REST_APIDoc). 

The result appears on the map as a pin with attached metadata:
![image](https://user-images.githubusercontent.com/60719165/125200108-d5a35400-e23f-11eb-934e-fc04210820c4.png)

