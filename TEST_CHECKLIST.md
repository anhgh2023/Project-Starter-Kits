# Checklist for game testing (Mobile target)
##1. General:

###User Interface:
- Screen flow
- Check for animation, movement of character, graphics, Zoom In/Out.
- There should not be any clopping (cut background)
- Test whether one object overlaps with another
- verify if loading indicator is displayed wherever required
- Character should not move out of the screen/specified area
- Test for enable and disable pages/icons/button
- Check for screen title
- Check for message title, message description, lable (should be appropriate)
- Check scrolling
- Font displayed (color, size..)
- Check other objects

###Score
- Score calculation
- Verify leader boards General/ all time/ weekly/ local
- Check the score registration functionality
- Check the format(whether, comma is required in score etc ideally if customer is foreigner coma should be in millions not in thousands)
- Check for level competition syncs with the score 

###Time out:
- Check for time out
- Do the actions when time-out yet to happen

###Multitasking
- Switch b/w different apps and play game, check for sound, score, UI, time out…"

###Pause
- Check if game is paused when call received or multitasking or sleep mode

###Data save & load
- Turnoff and ON device, check if settings are saved
- Log out /On , check same
- User should not loose his game in above conditions

###User profile
- Put a all types of images in Player profile and check
- Put special character, numbers,space in username and check
- Password should be in masked

###Text & image limitation
- Check the profile images
- Max limit of description
- Enter empty string, special character and check

##2. Functionality
###Game logic
- Game logic & game area

###Level play 
- Play till last level

###Cheat codes from development team 
- Enter the cheat mode and check all the levels
- Check for the features that will be unlocked level-wise
- Check for bonus score
- Check the score hike when level gets increased

###User test
- Check for multi-tap action (example in a car race we hold accelerator and left/right turn button simultaneously)
- Menu options
- Different game modes/location

###Help & About Screen
- Should be in easily understandable format
- Free from spelling mistakes
- URL should be hyperlinked (depends)

###SNS
- FB/Twitter sharing & posting

###Music & sound
- Check for background music and sound effects
- If music player running and we start installing any game app, music player should pauses without prompting for the user permission.
Steps for checking this:
1. Play a music file.
2. Launch the application.
3. Verify that while the application loads, it does not pause, resume or stop the actively playing music.

##3. Texture & Image
###Format, ratio, size
- Display correct size and ratio
- Design is correct

###Quality
- Fit quality


##4. Deep Testing
###Performance
- Check the loading time of a game 
- Make sure that any action is not taking considerable time, game flow should be fast

###Memory leak
-	Check the game when device memory is low

###Network
- N/w messages if n/w is not present
- Check if what happens when n/w not present and user plays a move (whether score submitted for that move etc)

###App size
- User wont like if your game takes lot of device space, so keep one eye on game file size

###Device , OS
- Check in supported screen sizes and os versions (basicaly depend upon Client requirement)
- Check for platform independence, whether the game works as expected on respective platforms.

###Upgrade game 
- Game must upgrade itself while keeping the data(score, user profiles) of the user intact.

###Battery
- What if Battery goes down/switched of the cell while playing, Wheter the score wil get saved?