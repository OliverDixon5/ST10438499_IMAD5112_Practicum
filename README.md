# ST10438499_IMAD5112_Practicum
Weather App that calculates temperatures and displays them.
This Psedocode will plan the logic that my app will use.
Pseudocode
Start
 Declarations
 String weatherConditon
 String dateArray["Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday",]
 Num minTempArray[11,9,7,10,13,15,18]
 Num maxTempArray[24,21,19,22,27,28,30]
 Num averageWeekTemp = 0
 Num averagedayTemp = 0
 Num index = 0
 bool Raining ???
 

 While index < dateArray 
   averageDayTemp = minTempArray[index] + maxTempArray[index] / 2
   dateArray[index] = averageDayTemp
   If averageDayTemp >= 20 Then
     weatherCondition = Sunny
   Else
     weatherCondition = Cold
   EndIf
   averageWeekTemp = averageWeekTemp + averageDayTemp
   If Raining = True Then
     weatherCondition = Raining
   EndIf
   index = index + 1
 EndWhile
Stop

Main Activity 1 code 
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/7208c592-ceaf-4d00-9811-1db24b3205ea)


In the First Main Activity i Set up Code for two buttons the one button would exit you out the app and the second button would take you to the next screen which would showcase the main app.


Activity Main 1 UI
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/df8407f3-8224-43d8-83a7-74b936b12db4)


The First Main activity has its logo in the middle with my student number and name above that and at the bottom of the screen there are two two buttons.


Main Activity 2 code part 1
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/fba4ac23-125d-4f0d-911a-8e4d3d04a37a)


The Second Main activity creates arrays to store the weather data and then calculates the average temperature based on the min and max units that are stored in arrays this is done by taking the place of the element in the array and matching it up with another number in that array and assigning it to its corrispondant day. It then adds the numbers to a total amount and divides when out of the while loop.


Main Activity 2 code part 2
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/93fef90f-918d-4c53-b0b6-735d66d62c55)


There are three buttons on the screen one button exits the program one button clears the data in the fields allowing for the suer to enter new data values into the areasand the last button sends the user to a more detailed screen of weather conditions and tempreatures.


Activity Main 2 UI
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/92d64324-f8fe-4a15-9d71-92e6c8c95fc0)


The Second Activity main has more on the screen displaying the days on the left and thier average temperature on the right at the top is a heading and at the button there are three buttons the average tempretures can also be changed by the user by touch.


Main Activity 3 code part 1
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/ce376e27-af83-4b1c-8aaf-e22d8e0bbbb4)


This code goes throught three arrays and displays them in the text views that are found in the UI it goes throught three mini while loops that display and update the text views  at the end there is a for loop that checks the tempreture and updates the weather condition depending on the value.


Main Activity 3 code part 2

![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/6910b6ad-db3b-44a2-8474-227105c74c5c)


There is also a button that takes the user back to the second main activity so that they can see the main weather values.


Activity Main 3 UI

![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/d4c38beb-e2bc-4bf5-8e92-342c98b7d16a)


The Main activity has four coloums with the days of the week thier minimum and maximum temperatures for those days and an area where they display the conditions of the weather.











