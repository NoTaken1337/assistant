# assistant
Kuro version 1.0 voice assistant 
#Install 
Libraries
#speech_recognition
#fuzzywuzzy
#pyttsx3 

Microphone device index 
#Run the code in a third-party Python program

#import speech_recognition as sr
for index, name in enumerate(sr.Microphone.list_microphone_names()):
print("Microphone with name \"{1}\" found for 'Microphone(device_index={0})'".format(index, name))
