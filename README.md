# ST10438499_IMAD5112_Practicum
Weather App that calculates temperatures and displays them.

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
