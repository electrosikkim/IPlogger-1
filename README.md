# IP Logger
Functioning IP Logger. Requires Repl.it db. 

# Features 

#### IP "Disabled"

If you return to the page, it'll replace the html with "Your IP Has The Disabled Status"

<img src="https://storage.googleapis.com/replit/images/1607992167546_5c04121255d174f0bfead5483cc627b3.png" height=200px>

#### Countdown 

If you do not click the button in 30 seconds, your IP will be automatically marked as Disabled.


#### 1/2 Chance Of Success 

If the odds go in your favor, your IP will be removed from the database. If they do not, you ip will remain the the database and be marked as "Disabled".

#### Disconnection Punishment 

If you disconnected and haven't "rolled" yet, your IP will remain in the database and be marked as Disabled.

# Setup
It's ready to use. If you would like to store ips in the ips.txt file, uncomment
```javascript
fs.appendFileSync('ips.txt', ip + "\n");
```
on line 25 in index.js.
# Stuff To Note:
I don't care how you use this.

Contact Me at paradoxdotexe@protonmail.com for any concerns.

This is part of an upcoming project that functions similarly but does not log ips.

This is partly satire.

If you would like to test this, go to: [Here](https://IPlogger.pepelaugh.repl.co)

If you do go there, note that your IP will be stored in a database, but it will not be publicly available. Feel free to use a VPN.
