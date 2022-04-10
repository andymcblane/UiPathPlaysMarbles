# UiPathPlaysMarbles
Auto playing agent of Marbles on Stream

Basic program flow: 
- Find chrome instance matching '* - Twitch'
- Get chat, and wait until chat length >= 80 characters
- If regex "play" matches => 3 times in chat, type !play + enter key
- Wait 3 mins 
- Loop
