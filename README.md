# Lab 8 - Stoplight
## Part I - Tinkercad

- Visit https://www.tinkercad.com/
- Click Circuits > Create New Circuit
- Create a circuit to light up 3 light bulbs - *Remember each 3V coin battery is equivalent to a GPIO pin on your Raspberry Pi*
- Take a screenshot of your circuit

- [x] Take a screenshot of your circuit and upload it to this repository ![led_circuit](https://github.com/user-attachments/assets/b1e5b086-c16d-4ce3-b7ee-ade44d5d219c)

## Part II - Python3

- Redo part I with real components; however, for your power source, use GPIO pins on your Raspberry Pi. _Turn off your Pi when connecting cables to the GPIO ports._
- Create a Python script `led_stoplight.py`  to recreate the following pattern out with your LEDs - Green for 5 seconds, then Yellow for 1 second,  Red for 4 seconds, then it repeats. _Do not use the stoplight sensor, use three individual LEDs._  
- You will need to import the `GPIO` and `time` libraries for this assignment.
- Add comments to your Python script to explain how it works.
- Take a short video of your stoplight working and a clear top-down photo of your wiring

- [x] Upload `led_stoplight.py`, the video, and the photo to this repository then continue to Part II
- [ ]![led_stoplight](https://github.com/user-attachments/assets/cabeccf1-9b42-42f5-9514-78654bd7c0bc)
https://github.com/user-attachments/assets/c02668dd-2c95-4935-8f67-8becec0cd551



 

## Part III - RBG LED  

![Pasted image 20240918085928](https://github.com/user-attachments/assets/afc83c00-95dd-4bed-a120-0daec07b2c7f)

- In a new script`rgb_stoplight.py`, repeat the previous two parts, this time using one 4 prong RGB LED, instead of 3 separate lights. This light should follow the same pattern switching from green, to yellow, to red.
- Add comments to your Python script to explain how it works.
- Take a clear top-down photo of your wiring

- [x] Upload `rgb_stoplight.py` and your photo then continue to Part IV
- [ ] ![IMG_0429](https://github.com/user-attachments/assets/4df9d7dc-3785-4161-9a67-d1265535972f)

## Part IV - Starting with a Button

- In a new script `button_stoplight.py`, add a button or touch module to your project to start your RGB stoplight. When the button is pressed the light should light up in the green, yellow, red pattern.
- Take a short video of your button starting the stoplight and the pattern appearing correctly

- [x] Upload `button_stoplight.py`  and the video to this repository then continue to Part V - Wrap Up
- [ ]https://github.com/user-attachments/assets/5c46cc36-0e28-4645-9377-f24ce640d176

 
## Part V - Wrap Up

- Make sure all the deliverables above are  uploaded to the repository
- Answer the following questions:

1. What is a Python library and how do you include one in your script? - A Python library is pre-written code you can use to perform specific tasks without having to write the code from scratch. To include one in your script, use the import statement, like we used the import time library to have our stoplights function on a timer

2. What does it mean for elements of a circuits to be in series vs. in parallel? - Series: components are in a single path, so current flows through each one in turn. If one component breaks, the whole circuit stops working.
Parallel: components are in multiple paths, so current can flow through each one separately. If one element breaks, the others can still work.

3. Can you create a circuit of 3 light bulbs in series? Why or why not? - yes, you can but the bulbs will get progressively dimmer and may be harder to see.


## Rubric 

_Course Content_

- 6 points - All required items are present.    
- 5 points - Task was completed, but supplementary materials are weak or missing.
  - Code is complete, but poorly communicates necessary information
- 4 points - Task was attempted, but is missing major components.    
  - Missing comments, videos/photos, or reflection questions  
- 3 points - Did not attempt or student should reattempt.  
  - Inappropriate use of AI tools.
  
_Workforce Readiness_  
  
- 4 points - Exemplified  WFR standards  
  - Language is profess

https://github.com/user-attachments/assets/73593847-1bd5-4b65-ba4a-4e0c6bb5c64c

ional.  
  - Work is clear and easy to read.
  - Used deductive reasoning guide solution.
  - Reflection on own work was thoughtful and honest.  
- 3 points - Practiced WFR standards  
  - Language is readable but not professional.  
  - Work is understandable but not completely clear.  
  - Reflection on own work was weak.  
  - Citations were not complete.
  - Format is somewhat distracting from content
- 2 points - Developing WFR standards
  - Work is unprofessional. Significant spelling or grammar errors.
  - Format is actively distracting from content
  - Did not attempt or student should reattempt.
