a heroic browser, a thoughtful server, and the friends who help them talk to each other
=======================================================================================

A dramatization of what happens when you type "http://chadoh.com/cset160" into your browser. How does your browser communicate with some server across the internet? What are all the pieces in between?


The Cast (in order of appearance)
---------------------------------

1. Browser's **friend**: has good ideas for Browser
2. **Browser**: our hero; a talented artist who needs good instructions
3. **Computer** Browser's landlord
4. **Router** A lazy grouch! Computer's secretary
5. **Local Name Server**: claims to know some things
6. **Root Name Server**: knows where TLD Name Servers are
7. **TLD Name Server**: knows where Chadoh's Name Server is
8. **Chadoh's Name Server**: Knows things about Chadoh.com
9. **Server**: has art instructions for Browser


Without Further Ado: The Script!
--------------------------------

**FRIEND**: Browser! I have a project for you! You can get it from chadoh.com, and the instructions are called “/cset160”.

**BROWSER**: Thank you kindly, Friend! Let me look that up. Let’s see... I will need the number for www.chadoh.com since I haven't previously called there.  [_pause_] Hey, Computer! Do you know the number for “chadoh.com”?

**COMPUTER**: I have, like, almost no one in my address book. Hang on, our Local Name Server usually knows these things. [_pause_] Router? Can you pass a message to the Local Name Server at this number. [_COMPUTER hands ROUTER a letter_]

**ROUTER**: [_waking up, disgruntled_] Huh? What? Ok. What's the Local Name Server's number?

**COMPUTER**: It's still the same, 8.8.8.8

**ROUTER**: [_hands the message to LOCAL NAME SERVER_] here you go

**LOCAL NAME SERVER**: Someone wants to know where "chadoh.com" is. No one's asked before, so I don't know. Let me ask the ROOT NAME SERVER who I should talk to for ".COM" numbers. Hey ROUTER, send this message to the ROOT NAME SERVER.

**ROUTER**: [_waking back up again_] Huh? What's the number again?

**LOCAL NAME SERVER**: Well you can use any of the 13 different ones, but I like the one at 198.41.0.4

**ROUTER**: Hey Root Name Server. Message for you. [_hands the message to ROOT NAME SERVER_]

**ROOT NAME SERVER**: [_short and to the point_] COM TLD Name Server at 8.20.247.20

**ROUTER**: Hey Local, he says you should talk to the .COM Top Level Domain server.

**LOCAL NAME SERVER**: Thanks. [_writes a new message and hands it to ROUTER_] Can you ask the TLD Name Server for the number to Chadoh's Name Server.

**ROUTER**: [_takes message and drops it on the floor_] Oops, sorry. What did you say?

**LOCAL NAME SERVER**: [_writes the message again and hands it to the ROUTER_] Can you ask the TLD Name Server for the number to Chadoh's Name Server.

**ROUTER**: [_thinks about dropping it again, but hands it to the TLD Name Server instead_]

**TLD NAME SERVER**: Oh man, someone's asking about Chadoh. I've got his Name Server number right here. It's 104.24.106.163 [_hands a message to ROUTER_]

**ROUTER**: Ok, here you go Local 

**LOCAL NAME SERVER**: Thanks Router. Now I'll ask Chadoh's Name Server what the number for his webserver at "chadoh.com" is since I know his Name Server's number. [_hands another message to the ROUTER_]

**ROUTER**: [_hands the message to Chadoh's Name Server_]

**CHADOH's NAME SERVER**: I totally know the number for my webserver. I'm authorized to tell you the numbers for everything at "chadoh.com". The one you want is 75.101.145.87

**ROUTER**: [_hands the message back to Local Name Server_]

**LOCAL NAME SERVER**: Awesome. I'll hold on to that for a while. [_write down the number_]. Hey Router, can you send this message back to Computer.

**ROUTER**: [_hands the message back to COMPUTER_] Sorry this took so long.  Your local friend had to ask around.

**COMPUTER**: Thanks. Hey Browser. Here's that number you were looking for.

**BROWSER**: Awesome. I'll remember that for a while so I don't have to ask you again. Now can you send this message to number 75.101.145.87.

**COMPUTER**: [_takes message from Browser_] Sure thing. Hey Router, give this to 75.101.145.87.

**ROUTER**: [_now sleepy again_] What? Where? [_rubs eyes while taking the message_] Ok, I'll pass that on.

**SERVER**: Hello. [_reads message_] So someone wants to know what is at "/cset160" [_looks through a file, pulls out a document, makes a copy of it, puts copy in an envelope_] It’s on it’s way! [_throws the envelope to Router_] Have a lovely day!

**ROUTER**: Hm. You too. [_yawns_] Computer, here go. [_hands envelope to Computer_]

**COMPUTER**: [_to Browser_] Here you go, browser!

**BROWSER**: Finally. Ok Friend. Here's the info you asked me about.
