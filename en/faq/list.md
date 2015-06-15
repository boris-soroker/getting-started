 - [**What does it mean when we say two chat rooms are connected?**](/getting-started/en/faq/list#connected-rooms)
 - [**What is Sameroom used for?**](/getting-started/en/faq/list#sameroom-purpose)
 - [**What is a Portal?**](/getting-started/en/faq/list#portal-definition)
 - [**What is a Tube?**](/getting-started/en/faq/list#tube-definition)
 
---
### <a href="#connected-rooms" name="connected-rooms">**What does it mean when we say two chat rooms are connected?**</a>
 
Lat's say we have a couple of rooms, **A** and **B**, from some chat platforms. For example, room **A** can be from a _Slack_ team (in that case, _Slack_ calls it the _channel_ **A**), and room **B** can be from a _HipChat_ team.

Often, it is very useful to be able to see in room **A** all messages posted in room **B**, and vice virsa, to see in room **B** all messages posted in room **A**.

Our product, [Sameroom](https://sameroom.io), does exactly that, relaying messages between rooms, and we will say that **A** and **B** are _connected_ by Sameroom. 

---
### <a href="#sameroom-purpose" name="sameroom-purpose">**What is Sameroom used for?**</a>
 
If you want to [connect](/getting-started/en/faq/list#connected-rooms) rooms from different chat platforms (for example, from _Fleep_ and _Campfire_ teams), [Sameroom](https://sameroom.io) can help. 

We will use names **A** and **B** for rooms you would like to connect.

There are two basic scenarios:

#### ![step-1.png](https://in.kato.im/b8be284b81c9467fed3170d274c28de6789dd2fae1957895cd34bc20a2676d25/step-1.png) &ensp; **You create a Tube**
 
In that scenario, you have access to both rooms you would like to connect, **A** and **B**. In our example, it means you have access to a conversation from a _Fleep_ team and a room from a _Campfire_ team.  

So, to connect rooms **A** and **B**, you just create in Sameroom a Tube between **A** and **B** [[see how]](/getting-started/en/faq/list#how-to-create-a-tube). After that, **A** and **B** are connected when the Tube is active.

#### ![step-2.png](https://in.kato.im/99977b264e016814f4af35ac12a7fe42f1138758cd4b9285fa8c34e628a264fd/step-2.png) &ensp; **You create a Portal and your counterpart uses it to create a Tube**
 
In that scenario, you have access only to one of the rooms you would like to connect (say, room **A**), and you know somebody (your _counterpart_) who has access to the second room (room **B**).

First, you create in Sameroom a Portal for the room **A** [[see how]](/getting-started/en/faq/list#how-to-use-a-portal).

Then, you send that Portal (which is just a URL) to your counterpart.

Finally, your counterpart creates in Sameroom a Tube between your Portal for the room **A** and the room **B** [[see how]](/getting-started/en/faq/list#how-to-create-a-tube). After that, **A** and **B** are connected when the Tube is active.

---
### <a href="#portal-definition" name="portal-definition">**What is a Portal?**</a>

A Sameroom user who has access to a chat room **A** from any supported chat platform can create in Sameroom a _Portal_ for that room **A** [[see how]](/getting-started/en/faq/list#portal-creation).

The created Portal is just a URL which can be sent (for example, by email) to a counterpart and then be used by that counterpart to create a Tube [[see how]](/getting-started/en/faq/list#tube-creation-from-portal).

We recommend to use [bot accounts](/getting-started/en/faq/list#bot-accounts) to create Portals.

---
### <a href="#tube-definition" name="tube-definition">**What is a Tube?**</a>

A Sameroom user creates a Tube to [connect](/getting-started/en/faq/list#connected-rooms) two chat rooms. 

If that user has access to both chat rooms, the Tube can be created directly [[how-to]](/getting-started/en/faq/list#tube-creation).

If that user has access to only one of the chat rooms, the Tube can be created by using a Portal [[how-to]](/getting-started/en/faq/list#tube-creation-from_portal).

We recommend to use [bot accounts](/getting-started/en/faq/list#bot-accounts) to create Tubes.
