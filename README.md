# Sight for the Blind</br>
### The aim for this project is to provide automation for the blind.</br> 
Blind people don't want to feel any different from others, but they are constraint from doing certain things like writing, eating on their own, walking.</br>This things require sight so with the use of Machine Learning and voice automation in android, we would give sight to the blind.</br>
## Insipration</br>
While preparing for 2nd semester exams, on my way to the Library on the last week of December 2019, I meet a blind student who was himself making His way to the library,we walked and talked together, and I could only imagine how much strength and determination he puts in day after day to be a student like studying, going for classes, submitting assignment,... and doing what students do every day. <b>Believe me its stressful</b></br>
As the conversation progressed I could see He struggles, what ordinary what have been easily done by mewould take him time to get done.</br>
So after our brief conversation, I sat him down at the library desk and setup his laptop, earphone and charger,.. but before leaving I noticed that he used microsoft-word TextToSpeech to read (that means technology can be used to solve this problem)
And I was determined to use technology to help him and other visually diasabled persons(blind) see the world and the way for me to do this, is to use <b>Machine learning</b>.</br>
## Technology stacks
- Keras with Tensorflow 2.0 backend
- Google colab
- Android studio

## How it works
By clicking on the app screen, the app would speak out what it detects, either to read lables or detect item.</br>
The app will consist of two screens;
- Tell me </br>
For this section, the app will be able to read every-day items like product label, book name, food item name <b>...</b></br> 
This will be done by point the phone directly in front of what to read
- Detect traffic</br>
Just by my experince, they navigate everyday and crossing the road without know the traffic sign is not such a good idea</br>
This setion is to detect the trafiic sign and say what the model detect, so that He can cross safely.

## Featues
- On device Machine learning
- Privacy in users data

## Presently
- Optical character recognotion has been implemented for Tell me section. 
- Pre-trained TFLite model on 80 classes is presently used for testing the app
- Android in built TextToSpeech is in use to speak the text

## Next
- Improve the OCR
- Gather data and train the model
- Convert to TFLite
- Improve the speech reconition
- Proved Real-time description of the environment for easy automation
