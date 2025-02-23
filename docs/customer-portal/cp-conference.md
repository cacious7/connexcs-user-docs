# Conference
Use the **Conference** feature (also known as a Conference Call or Bridge) to allow multiple callers to communicate with each other over a voice call. Once created, Callers join the call and are presided over by a Moderator

In this section, view all configured **Conference** groups:

+ **Name**: The name of the Conference
+ **Extension**: The dial-in numbers to callers to reach the Conference
+ **Active Participants**: All callers who have joined the Conference

## Edit Existing Conference
Click on the existing Conference name to edit the following fields:

*Field details:*

* **Name**: Conference room identifier.
* **Extension**: The dial-in number for callers to reach the room.
* **PIN** and **Moderator PIN**: Set these for additional security, they will be required to enter the room. 
* **Quality**: Set the amount of bandwidth available per caller:
    
    :material-menu-right: `Narrow Band`- 8 KHz (G711)
    
    :material-menu-right: `Wide Band1`- 16 KHZ
    
    :material-menu-right: `Ultra Wide Band`- 32 KHz
    
* **Max Members**: Limit the number of concurrent callers this conference must allow. Note: the preset of '0' Max Members allows an unlimited number of callers can join the conference. 

    ![alt text][conference]

Click **`Save`** to retain thew new settings. 

!!! tip "Conference calls for external callers"
    The standard Conference configuration above can only be used by internal callers. To allow external numbers to dial into the conference, setup a [**Customer DID**](/customer-portal/did/) and set the Destination to Internal, then select the available pre-configured conference. 

## Conference Call keypad options
Callers may use the keypad to control the audio on the conference call. 

|Key|Result|Description|
|-------|------|------|
|0|Mute|Mute your microphone. The other callers cannot hear you.|
|1|Vol talk -|Decrease the volume (sensitivity) of your microphone, by 1 unit.|
|2|Vol talk reset|Reset the volume (sensitivity) of your microphone to the default value.|
|3|Vol talk +|Increase the volume (sensitivity) of your microphone by 1 unit. The other callers hear you louder.|
|4|Vol listen +|Increase the volume of the speakers by 1 unit. You hear other callers louder.|
|5|Vol listen reset|Reset the volume of the speakers to the default value.|
|6|Vol listen -|Decrease the volume of the speakers by 1 unit.|
|7|Energy +|Increase the minimum energy threshold by 1 unit (background noise above this threshold is bridged into the conference and only when you speak).|
|8|Energy reset|Reset the minimum energy threshold to the default value.|
|9|Energy -|Decrease the minimum energy threshold by 1 unit.|
|\*|Deaf/mute|Mute your speakers and the microphone in one action.|
|#|Hang up|Disconnect the call and drop out of the conference.|
 
[conference]: /class5/img/conference.png "Add Conference"
