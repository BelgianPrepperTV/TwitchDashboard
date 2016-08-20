Functionallities of Twitch Dashboard Project:

Authentication:

Go to login page when clicking LOG IN
	- On clicking Sign in with Twitch --> Authenticate with TwitchTV
	- When authenticated successfully go to Dashboard
		- Authentication expires after a while
		- Sessions saved in database
		- When authenticated, "LOG IN" button on homepage changes to "DASHBOARD" and when going to [URL]/login.php redirect immediately to dashboard
		- If session expires, Button would change to log in again and they can go back to login.php

Main dashboard page:
	- Slick looking box with:
		- Uptime when streaming
		- Offline when not streaming
	- Change Title/Game option
	- Latest 15 Followers
	- Latest 15 subscribers
	- Latest 15 Donations 
		(When hovering over donator name, you see their donation msg and amount in a popup)
	
- Widgets Page
	- Create widgets (Followers, Subscribers, Donation and host)
		- A lot of customization, text size, color, font, family, position
			fade delay, animations, backgrounds, sound, length, ...
			(basically TwitchAlerts/Tnotifier functionallities + Support for MP4/Webm alerts
			- Custom CSS box, so people can still customize it.
			- URL to the page where their alerts would work (for use with CLR browser, ...)
