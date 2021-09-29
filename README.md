# Gesture-controlled-voice-assistant
The Gesture Controlled Voice Assistant for deaf and elderly allow users to communicate more effectively with their computers and other people. To be specific, using this program, you can sign multiple words with gesture and copy the translated text with the click of a button. Additionally, users can video call each other and talk using gestures that get converted into Computer Speech.This live speech or audio is converted into text and displays the relevant Indian Sign Language images or GIFs.
# Features
✔Hand Gesture Training and Classification

✔Retrainable Image Classes

✔Translated Text can be Copied to Clipboard

✔Cards that display Information about each Gesture

✔Video Call functionality

✔Text to Speech of translated text

✔Minimal stress on memory

✔Cohesive Text Styling

 ✔Simple User Interface
 
✔Speech to gesture and text translation.

# To run the Application

1. Open the Downloads folder
2. Open index.html in Chrome.
NOTE: This will disable video call functionality.
3. From the terminal, run the main python file using the command python main.py.
4. The application interface appears on the screen.
5. Any speech recorded is then processed and respective outputs are shown accordingly.
6. To exit the application using speech, say goodbye.

# Algorithm

i.	open index.html in supported browsers.

ii.	Allow access for the usage of the microphone and camera.

iii.	Click on Proceed

iv.	Train the START and STOP gestures continuously for a minimum of 30 times.

v.	Add the title of the gesture which you want to train and then train the system with the gesture for a minimum of 30 times and Click on Translate.

vi.	Pose the gestures to the webcam. The system starts to predict the gestures and displays the mapped title in text and audio format.
            //The audio query is taken as input by the Alexa application when triggered by 
                   the “alexa” command and either perform an action or outputs the answer in  
                   audio form.

vii.	Getting the Alexa’s response.

⮚	Microphone listens for 1 second and calibrates the energy threshold for ambient noise levels.

⮚	Now the energy threshold is already set to a good value, and the speech can be caught reliably right away.

viii.	The Speech is recognized.

ix.	      The Speech to converted to Text 

⮚	Text converted to lowercase for further manipulation.

x.	Detected Text.

⮚	If Goodbye” then exit, Else if Detected Text in predefined Dictionary Words, display respective gifs of the phrase.

⮚	Else Count the Letters of the Word/Phrase.

❖	Display gestures of each alphabet in the phrase with some delay of Actions.

⮚	All the steps are repeated from Step vii till the audio ends. 

xi.	If Error in Step vii, that is if no Speech Detected then display the error message “Could not listen”.

xii.	 Continue the steps from Step vi until one wants to interact with the System.

