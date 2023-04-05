# SetGen
A musician's Set Generator utility that allows for backend-based setlists to be managed by one individual and the core program to be used to bring up date-based 
setlists for any gig, using their mobile device.
I am writing this in HTML/CSS/JavaScript with a touch of PHP/MySQL.  I am new to JS and don't know it very well.  This program is personal to me because I am a 
professional keyboardist that uses multiple keyboards in each gig I play.  I needed a way to merge a paper setlist I am given by the bassist for each gig, with the
keyboard information specific to each song.  I create "Live Sets" on my Roland Fantom-G workstation that encompass all of the sounds, effects, mixing, etc. for sounds
I play both on this keyboard, and a MIDI board connected as well.  I also play a third keyboard, a Roland Juno Di, which has sounds and user-created programs 
containing multiple sounds mapped across the keyboard that I use for each song.  

I am currently using an Excel spreadsheet of my own design to enter each song in each setlist and include the keyboard-based info for each song, so that I can see at
a glance during the gig, where I am, and which buttons I have to push to be ready to go for the next song.  Any gigging, dance-band musician will tell you, that once
the set begins, it can be non-stop, going from one song to the next, in an awful hurry, in order to do one simple thing:  keep people dancing.  Especially the women.
If the women are dancing, the men like to watch, and they need something to drink while they are watching.  This drives liquor sales, and then the club owner is happy, 
and will continue to invite your band back to the same club.  So anything I can do to streamline my processing of meeting these goals for my band is a good thing for 
everyone.

This program is a pathway to help me do just that.  It will also be something that will be useful to any member of the band, whether they are a vocalist, a guitarist,
bassist, drummer, or even a horn player.  By using PHP/MySQL, I can instantiate user-specific logins to the system, which will result in providing customized content for that musician, 
based on a profile they create when they first use the program.  For example, a new user who chooses "vocalist" from a drop-down list in the user creation process, 
will get a link to the lyrics for each song and perhaps an audio clip which plays their starting note.  A bassist, guitarist, keyboardist, and a drummer might get a rhythm chart link that would open up on top of the program and could be escaped to clear it.  A horn player would get their chart, transposed into their specific horns' key, on their screen at the touch of a link.  

Here is the basic user screen:
![image](https://user-images.githubusercontent.com/124417348/230197328-70df7922-6242-4baf-8bd9-e45a6393213e.png)
As you can see, it's pretty simple.  Choose the mode you wish to operate the program in (User or Admin), and the screen will change (unhide) based on your choice and your logon information (password, name, address, phone, musician-type, etc).  The Admin screen will change based on whether you are a System Admin or a User.  A User in Admin mode will be able to modify their own information but no one else's.  In User mode, the user can choose the date of the gig using a calendar drop-down widget, and that will load the set information.  When the user drops down the Set field, it will allow them to choose which of 4 sets and an Extras list they want to use.  I should also include a search feature that will go directly to a specific song, because, sometimes changes are made to a set on the fly.  Once the user chooses a set, the songs for that set, and their respective keys will populate below the header ![image](https://user-images.githubusercontent.com/124417348/230200010-ff24bdb1-4fcf-4faf-9724-0fe8bb534b10.png)
 in the order they are intended to be performed, along with any user specific information.  The header shown is specific to my keyboard setup, and could easily be modified programatically by the type of user set in the profile.
 
 User color control:  The user should have control over certain aspects of the screen, such as colors.  The colors available might be background and foreground colors and could be setup in such a way as to minimize light emissions on-stage.  No blazing white backgrounds, for example, that might shine off the face of the musician and be seen by the audience, will be permitted.  White text (among other colors) will be allowed, on a medium to dark colored background.

The Admin user has complete control over all aspects of the program, including all users, database management, creation of setlists, etc. The Admin screen has undergone several revisions already and I do not seem to have a suitable copy of something to use as a screenshot.  It will provide functions for administering the program in all manner of events.

Add-Song screen:  The basic screen for adding a song to the master songlist (Admin only) is below: ![image](https://user-images.githubusercontent.com/124417348/230205907-71682bcd-af79-457d-87ef-495efc380451.png)
Again, this screen only contains fields that I would use for my keyboard equipment.  A more advanced input screen, including all fields required for each user type would be necessary here to account for the various display screen requirements.

Lots of other screens will be developed over time.  This is a large project, but one I feel led to create for the musician community out there.  Should you desire to fork this program and work on it, I would be delighted to add your name, pen name, to the list of contributors to this venture, should I decide to use your code.  Thank you in advance.  
Dave Markivee
davemarkivee@gmail.com
