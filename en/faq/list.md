---

 - [**What does it mean when we say _Two chat rooms are connected_?**](/getting-started/en/faq/list#connected-rooms)
 - [**What is _Sameroom_ used for?**](/getting-started/en/faq/list#sameroom-purpose)
 - [**What is a _supported platform_?**](/getting-started/en/faq/list#supported-platform)
 - [**Do you have a list of supported platforms?**](/getting-started/en/faq/list#supported-platform)
 - [**What is a _Portal_?**](/getting-started/en/faq/list#portal-definition)
 - [**What is a _Tube_?**](/getting-started/en/faq/list#tube-definition)
 - [**How much?**](/getting-started/en/faq/list#how-much)
 - [**What does _Unlimited Tube_ mean?**](/getting-started/en/faq/list#unlimited-tube)
 - [**What is a _Rate-limited Tube_?**](/getting-started/en/faq/list#limited-tube)
 - [**What is a _Roomcoin_?**](/getting-started/en/faq/list#roomcoin-definition)
 - [**What is a _bot account_?**](/getting-started/en/faq/list#bot-account)
 - [**Do you have a step-by-step example of a Tube creation?**](/getting-started/en/faq/list#tube-creation)
 - [**How about Sameroom security?**](/getting-started/en/faq/list#security)
 - [**What to do if my Tube does not work?**](/getting-started/en/faq/list#troubleshooting)
 
---
### <a href="#connected-rooms" name="connected-rooms">**What does it mean when we say _Two chat rooms are connected_?**</a>
 
Lat's say we have a couple of rooms, **A** and **B**, from some chat platforms. For example, room **A** can be from a _Slack_ team (_Slack_ itself calls it "channel", but we still call it "room"), and room **B** can be from a _HipChat_ team.

Often, it is very useful to be able to see in the room **A** all messages posted in the room **B**, and vice virsa, to see in the room **B** all messages posted in the room **A**.

Our product, [Sameroom](https://sameroom.io), does exactly that, relaying messages between rooms, and we say that rooms **A** and **B** are _connected_ (by Sameroom). 

---
### <a href="#sameroom-purpose" name="sameroom-purpose">**What is _Sameroom_ used for?**</a>
 
If you want to [connect](/getting-started/en/faq/list#connected-rooms) different rooms (for example, one of them is from from a _Fleep_ team and another one is from a _Campfire_ team), [Sameroom](https://sameroom.io) can help. 

We will use names **A** and **B** for rooms you would like to connect.

There are two basic scenarios:

#### ![step-1.png](https://in.kato.im/b8be284b81c9467fed3170d274c28de6789dd2fae1957895cd34bc20a2676d25/step-1.png) &ensp; **You create a Tube**
 
In that scenario, you have access to both rooms, **A** and **B**, you would like to connect. In our example, it means you have access to a room (_Fleep_ itself calls it "conversation", but we still call it "room") from a _Fleep_ team and a room from a _Campfire_ team.  

To connect rooms **A** and **B**, you just create in Sameroom a Tube between **A** and **B** [[see how]](/getting-started/en/faq/list#tube-creation). After that, **A** and **B** are connected when the Tube is active.

#### ![step-2.png](https://in.kato.im/99977b264e016814f4af35ac12a7fe42f1138758cd4b9285fa8c34e628a264fd/step-2.png) &ensp; **You create a Portal and your counterpart uses it to create a Tube**
 
In that scenario, you have access only to one of the rooms you would like to connect (say, room **A**), and you know somebody (your _counterpart_) who has access to the second room (room **B**).

First, you create in Sameroom a Portal for the room **A** [[see how]](/getting-started/en/faq/list#how-to-use-a-portal).

Then, you send that Portal (which is just a URL) to your counterpart.

Finally, your counterpart creates in Sameroom a Tube between your Portal for the room **A** and the room **B** [[see how]](/getting-started/en/faq/list#how-to-create-a-tube). After that, **A** and **B** are connected when the Tube is active.

---
### <a href="#supported-platform" name="supported-platform">**What is a _supported platform_?**</a>

At this moment, Sameroom can [connect](/getting-started/en/faq/list#connected-rooms) rooms from the following so-called _supported platforms_:

 - [Campfire](https://launchpad.37signals.com/campfire/signin)
 - [Fleep](https://fleep.io)
 - [Flowdock](https://www.flowdock.com/login)
 - [Email](https://en.wikipedia.org/wiki/Email)
 - [Gitter](https://gitter.im)
 - [HipChat](https://www.hipchat.com/sign_in)
 - [IRC](http://webchat.freenode.net)
 - [Kato](https://kato.im)
 - [Skype](https://web.skype.com/en)
 - [Slack](https://slack.com)

That list of supported platforms is going to grow over time.

---
### <a href="#portal-definition" name="portal-definition">**What is a _Portal_?**</a>

A Sameroom user who has access to a chat room **A** from any supported chat platform can create in Sameroom a _Portal_ for that room **A** [[see how]](/getting-started/en/faq/list#portal-creation).

The created Portal is just a URL which can be sent (for example, by email) to a counterpart and then be used by that counterpart to create a Tube [[see how]](/getting-started/en/faq/list#tube-creation-from-portal).

For some platforms, we recommend to use [bot accounts](/getting-started/en/faq/list#bot-account) to create Portals.

---
### <a href="#tube-definition" name="tube-definition">**What is a _Tube_?**</a>

A Sameroom user creates a Tube to [connect](/getting-started/en/faq/list#connected-rooms) two chat rooms. 

If that user has access to both chat rooms, the Tube can be created directly [[see how]](/getting-started/en/faq/list#tube-creation).

If that user has access to only one of the chat rooms, the Tube can be created by using a Portal [[see how]](/getting-started/en/faq/list#tube-creation-from_portal).

For some platforms, we recommend to use [bot accounts](/getting-started/en/faq/list#bot-account) to create Tubes.

---
### <a href="#how-much" name="how-much">**How much?**</a>

Here is our [pricing page](https://sameroom.io/pricing).

Any Sameroom user can have a lot (no enforced maximum, actually) [Rate-limited Tubes](/getting-started/en/faq/list#limited-tube).

Note that we have [Roomcoins](/getting-started/en/faq/list#roomcoin-definition) which are financially helpful.

---
### <a href="#unlimited-tube" name="unlimited-tube">**What does _Unlimited Tube_ mean?**</a>

It would be better to call it a _Rate-unlimited Tube_ or something like that. It simply means that this Tube does not have the trial-imposed [restriction](/getting-started/en/faq/list#limited-tube) (maximum 30 messages per a calendar hour per a Rate-limited Tube).

Note that if you try to send a lot of messages in a rapid sequence (more than a couple of messages per a second, for example) some of your messages will be not relayed by Sameroom to the connected rooms. _Rate-unlimited_ does not mean that Sameroom knows how to defeat laws of physics.

---
### <a href="#limited-tube" name="limited-tube">**What is a _Rate-limited Tube_?**</a>

Sameroom has _Rate-limited Tubes_ to allow users to try our service without charging their credit cards. The trial limit allows to relay maximum 30 messages per a calendar hour. After reaching that limit in rooms, connected by a Rate-limited Tube, a warning message appears in those rooms: {picture}    

Note that for some users the trial limit is perfectly acceplable, so those users do not need to upgrade Sameroom service to a paid plan. 

---
### <a href="#roomcoin-definition" name="roomcoin-definition">**What is a _Roomcoin_?**</a>

_Roomcoin_ is a Sameroom currency (well, not really). As an example, a Roomcoin with a nominal value **2** allows its owner to keep **2** Unlimited Tubes without paying for them by a credit card. Note that Roomcoins are transferable (so if you don't need a Roomcoin anymore, you can hand it over to your friend).

We hand out Roomcoins during our promotional events.

Here is our [Roomcoin page](https://sameroom.io/roomcoin). 

---
### <a href="#bot-account" name="bot-account">**What is a _bot account_?**</a>

We recommend to use so-called _bot accounts_ (specially created accounts) to create Portals and/or Tubes for chat rooms from the following subset of [supported platforms](/getting-started/en/faq/list#supported-platform):
 
 - Campfire
 - Gitter
 - HipChat
 - IRC
 - Skype

---
### <a href="#tube-creation" name="tube-creation">**Do you have a step-by-step example of a Tube creation?**</a>

Yes, we do. In our example, the Simpson family is using _Skype_ as their primary chat platform, and the Springfield Nuclear Power Plant (where Homer Simpson works as a Safety Inspector) is using _Slack_. Mr. Burnes does not allow to use Skype by his employees, so Homer needs to connect a Skype conversation named _Caramba_ (where Bart posts math problems Homer is supposed to help him to solve) with the Slack channel (named _#Secret-channel_).

#### ![step-1.png](https://in.kato.im/b8be284b81c9467fed3170d274c28de6789dd2fae1957895cd34bc20a2676d25/step-1.png) &ensp; **Prepare your bot accounts**
 
In our scenario, Homer has access to both rooms he would like to connect. For _Skype_, we recommend to use a [bot account](/getting-started/en/faq/list#bot-account), so Homer has added a new bot account to the Skype _Caramba_ conversation: {picture}. 

#### ![step-2.png](https://in.kato.im/99977b264e016814f4af35ac12a7fe42f1138758cd4b9285fa8c34e628a264fd/step-2.png) &ensp; **Open Sameroom and join it using your chat platforms**
 
Homer visits [https://sameroom.io](https://sameroom.io) in his favorite browser and joins it using his bot Skype account first, and then using his Slack acoount: {picture}. 

[[See how]](/getting-started/en/faq/list#join-sameroom) to do that.

#### ![step-3.png](https://in.kato.im/763f5cfdca4b46f6700a5fb457aa9bb52c22b54ae79653324c24a5c75c78d2/step-3.png) &ensp; **Click on the _Open a Tube_ menu option**

If Homer sees the _Select Side A_ page, he is already in the right place. If he does not see that page, he needs to click here: {picture}.

#### ![step-4.png](https://in.kato.im/aaca13a3bf3bd02e7c564df12590fd48a6158e7f255b70f71ccb95b1eb813552/step-4.png) &ensp; **Search for your room name _A_ and select it**

Homer enters the Skype room name _Caramba_ in the search box: {picture}. 

Note that the room name is visible in the drop-down list. Homer clicks on it there.

#### ![step-5.png](https://in.kato.im/d60566787495e1d710e7cafc8d5580c1fd2cd1aaf7c9e75bb4048a98b5e3dada/step-5.png) &ensp; **Search for your room name _B_ and select it**

Homer enters the Slack room name _#Secret-channel_ in the search box: {picture}. 

Note that the room name is visible in the drop-down list. Homer clicks on it there.

#### ![step-6.png](https://in.kato.im/f093511f290ddcb9e024632b397679fa05a17d0b414fec44b5cbd2b55148d8/step-6.png) &ensp; **Look at your new Tube**

Homer sees his new Tube on the _Manage_ page: {picture}

#### ![step-7.png](https://in.kato.im/a1fb64af4d3bd98f7deae4722bcb4d7b75de7851657014ee568db97dda7e7013/step-7.png) &ensp; **See how your new Tube is working**

After the new Tube is created (and we recomment to wait about 30 seconds), Homer posts a message in his _Slack_ room _#Secret-channel_: {picture}

Bart sees that message in his Skype room _Caramba_: {picture} 

Bart responds in his Skype room _Caramba_: {picture}

Homer sees that message in his Slack room _#Secret-channel_: {picture}  

---
### <a href="#security" name="security">**How about Sameroom security?**</a>

Sameroom stores maximum 20 last messages over 24-hour period for each Sameroom-connected room (to be able to provide some context after a new room is connected to the existing one). No other messages are being stored in Sameroom.

Security of the relayed messages from or to a [supported chat platform](/getting-started/en/faq/list#supported-platform) is not better or worse that security of that chat platform.

Sameroom does not store your credit card data - [Stripe](https://stripe.com) does.

Sameroom does not store your passwords or session information for any of [supported platforms](/getting-started/en/faq/list#supported-platform) - your browser does, if any (in cookies).

Sameroom does store maps of your Sameroom-connected networks, your Roomcoins, and some elements of your credentials (like email addresses and/or nicknames) for [supported chat platforms](/getting-started/en/faq/list#supported-platform) to be able to identify you. 

---
### <a href="#troubleshooting" name="troubleshooting">**What to do if my Tube does not work?**</a>

Here we are going to describe a "normal" process of self-troubleshooting. Even if you cannot fix a problem by yourself, it would be very useful if you can do some screenshots on each step. It will help us to recognize and fix a problem with your Tube. 

#### ![step-1.png](https://in.kato.im/b8be284b81c9467fed3170d274c28de6789dd2fae1957895cd34bc20a2676d25/step-1.png) &ensp; **Check your Tube on the Manage page**
 
Sometimes, you can see on the [Manage](https://sameroom.io/manage) page **Failed** Status for your non-working Tube:

![clip.png](https://in.kato.im/4d83b7163e9189a39da18b22d2647e96ea559a022867923ac6baf0aa4b09a836/clip.png)

{describe actions}

#### ![step-2.png](https://in.kato.im/99977b264e016814f4af35ac12a7fe42f1138758cd4b9285fa8c34e628a264fd/step-2.png) &ensp; **Post the `-sameroom map` message in your connected room**

Normally, your Tube should look on the Manage page like this: 

{picture}

If you do not see something strange on the Manage page, post this message in your room which is connected by your non-working Tube:

`-sameroom map`

If your Tube is Active, you will see this kind of response in your room:

{picture}

#### ![step-3.png](https://in.kato.im/763f5cfdca4b46f6700a5fb457aa9bb52c22b54ae79653324c24a5c75c78d2/step-3.png) &ensp; **Ask us!**

If everything looks normal and your Tube still does not work, ask us for help.

{explain how}
