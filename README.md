# Friday-AI-Assistant-Using-Python
Created a small example of AI which will help me in some daily tasks.

What can this A.I. assistant do for you?
It can send emails for you.
It can play music for you.
It can do Wikipedia searches for you.
It is capable of opening websites like Google, Youtube, etc., in a web browser.
It is capable of opening your code editor or IDE with a single voice command.

Defining Speak Function
The and first and foremost thing for an A.I. assistant is that it should be able to speak. To make our F.R.I.D.A.Y. talk, we will make a function called speak(). This function will take audio as an argument, and then, it will pronounce it.

 

def speak(audio):
       pass      #For now, we will write the conditions later.
Now, the next thing we need is audio. We must supply audio so that we can pronounce it using the speak() function we made. We are going to install a module called pyttsx3.

 

What is pyttsx3?

A python library which will help us to convert text to speech. In short, it is a text-to-speech library.
It works offline, and it is compatible with Python 2 as well the Python 3.

What is sapi5?

Speech API developed by Microsoft.
Helps in synthesis and recognition of voice
 

What Is VoiceId?

Voice id helps us to select different voices.
voice[0].id = Male voice 
voice[1].id = Female voice
 

Writing Our speak() Function?
We made a function called speak() at the starting of this tutorial. Now, we will write our speak() function so that it can convert our text to speech.

