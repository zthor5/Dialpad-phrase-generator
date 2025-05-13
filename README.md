# Dialpad Phrase Generator
A prompt for using Gemini to generate memorable phrases from phone numbers based on telephone keypad letters. 

![Simple Logo](./AI_image_logo.png)


## Prompt Used
Generate memorable phrases for the phone number [INSERT_PHONE_NUMBER]. Base the phrases on the letters corresponding to each digit on a standard telephone keypad. 
 Rules: 
- First, reason out each viable option. Run through multiple scenarios, then refine the best options.
    - Only use 'O' or 0 in each generation, do not mix the two.
    - You can have only a portion of the phone number be a word or phrase (Ex. 800-PLUMBER)
    - Only respond to the user with the best viable options that only use 10 letters/numbers.    
    - Respond with "No good options" if there are no distinct phrases.


## Code to run against all your contacts! (Not Finished)
The code under the [CoLab] folder is a simple Notebook to run Gemini in parallel against all of your contacts.
- Currently written to take in a .VCF Contact File.
- Not finished! Final version will include all the bells and whistles for user-friendliness. :)



