# openai-raspberrypi

## OpenAI + Raspberry Pi Setup Instructions 

### What would you need to assemble your bot 

Supplies 

* Raspberry Pi Starter Kit (with micro CD card)
* Speaker set  & Speaker bonnet
* Or any plug and play speaker
* Buttons
* Jumper wires 
* USB microphone 
* Breadboard

Setting up Raspberry Pi 

1) Set up your PI using instructions from the Raspberry PI Foundation website 
2) Connect the USB microphone to the raspberry PI via the USB port 
3) Connect speaker bonnet to the pins on the raspberry pi 
4) Connect the speakers to the audio ports on the bonnet 
5) Place button on breadboard 
6) Connect a wire to the top of the button and the GND (ground) pin in the raspberry pi 
7) Connect a wire to the button of the button and to the 23 pin in the raspberry pi 
Note: You can use another pin but you’ll need to change it in the code. Certain pins may interfere with the audio. 

Running the code 

1) Make sure you add an enivronmental variable. Follow instructions from OpenAI website 
2) Run to install `sh setup.sh` requirements to run the file 
3) To run the python file, go to the terminal in your editor and type in `python script.py`
5) To test, rress the button on the breadboard. You should see “recording” on the console. You’ll have 5 seconds to record your question. You should see “finish recording” on the console. You should hear a response from the raspberry pi within a few seconds after asking your question. If you don’t hear a response, press the button again. 
Note: You need to press the button every time you want to ask a question. Press any key to exit the program. 


 