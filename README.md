# SAMMIpelago
SAMMIpelago - An Archipelago Integration Extension for SAMMI
by Caigan and Erdenshire
version 0.9.0_beta
----------

--INSTALL--

Extract the zip file into its own folder.

In SAMMI main menu, click the Bridge button on the left side, and click Install Extension. Select the [SAMMIpelago.sef] file.

--USAGE--

This extension enables you to connect to a running Archipelago game server as a Tracker, and receive information such as item unlocks, messages, and more from the server.

You must have OBS running with the SAMMI Bridge to connect.

For full documentation on how to use this extension, please visit : https://docs.google.com/document/d/1TLdXEvEttrpAO0HhtxrtCHOQoRcQzSiuueUMl4NHldo/edit?usp=sharing

--CHANGELOG--

V0.9.0 
    
    Increased delay between messages from 75ms to 200ms
    Implemented batching of messages based on size of packets
        Both of these changes are to prevent overloading the OBS Websocket, as SAMMIpelago may not be the only thing utilizing it at any given time.
    Added toggles to the OBS SAMMI Bridge which control the sending of certain messages
        These messages are the various RAW messages SAMMIpelago can send, which contains items and locations in ID format instead of the translated format 
        (Example : "12345" instead of "Behind the Waterfall"). All of these are off by default, but can be enabled if a user wants to utilize the data themselves.

V0.8.0a
    
    Beta Release


--ATTRIBUTIONS AND LINKS--

Archipelago : https://archipelago.gg

SAMMI : https://sammi.solutions/

My Twitch : https://www.twitch.tv/caigan 

