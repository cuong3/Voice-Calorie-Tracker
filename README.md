# Voice-Calorie-Tracker

How to use
The main screen shows the help file by default. There are three main buttons: Speak, View Log, and Help.

Pressing Speak will trigger the speech recognizer. User can speak to quickly add multiple food entries. Each entry is connected by the keyword “and” and follow the format: food name [pause] food quantity [pause] food measurement. For example: “chicken breast 1 pound and milk 2 cups”.

After speaking, the app will send data to our backend server, which will process the user’s speech, detect the food name, food quantity, and food measurement. Then it will query FatSecret’s database for corresponding food to get the calorie information. Finally, it will return these information to the user as editable forms so user can edit them. User can then press “Check Again” button to update the calorie, or press “Save” to save the results.

Pressing View Log will show users the food she has recorded. 
