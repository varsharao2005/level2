# level2
**_TASK 1_**


Got introduced to two new computer softwares for designing an electronic circuit.
Figured out how to use LTspice to to design an astable multivibrator using 555 timer. Having calculated the values of the resistors in level 1 task 13, I tried to directly use the values of resistors as 3k and 6k ohms and 2 capacitors of 0.01 micro farads each to get a duty cycle of 60 percent.
![59ce84b0-65f0-4475-9290-81bb691ab559](https://github.com/varsharao2005/level2/assets/148563974/d5956cce-7e83-4d18-998e-27925e174d18)
![c349e007-c91f-454b-8060-cde359945976](https://github.com/varsharao2005/level2/assets/148563974/e7f7c0a2-34a6-43ab-9181-1659150f0cd3)
Also learnt how to use KiCad to design a simple led blinking circuit(using a 7555 timer).
![474dd71c-1ddb-425d-a8d8-e15ee1623d76](https://github.com/varsharao2005/level2/assets/148563974/e6e1187c-b962-42f0-ab7f-989c5ff94f7f)


**_TASK 2 and TASK 3_**


So, the aim of the TWO task was to be able to control the speed and direction of the two motors, driven by the motor driver L293D. Having done tasks in level 0, I found this to be easier except there two motors instead of one and I faced few errors. So, after taking help from MARVEL coordinators I was able to finally able to make sure that the motor rotated. I learnt that the two pins of the EnA have to be shorted and similar thing to be done in casE of EnB. The the tasks had similar circuit assembly and only differed in the code that was uploaded through the ardiuno.
![5abc498f-8691-4ee6-ab6e-de35041bc02f](https://github.com/varsharao2005/level2/assets/148563974/cc2b4a3a-1a08-40a8-ae9d-be15d15914cf)
![09ba144f-1fc7-4326-a0fc-823878544bea](https://github.com/varsharao2005/level2/assets/148563974/714fcdd4-50ef-4922-8f98-b519e867c6a1)
![b64cdee2-cf0d-4f07-907f-5d532d5e76ae](https://github.com/varsharao2005/level2/assets/148563974/19edb470-d785-49ea-ac20-73faac4b2809)


**_TASK 4 and TASK 5_**


This task involved making of a vehicle model that could a) avoid obstacles b) can turn when there is an obstacle in front. 
I used HC-SR04 Ultrasonic Distance Sensor which works on the echo principle. I used arduino board along with l298n motor driver and 4 motors, attached to the chasis.
Again, even here the tasks differ by their code.
![49494d1b-7c10-4bee-a3f1-d6e5163be3bf](https://github.com/varsharao2005/level2/assets/148563974/ed078451-8b4f-4546-ab80-6c8ed54a9fcd)
![5f59df54-6608-42c2-92b5-212f9b2415d7](https://github.com/varsharao2005/level2/assets/148563974/efe1d31f-bd36-4ed3-bc7b-59b6c50e5bd5)
![12c4fe22-d598-416c-b1fe-1edda53f91a8](https://github.com/varsharao2005/level2/assets/148563974/e22b6a7c-9d90-473d-bb26-164873d2655f)


**_TASK 6_**


In this particular task, we had to measure the temperature using the lm35 temperature sensor and display it on an lcd screen and also set a threshold value such that when temperature goes beyond this value, an led turns on.
[Here's the link my tinkercad circuit.](https://www.tinkercad.com/things/iAWaCfF3Xd1-temp-measuring-thingy)


**_TASK 7_**


This task involves the use of DHT11 which is the temperature and humidity sensor. The sensor has a moisture holding substrate held between two electrodes along with a thermal resistor that senses the temperature. It can measure temperature within the range of 0-50 and humidity from 20-90%. As the temperature and relative humidity increase, the resistance decreases.
The readings were to be displayed on the lcd screen. For this, two very important libraries used in the Arduino IDE are LiquidCrystalDisplay and DHT11.h. 

![10c0ea4c-da23-4c01-a694-bb8eec1d6ae0](https://github.com/varsharao2005/level2/assets/148563974/06acb3bf-ca95-43cd-96aa-93b4ccaac8f6)
![15AR-05](https://github.com/varsharao2005/level2/assets/148563974/80684169-4ec9-407f-b31c-a4254310c96b)


**_TASK 8_**


Learnt about what a Brushless DC motor is. It has a permanent magnet. Here, the commutation or the change in the direction of current and concepts of electromagnetism are used. Unlike the usual DC motors, here there is no physical commutator, which is generally a segmented metallic ring attached to the rotor shaft and also, there are no brushes here, which has multiple advantages, like no wear and tear, no electrical noise produced when there's arcing and sparking. 
![a3144_hall_setup_wiring](https://github.com/varsharao2005/level2/assets/148563974/5929c413-c71b-4c89-91e1-cc20af2f9818)
![download](https://github.com/varsharao2005/level2/assets/148563974/da406929-29d4-4c73-800e-8990369add6a)
The principle of the Hall effect states that when a current-carrying conductor or a semiconductor is introduced to a perpendicular magnetic field, a voltage can be measured at the right angle to the current path. Speed calculation is done by calculating periods of the Hall Effect Sensor signal.


**_TASK 9_**


In this task, we learnt how to use MOSFET as switch and also how using Q=I*t how we can know about the Li ion battery.
To find the total energy contained in the cell, we would need to look at the electrical power expended in the test.
Good rule of thumb is that the power rating of the shunt resistor should be roughly four times the current.
![c3507887-61af-42d7-989e-ec542dfa0173](https://github.com/varsharao2005/level2/assets/148563974/b366c6bd-841a-4d7b-92fc-e2167292799f)
![0e8ae13e-2717-49a6-bd07-a12eb4631e56](https://github.com/varsharao2005/level2/assets/148563974/65097b7a-0315-4b97-8424-812957fb64ef)
![36827841-b330-4d20-8b00-67dafba0edbd](https://github.com/varsharao2005/level2/assets/148563974/b1364a62-2408-49a9-9b36-b4bf4fc7c5ed)


**_TASK 10_**


The task was to recharge a Li ion battery using solar panel. A boost coverter could be used to step up the output voltage.
![DIY-Solar-Battery-Charger-for-18650-Connection-Diagram](https://github.com/varsharao2005/level2/assets/148563974/bbf1d6af-d66a-4c91-98e0-acd87aacf139)


**_TASK 11_**

This task included the usage of 555 timer and light dependent resistor to make an automatic headlight.
![This is my tinkercad circuit](https://www.tinkercad.com/things/entuZCIwFSR-fantastic-snicket)


**_TASK 12_**


This task was about making a solar panel using 4 photdiodes and check if it works using a multimeter.
![This is my tinkercad circuit](https://www.tinkercad.com/things/61dBguI9rXT-solar-panel-from-diodes?sharecode=o7CMmCKpHAENVKDQUaHKTqETCYXLQYKpW0riAb-mzs4)


**_TASK 13_**


This involves making of a system, in which the solar panel follows the sun to maximize the energy absorbed by the solar panel, using LDR and servo motor, controlling movement along two axes.
![6dab8a93-4f37-4622-bb44-30b5a0decd33](https://github.com/varsharao2005/level2/assets/148563974/41f5ef24-bae2-40f0-b2de-25c3ab1d62f7)

