## Module Two Team Project Plan
Nicholas Wilkins [Member] {Responsibilites: Possible Game Tester

Michael May [Member] {Responsibilites: Lead QA Tester

Tim Jagielski [Not Assigned Yet] {Responsibilites:

[Team Charter]
The purpose of this team is to produce a game or level utalizing a Top-Down perseptive. 

So far our teams communication has been through email but we have other forms of contact if needed like text messaging through the phone.

We have been communicating every few days due to are busy schedules. It seems the weekend is a good time for us to figure out what to work on throughout the week.

[Project Vison and Goals]
The Project is in a Beta faze as the team is currently making plans and figuring out what we want to do for the final project.

The Project would be in its Alpha faze when the idea becomes more relized with a game and code being developed.

We have come together and decided that we want to make a Top-Down Game with a Medieval theme. Are inspiration is old tower defence games like Plants vs Zombies and a flash game called Dungeon Defender.

## Module Three Team Development: QA and Testing Plan
To test out our project we will assign a member to become a game tester. They will play the game to detect any errors or bugs the players could come into contact with. 

[How we should Test It? / Reported]

//Nick
I believe it would be a good idea that every time the project is commited or updated to have the Game tester go through and mark down any problems they come across that can be fixed before the next commit. The Tester can make a word doc or an additional section in the ReadMe for the others in the team to seem exacatly what is wrong and where the problem occured. The Tester will not only have to check out the objects and levels made for the game but the code as one simple mistake can be disaterous to the development of the project.
//side note I have created an aditional file for the game tester to input any issues they run into so the whole team can view it.

//Michael - added after the repo was fixed
I believe when it comes to testing anything that getting as many sets of eyes on the test build is the best way to ensure as many bugs are caught as possible. I've gone ahead and volunteered myself as the lead tester but I would also like that all three of us at least take a brief look over major builds as we progress for anything that might have been missed. I plan to thoroughly check over every aspect of the game as lead tester as even one small error can be a huge detriment to the final product. I also plan to make a checklist to go through each testing phase to keep track of where improvements are needed in a neat and orderly manner.

[Schedule]
We will constantly play test the game during the preproduction to make sure the game runs smoothly. While we might miss some things like every game company in the world, we will create a Demo for players to test out and give feedback. This allows us to make changes and fix any problems before a full release. 

## Module Four Team Refelction

What went Well?

//Nick created a Top-Down player character. He used the help of one of Unreal Engines test projects to get an idea of how it should work. The player character features two forms of movement options with the keyboard/mouse and a fire action. The first movement is keyboard inputs that utalize W,A,S,D to point the player in a certain direction. The secound player movement is a rotation. The Player character follows the mouse around the screen. A fire action activated by the left mouse click is used with the rotation of the player so the projectile that was added can hit the enemies. The enemy characters will follow the player across the map and if they come in contact with the player the player get destroyed. If the projectile makes contact with the enemy first then the enemy is destroyed.

//Michael
Michael got access to the build of what Nick created after gaining access to the new repo. After briefly testing the build, a few bugs were noted and quickly fixed by Nick while working on the project and during the brief test, no more major bugs or issues were found. The player character moved without issue, following the mouse around the screen and fires without issue using the left mouse click. 

What would you do differently?:

//Nick
I would like to try and make sure I have more time to work on the project. I dont want to have this project in the back of my mind and have to rush certain parts to make sure it gets done just because the rest of my life is a bit busy. I want to implement some possible animations to go along with the fire machanic and have some variation in enemy types. The map needs to have some scenery so it doesnt look so bland but I just wanted to make sure there was some gameplay to give the project life.

//Michael
I was unaware there was an issue with the previous repo and found out about the new one far too late in the week because of illness. I'd like for myself to check on these things more, even if I'm busy with other classwork or not feeling my best. I'm not usually the type to like working in a team and truly am not good at communication which is something I need to massively improve. I'd like to be able to spend some time adding some small bits details, something I can't do if I let myself drag behind.

Possible Bugs

//Nick
A bug that was fixed in a matter of minutes was the inputs for the directions being wrong or backwards. It was eventually fixed by adjusting the code to send the right inputs when certain buttons were pressed. It was a simple mistake that could have messed up the team when testing a level layout in the future.
The one of the issues that we expierenced was a lighting glitch which has been solved. The lights won't work when the level is played but I eventually relized that I acidently removed the object that made the light. While it may not have been a bug it was still an issue that was overcome.
When making the projectile for the player character the object wouldnt fire. It turns out a bit of the code I made was wrong but got it fixed and the correct mesh wasnt applied so it wasnt appearing when fired.

//Michael
When I booted up the build for a brief test I didn't notice any issues and all of the bugs Nick mentioned seemed to be fixed. I'll do a more in-depth look in the near future to catch any bugs that may have been missed before Nick or I add anything major.

Helpful tools:

//Nick
The use of youtube and looking at the basic Unreal Projects that are provided help Nick out when he is working. They give him a clear view of what he is supposed to do or how to fix an issues that he has run into. Youtube supplies many videos and tutorials on how to get any idea for the project to be functional. These videos come in handy just in case the user forgets how to do something in unreal engine. 

//Michael
The most helpful tool for me is my second monitor. Having access to multiple windows at once makes following a video guide or checking a list much easier.

Not so Helpful tools:

//Nick
So far I havent found any tools that where not helpful in some fashion to me. 

//Michael
I also haven't found any non-useful tools

## Module Five Project Log - Team Reflection

What Went Well?

//Nick 
I had the code working perfectly for the movement of the player and the enemy. The fire mechanism destroys the enemy when hit. I created some object for the player to manuver through when trying to attack the enemeny. I have also not expierenced any forms of interactions with the map layout that would cause me to change it.


What Went Wrong?

//Nick
I encountered an error when pushing the updates to github. "Deletion of directory 'Content/__ExternalActors__/TopDown/Maps/TopDownMap/6/MJ' failed. Should I try again? (y/n) y". It kept popping up and I dont no why but when I typed no it ended up removing what i had done and i had to redo most of what I implemented. Once I figure out the reason for this message appering I hope it will stop me from having to do stuff over.


What would we do Differently?

//Nick
I want to make it so that the enemy characters will respawn when killed that way the player has more things to fight. Not having a respawn point makes the enemies feel not as terifying. The player could easily take out the ones on the map and be left with nothing to do. I also want to impliment a scoreboard to count the players kills so people can compare to see how well they did before being overrun by the enemy. To combat the issue I have been having with the error when pushing to github I will make a clone of the project so that if anything gets deleted I can easily copy it from the other project clone without having to waste hours doing what I have already completed.


Tools/Techniques Not Helpful?

//Nick
While I have been mainly using the same tools as last time and not had many issues, I began to run into a few with GitHub and Unreal Engine 5. When trying to push to github some of the stuff that I have created in Unreal pops up as errors and it will delete what I have done because it wont accept my yes command to keep it. This causes me to have to rewrite what i have done while adding what needs to be completed for this week. Hopefully I can understand the issue and fix it soon.


## Module Six Project Log - Team Reflection

What Went Well?

//Nick
I figured out a way to stop my updates to the project from being deleted. I created backups to work on so none of my stuff would be lost. I also added a few features to the project for the player to interact with. The map layout with all the included objects dont cause any issues with movement of the player. All actions work as planned like movement and fire actions. The enemy also fallows and destroys the player on contact.

What Went Wrong?

//Nick
Im still having an issue with the project deleting stuff i have done when trying to push to the github repository. I still dont know the reason for this but I managed to find a way to keep my project intact. When implementing the scoreboard for the game I had an issue with it multiplying the score after destroying an enemy. The speed up ability didnt work at first but it was becasue I plugged the wrong variable in.

What Previous Evaluations that were integrated?

//Nick
I added more elements to the game project. A scoreboard was added that allows the player to see how many enemies have been destroyed by the player. It is activated by holding down the TAB button on the keyboard. I also put an ability that can be found arcoss the level that will increase the speed of the player so that you can speed out of a bind. The object is placede into the world and when the player comes into contact with it there speed basically doubles. I downloaded some free models off of the Unreal Engine site that I used to make it feel like the enemies were viking attacking the village. 


What would we do Differently?

//Nick 
I would still like to have more time to possibly add more abilities or add some animations to make the game look better. The playercharacter looks pretty basic and has no animation besides running. The bullets that are fired when the left mouse button is pressed are just cones that are stretched but I wanted to desgin it so it looked like a bow and arrow was being shot.

Tools/Techniques Not Helpful?

//Nick
While I have been mainly using the same tools as last time and not had many issues, I still have an issue with GitHub and Unreal Engine 5. When trying to push to github some of the stuff that I have created in Unreal pops up as errors and it will delete what I have done because it wont accept my yes command to keep it. This caused me to have to rewrite what I have done while adding what needs to be completed for this week. I found out how useful the Unreal Engine store is with free object that I can download to make my project look better. I download a village file that included objects that I could place on the level and spruce it up. 


## GAM-495 Final Update

Final Updates Done

//Nick
I went through my blueprints made for my original project. Using the review left by my instructor in my Gam-495 class I adjusted and added comments to the project. I couldn't find any use of the unnecessary debug text in my  final presentation. The only real updates made in the code was comments made to the AI blueprints so certain sections would be easier to understand. The comments tells the viewer what the code layout does for the game. Since I was struggling to push the update to the GitHub I will submit photos to provide my proof of what was done. The project somehow got disconnected from the github and i didnt know how to fix it.
