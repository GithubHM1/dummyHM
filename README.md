## Good morning Monday Test 
Thank you !!!!


# dummyHM aka DevOps HW
Still have issues after reading Uli's slides as well as some websites on Github 
Scratching my heading and yes of course losing more hair on the 30th of June 2021

Found an option to try out Discord API vid webhook functionality. So here I am testing it!
Found something and fingers cross on 30th of June 2021

HEY what do you think! It works!!!! But I'm not sure if this qualifies as an API?  What do you think Uli?

## To follow the steps on what I've tried, please read the dummy's guide. 
https://github.com/GithubHM1/dummyHM/wiki/Dummy's-guide-Wiki-version

PS: If the link gets you a 404 for some reason of the other. Look for my ID: GithubHM1 Repository: dummyHM Wiki tab for the full write up
PSS: I didn't know I could get images to work in the README.md file So this is the complete write up! Yeah


# Welcome to the dummyHM wiki Guide to Discord Webhook!


## To whoever that reads this! I promise to make this as instructive as possible and if I can do it, so can you!
Discord's built in Webhooks function as an easy way to get automated messages and data updates sent to a text channel in your server. 
To put it in simpler terms, you get a message via Discord whenever an update is performed in your repository. 

## So what is a Webhook? 😅
If you're asking this question. You're a better student than I am. Simply put, a webhook is a Push API. 
It is a way for an app to provide other applications with real time information. But seriously, I won't bore you 
with more text. If you're a way better student than I am, please read up the following: [Webhook Anyone?](https://sendgrid.com/blog/whats-webhook/)


## So what is Discord? 🥲
Ok, if you're asking this...you're probably as old if not older than I. That don't matter...I've no idea what's 
UiPath before June of 2021 too. So yes... Discord is a VoIP, instant messaging and digital distribution platform 
designed for everyday people. Users communicate with voice calls, video calls, text messaging, media and files in private chats 
or as part of communities called "servers".  Usually for gamers and for technophiles, Discord isn't as popular as Whatsapp, Telegram or 
Facebook. So I won't really blame you if you didn't hear of them!


## So how do we get there? 🤔
In order to first get this started, you'll have to install [Discord](https://discord.com) on your laptop. 

![image](https://user-images.githubusercontent.com/84888095/123969514-e0ade700-d9ea-11eb-8244-b5c920586b43.png)


Once you've launched Discord, play around with the interface! I mean seriously!!! You don't expect to be spoon
fed every step of the way do you?

## So...I know you know that I saw you rolling your eyes when you read the above statement. 🙄
Ok so you need to be spoon fed every step of the way. 

Click on the big PLUS + sign you see on the left hand panel.

![image](https://user-images.githubusercontent.com/84888095/123969291-aa706780-d9ea-11eb-9f76-991f5a32c2b0.png)

Add a server and then click on the drop down menu

![image](https://user-images.githubusercontent.com/84888095/123969323-b2300c00-d9ea-11eb-969b-bb668d69580c.png)

Once you are there, click on the Integration tab

![image](https://user-images.githubusercontent.com/84888095/123969555-ec99a900-d9ea-11eb-8a57-548307690691.png)

Click the "Create Webhook" button to create a new webhook!
You'll have a few options here. You can:

Edit the avatar: By clicking the avatar next to the Name in the top left
Choose what channel the Webhook posts to: By selecting the desired text channel in the  dropdown menu.
It's important to name your Webhook! You may create multiple webhooks subsequently for other services in future.
Once you are done, click on Copy Webhook URL

![image](https://user-images.githubusercontent.com/84888095/123969604-f4f1e400-d9ea-11eb-9dc4-d35e968efefe.png)

## SO....We are almost there!
Add the webhook URL into your GitHub repository settings


<img width="678" alt="image" src="https://user-images.githubusercontent.com/84888095/123974373-24a2eb00-d9ef-11eb-901c-8e07b30a048e.png">

Insert the Webhook URL you've copied from Discord into the Github repository's
Payload URL

Do take note to add in /github as per the image below. 
Leave SSL verification as default setting and select on 'Just the push event' option

<img width="680" alt="image" src="https://user-images.githubusercontent.com/84888095/123974294-1a80ec80-d9ef-11eb-9fe4-a94ea59180a9.png">

Finally click on Add web hook and start 🙏🏻


For each update you perform into your repository, you should receive a notification via Discord in the server channel chat which you've linked with your repository

<img width="387" alt="image" src="https://user-images.githubusercontent.com/84888095/124047955-de2daa80-da47-11eb-81df-b0be9c3a6af7.png">






### PS: It really should work! If it doesn't, you haven't paid attention to the instructions!!!

I would like to credit the work [John Grosh](https://github.com/jagrosh), he was instrumental in my success in creating the web hook link with Github. 
