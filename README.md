A python program that sends the bee movie script to someone on Instagram by Fred415

REQUIREMENTS:
Selenium
Python
Chrome

Installation:
1. Change the "secret.py" file with your Instagram details.
2. Run "beemovie.py" 

Problems you may run into:
- Chrome not working (session suspended)
  This happens because the webdriver used is older/newer than the chrome you're using,
  to fix this simply find the version of your chrome and download the selenium webdriver for it.

- Program stops after login.
  The problem here is the popups Instagram gives varies. Right now when i log in i get two popups,
  one prompting me to "save login info" and the other prompting me to "turn on notifications". 
  If you have only the "turn on notifications" popup then simply delete the "save login info" code in beemovie.py, vice versa.
  I have connotations in the python script so it won't be too hard to find.