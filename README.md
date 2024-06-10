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

Once the Pseudocode was complete i began creating a UI for the first screen of the weather app this would display, The name of the app and my student number below it is a weather themed logo and a weather themed background that will stay constant over the different screens. The user will be prompted with two buttons one button will navigate the user to the next screen which will display details about the weather and the other button will exit the app. They are labelled to help the user make clear and consise choices.
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/50d57a93-c5d9-4921-a19b-9a37a60855ee)
I created a .xml for strings so i could link them with the components in the first screen.
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/d011b805-b816-4c36-9597-7fc0eb068460)
I created a .xml for the colors used in the buttons.
![image](https://github.com/OliverDixon5/ST10438499_IMAD5112_Practicum/assets/164025499/479b4043-69a8-4a1b-8409-8ce42e95af12)

