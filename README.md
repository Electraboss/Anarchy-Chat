# Anarchy Chat
Anarchy Chat is a GUI and webserver setup designed to create a group chat where anyone can create their own group chat which is open to the public and that anyone can say whatever they want completely anonymously and without registration. 

WARNING: This project is not easy and has a lot of steps, only attempt if you know at least a little bit about scratch or, have a bad time, your choice.

## Table of contents

* [Setup](#Setup)
* [Config And Editing](#Config-and-Editing)


### Setup

1. Download the Scratch file off of the GitHub
2. Click this link: https://sheeptester.github.io/scratch-gui/index.html?width=800&height=450
3. Go to File > Load from your computer
4. Upload the dowloaded scratch file
5. Skip to [Config And Editing](#Config-and-Editing) then come back once done
6. Open a CMD window
7. Type the following: "git clone https://github.com/SheepTester/primitive-cloud-server"
8. Type the following: "cd primitive-cloud-server"
9. Type the following: "npm start"
10. Open the "primitive-cloud-server" folder
11. Open the "Static" folder
12. Place the html file you created in the config stage inside
13. Delete the "index.html" file
14. Rename your file to "index.html"
15. Stop the server from the terminal by holding the CTRL and C keys at the same time
16. Type "npm start" once again
17. Your website should be up!

### Config-and-Editing

It is time to configurate your website!

#### Blacklisting Words

First, Decide if you want some words blacklisted!

If you do, then follow these steps.
1. Click on "Main GUI" along the bottom of the scratch website
2. Along the left side you should see something that says "Variables", click it
3. Drag the block that says "Set *something* to 0" into the Main GUI window
4. Click on the dropdown menu on the block you just made and select "WordCheck"
5. Change the "0" on the block to a "1"
6. Click the block
7. Now, scroll down in the variable section until the blocks become red
8. Drag the block that says "add thing to *something*" into the Main GUI window
9. Click on the dropdown menu on the block you just made and select "Blacklisted Words"
10. Replace the word "thing" on the block with the first word you want to blacklist
11. Click the block
12. Keep replacing the text and clicking the block until you have added all the words, you can check your list so far by ticking the box next to "Blacklisted words" in the variable menu (Make sure to untick the box at the end!!!)

Now the words you added cannot be sent in the chat!

#### Customising GUI

Do you want to customise the GUI?
No problem! However, unless you know how to use scratch very well, it is not advised as you could break something very easily and I'm not going to teach you here.

#### The MAIN Setup

This is required no matter what

1. Port forward your IP (Necessary if you want people not on your wifi to join)
    - Google "what is my ipv4 address"
    - Google "how to port forward *insert router name here*"
    - Here is the basic config for that
    - IP: *your IPV4* (Maybe private, maybe public, depends on your router. You can google how to get either.)
    - Port: "3000"
    - And select TCP
    - (I can't tell you exact instructions as it is different for every router)
  
2. Go to File > Save to your computer in the scratch window
3. Go to https://sheeptester.github.io/htmlifier/
4. Select "Upload project file"
5. Upload the file you downloaded
6. Fill out the rest of the stuff as you please
7. Under "Cloud Variable Options" select "Use a custom server, like this example:"
8. Enter ws://*your-public-ipv4*:3000/
9. Under "E羊icques (modded) options" Tick both boxes
10. In "Does this project use a custom size?" Ender the following Values:
     - Width: 800
     - Height: 450
11. Click "HTMLify"
12. Continue the [Setup](#Setup)






#### Finally I finished this readme. I'm going to go sleep.
