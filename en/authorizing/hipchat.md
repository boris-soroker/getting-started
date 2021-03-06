---
Authorizing Sameroom with HipChat
---

####Note: due to certain limitations of the HipChat API, we highly recommend inviting a "Sameroom Bot" account to your HipChat team, and using this account to create Portals and Tubes on Sameroom.

---

#####Log in to your <a href="https://www.hipchat.com/sign_in" target="_blank">HipChat account</a>,

#####Click on "Group Admin" (You'll need admin access),

![HipChat Group Admin](https://in.kato.im/ddbb26118fdbbcb6ef1adc1fbf232acdda8866fe065ac4ae2c07dfd7a7c9f/Sameroom_HipChat_Group_Admin.png)

#####Click on the "Users" tab,

![HipChat Users Tab](https://in.kato.im/ddbb26118fdbbcb6ef1adc1fbf232acdda8866fe065ac4ae2c07dfd7a7c9f/Sameroom_Click_users.png)

#####Click on "Add",

![Add HipChat User](https://in.kato.im/ddbb26118fdbbcb6ef1adc1fbf232acdda8866fe065ac4ae2c07dfd7a7c9f/Sameroom_Add_User.png)

#####Enter the details for the "bot" user and click "Add user" (if your email address is alice@example.com, you can invite alice+sameroom-campfire-bot@example.com, which will go to your regular inbox),

![HipChat User Details](https://in.kato.im/ddbb26118fdbbcb6ef1adc1fbf232acdda8866fe065ac4ae2c07dfd7a7c9f/Sameroom%20HipChat%20Add%20User.png)

#####Follow the instructions in the HipChat email to setup the "bot" user account,

#####Go to the <a href="https://hipchat.com/account/api" target="_blank">HipChat Account API</a> page and login with your "bot" user credentials,

#####Click on "Re-create token" to re-create the "bot" users Personal OAuth 2 Bearer Token,

![clip.png](https://in.kato.im/dd9055f7d2f3bcad535ee373c06d649993c5d30f919639e6bb1b9665efa7a016/Sameroom_HipChat_Account_Settings.png)


#####Click "OK" in the pop-up message,

#####Go to <a href="https://sameroom.io" target="_blank">sameroom.io</a> and click on the HipChat logo,

![clip.png](https://in.kato.im/4c8bbe1a1338bc5da71ffd614e9be70a5694f208c138479c6de1a784f1d61d89/Sameroom%20HipChat.png)


#####Copy the OAuth 2 Bearer Token into the HipChat Token field and click "Submit" to authorize Sameroom with your HipChat account.

![clip.png](https://in.kato.im/d8d4f1003421016ba7d54cd669dde49319229ba235bc766285b205fd2d44078d/Sameroom%20Sign%20In%20HipChat%20copy.png)

---
####Once you've authorized your HipChat account, you can either; connect two chat teams by [creating a Tube](/getting-started/en/tubes-portals/tubes) or, share a chat room via a [Portal URL](/getting-started/en/tubes-portals/portals).
