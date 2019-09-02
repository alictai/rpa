# Email Image Fetch
This repo contains a UiPath robot which fetches images sent from and to a user's Outlook inbox, and places the image onto their computer and clipboard. 

I spend a lot of my day emailing photos of whiteboards with meeting notes to myself, and it is a frustrating and repetitive process to get them cataloged and available to send over IM. This attended robot handles that for me by downloading images from my email to my laptop and putting the images onto my clipboard for easy pasting into communications.

## Robot Process
1. Log into Outlook (myemail@email.com is the identity used in this example)
2. Scan the last 10 emails to and from myemail@email.com.
3. Download any attachments to those mails to the specified local destination folder.
4. Place the most recent image on the clipboard. 

## Using this Robot
1. [Download UiPath Studio](https://www.uipath.com/developers/community-edition)
2. Clone this repository and open it in UiPath
3. Change the 'MyEmail' and 'DestinationFolder' to your Outlook email address and the path of the place you'd like to save images on your computer, respectively.
4. Run the robot.
