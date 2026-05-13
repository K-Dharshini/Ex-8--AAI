<H3>Name: DHARSHINI K</H3>
<H3>Register No: 212223230047</H3>
<H3>Experiment: 8</H3>
<H3>Date: </H3>
<H1 ALIGN =CENTER>Implementation of Speech Recognition</H1>

## Aim:
To implement the conversion of live speech to text

## Algorithm:
<b>Step 1:</b> Import the speech_recognition library

<b>Step 2:</b> Initialize the Recognizer

<b>Step 3:</b> Create an instance of the Recognizer class, which will be used for recognizing speech

<b>Step 4:</b> Set the duration for audio capture

<b>Step 5:</b> Define a variable to specify the duration (in seconds) for which the program will capture audio from the microphone

<b>Step 6:</b> Display a message in the console to prompt the user to speak

<b>Step 7:</b> Capture audio from the default microphone

Step 9:</b> Use the default microphone as the audio source

<b>Step 10:</b> Record audio for the specified duration using the Recognizer instance

<b>Step 11:</b> Perform speech recognition with exceptional handling:<br>
•	Attempt to recognize speech from the captured audio using the Google Speech Recognition service<Br>
•	If successful, print the recognized text<Br>
•	Handle specific exceptions: If the recognition result is unknown or if there is an issue with the request to the Google Speech Recognition service, print corresponding error messages<Br>
•	A generic exception block captures any other unexpected errors<Br>

## Program:
```python

```

## Output:

## Result:
Thus, we have implemented the Python program that will transcribe the audio file in the file variable and print the transcribed text on the console, one line at a time
