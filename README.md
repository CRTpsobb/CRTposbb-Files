                          Schthack, and Kotrt present....
                       P P S O S     v 2 . 0     R E A D M E    
                            Written by MystikalIVVI


1. TERMS OF USE
2. SERVER HISTORY
3. THE SERVER SETUP
   1. SETUP
   2. STATS 
4. SERVER FUNCTIONS
   1. GM (Game masters)
   2. Hack Protection
   3. Game lvl
   4. The "Players" tab
   5. The "Games" tab
   6. Firewall/Ban
   7. Information board
   8. Mail
   9. Debug window
   10. GM commands
5. SHIPGATE.EXE
6. LOGS
7. SERVER COMMANDS
8. CREDITS/THANKYOU'S



1. TERMS OF USE 

 Note that this server is not authorized by SEGA and it's for private use only.

 This server is for the Phantasy Star online PC and DC version only and cant be used for XBOX and Gamecube.
 Any modification of this server are not allowed...

 To play; you must buy the original game from SEGA, Guild card are not needed since
 SEGA have shutdown their server for this version of Phantasy Star Online.

 Other versions of Phantasy Star Online are not supported because we do not want SEGA losing customers, causing legal action.
 Keep playing on official server with XBOX,GC and Phantasy Star Online blue burst on the PC!


2. SERVER HISTORY

 I really think that this game is one of the best online games, well 
 I know that we can play at other great online games i missed pso
 after SEGA closed the official server. 
 That is why I have started this project, hopefully 
 some weeks before they close the server I have made some logs of a connection to make a 
 server but the encryption has stopped me the first time... Some months after with the support of 
 Wildone, King Arthur this project was really born, the 17 Dec 2003 :) 
 --SCHTHACK (PPSOS DEVELOPER)


3.THE SERVER SETUP

1. SETUP

 PREQUISITIES:
 The directory structure of the server should be similar to this:

 "./(main dir)" folder files:

 advanced.dat
 cntry.dat
 gm.dat
 setting.dat
 ban.ini
 menu.ini

 friend/
 lang/
 save/

 "quest/" folder files:
 battle.ini
 chl.ini
 quest.ini

 quest/dc/
 quest/dcv1/
 quest/mnu/
 quest/pc/

 some files may be created later on

To successfully setup your server:

Goto the General tab (first page):

1. In the ship information box, name your ship, but leave out any country names such as: UK/(ship name) or CA/(ship name) or US/(ship name).
2. Select a country, such as the United States (US), this select adds the country name to your ship, so it would be 
   Countryname/shipname -- for example : US/MYSTIKAL.
3. In the next box Type in the ip of your ship, in the format XXX XXX XXX XXX ( 3 numbers per box limit). so box 1-for example would be 127, 
   box 2 would be 0, box 3 would be 0 and box 4 would be 1 (127.0.0.1).
   --WARNING!!!-- IF YOU HAVE A ROUTER YOU MIGHT WANT TO CONSIDER FORWARDING PORTS IN RANGE FROM 9100 TO 9700, AND USE
   YOUR INTERNET IP, NOT THE LAN IP IF HOSTING ON THE INTERNET!!.
   REFER TO YOUR ROUTER HANDBOOK ON INFORMATION ON FOWARDING PORTS.
4. The next box is The event box setting, this sets the event within games, not lobbies.
    Setting                    Description

    Normal                     The normal city
    
    Christmas                  This adds trees and changes the board in the city.

    21 Century                 This adds a sign in the city, along with changing the board.

    Valentine's                Adds Hearts to the city

    Easter                     Adds Easter Eggs to the city

    Halloween                  Adds Pumpkins to the city

    Sonic                      (ill leave that one as a suprise ;))

  The Fools day event checkbox will be a suprise to you too ;)

5. In the next box is the Block Port and Ship port of the server,
   (DEFAULT: Block Port:9125 ,Ship Port: 9601)
   !!-IT IS NOT NECCESARY TO CHANGE THIS OPTION, BUT IF YOU HAVE TO, PLEASE TAKE NOTE THAT IF
   YOUR PORTS ARE NOT FORWARDED, THE SERVER WILL NOT CONNECT EXTERNAL USERS.-!!
6. The "Register to" box registers you to a ship server(EXPLAINED IN: 5.shipgate.exe), default: gsproduc.ath.cx.
7. Click "SAVE SETTING".

 You have now setup the server. dont close this readme yet, you arent done!!



2. STATS

 This shows the statistical side of your server :).



4. SERVER FUNCTIONS


 The Option Tab (second page):



1. GM SECTION (Game masters)

 The game masters section (GM) is for adding "admins" for your server, who can kick and ban users, along with other things.
 The name list shows the guild card numbers of all the Game Masters you added.

 To add a Game Master:
1. Get the Characters Guild Card number, within the "Chat > Guildcard > My card" in phantasy star online

 1073741825
 1234567890
 7578686869
 8586576786

 You can delete the "put the guild card number here" string if you wish.



3. Set A password, for example: "MYSTIKAL".

 Your set for the gm part :).



2. Hack Protection
 This option allows the server to be protected against edited or "bad" packets:

Option                                       Description 

 Enable NOL protection                        Enables the server to block NOL packets (character edit).

 Enable FSOD protection                       Enables the server to protect against FSOD.

 Enable Wrap protection                       Prevents hackers teleporting players to other places.

 Enable Lobby reload                          Prevents the lobby being reloaded.

 Enable C-pipe protection                     Enables Crash pipe protection.

 Enable Big-bubble fix                        Enables the server to be protected against Big-bubble crashes.

 Enable Animation protection                  Prevents Animation crash.

 Enable Bank/Cheat Protection                 Prevents hackers making items in the bank.

 Enable auto kick after 5 hack                After 5 hack attempts, the hacker is kicked.



3. Game lvl

 Sets the level standards for all difficulties.



4. The "Players" tab

 This shows all the players on your server.
 Select the player, then take the course of action:

Button                     Description

 Mass Msg                   Sends the Player the messages that you type.

 Kick                       Kicks the player

 Ban Serial                 Bans the player's serial number 

 Ban IP                     Bans the players IP address
 
 Ban Player Name            Bans the players Pso name



5. The "Games" tab
 
 This option shows the games and their stats.



6. The "FireWall/Ban" tab

 This Bans a certain player from your server.

 To Ban a player:

 Input their player name or ip into the box, then click "Add".

 To Unban a player:

 Select the player then click "Remove".


7. Information board

 The Information board is for adding news, and of course..information to your server :P.

 To add information/news:

 1. Click new, and name your menu item.

 2. Type the text to show inthe right box, then press "update info"

 3. Click save.

 

8. Mail

 This is the mail center for all your bug reports, when the user sends a report, a mail icon will popup
 on the bottom right of the screen.

 Double-click on the mail item to view it, reply and delete messages.

9.Debug window

 This shows the bans, kicks, and action of the server and the admins within it.

 To clear, just click the clear button in teh bottom right of the window.

10. GM Commands

 When you are a gm on the server, and the person has added your guildcard number (see - 1. GM (game masters)):
 
 To login: /gm <password>

 To kick: /kick <username>

 To ban: /ban <username>

 To npc: /npc npc#(0-5) <username>

 To shrink: /shrink <username> (only seems to work while in quests?)

 To "BITCH": /bitch <username> (only use this in severe times!)

5. Shipgate.exe

 This executable file lets you have your own personal shipserver, after you have configured your server, and save
 saved the configuration, run the shipgate.

 This takes us back to 1.SETUP (part 6.), the register to box is where you input the ip or
 resolved name of the server, then it automatically adds your server to the shipgate.

6. Logs

gmlog.txt - is the log for gm actions.
mail.txt - is the log for mails.       
    
 
7. Server Commands

 /addfriend <user> - adds a friend and tells you when he/she are online.

 /delfriend <user>- deletes  the friend you added.

 /save <password>- makes a backup of your character.

 /restor <password> restores your character.

 /tell <num> <msg> - send a message to the player num in group.

 /say <msg> - send a message to all the group.

 /msg <playername> -sends a message to the player, note : type command then type the message
 separately.

 /log - see the current private chat log .

 /Private - block all personal chat from people that are not on your friend list.



8. Credits/Thankyou's



 KINGARTHURIVVI - For letting me on the first beta server :), and being a real mate and looking out for me!
 SCHTHACK - For your excellent server and your will to carry on making a fully-fledged server, and reviving pso for all of 
           us, thankyou!!
 WILDONEIVVI - For making my life easier on pso, and being a great friend on pso!!

                      And we cant forget to thank SEGA for their wonderful game :)

THIS README WAS WRITTEN FOR PPsoS v2.0 (21,july,2004 10:05 GMT)
THIS README IS PROPERTY OF SCHTHACK (schtserv.funurl.com), KOTRT, and MYSTIKALIVVI(http://digitalhaze.co.uk)

      Readme written by MYSTIKALIVVI (http://digitalhaze.co.uk)

