# How-I-find-FB-bug-about-group's-privacy-issue

Hellow guys, It’s me Janak Karki So today I am going to share the story of my 2nd valid bug fromfacebook that I found. I was searching for bugs in facebook for about 2 weeks but I didn’t find any :( and yeah got some informatives and duplicate too. I was on my vacation so there was nothing for me to do. So everyday I use(d) to search for bugs in facebook One day I went to fb group and saw the option of room in the group.(This is a simple bug)

What was the bug and How I reproduced it?

Title:
A user can join a room in group without any approval.

Vuln Type:
Privacy / Authorization

Product Area:
Facebook — Android

Description/Impact:
I have a group in which there are 10,11 members. I dont know all of them I only know 5 of the members of the group. Today I started a room in the group then a user which I dont know also joined my room in the group. Then I tried to remove him so that from next time If he tries to join my room again then I will have to approve the request as per FACEBOOK itself shows “When you remove someone, your settings will be updated and only people you approve can join. If you change your settings back, anyone will be able to join from the link, including the people you removed.”
But this didn’t happened infact the approval option didnt work in room of FB group (IN FB ANDROID VERSION & FB WEB BOTH) and the unknown user again joined my group so everytime I cant remove him its creepiness and I ended the room .

[It exists in both FB android version and Fb PC . In android verion I just happens but in FB PC there cames a pop up as “There was an error updating your room join permissions. Please try again later.”]

This issue don’t respect the user room privacy. Without authorization of the user any user can user a room in group although how many times the room’s owner remove him/her.

Repro Steps:
Mobile app version: 328v

Go to group & start a room.
2.ask your friends to join the room from group home.
3. A user(antagonist) can also join the room and he/she joined.
4. Remove the user and from next time “you will be given a approval option for anyone to join a group” This notification will be shown in screen.
5. From user(antagonist)’s view , again go to group and join the room, the user(antagonist ) can easily join the room without any approval.
They reproduced it & I got the messages after 3 days and also they triaged after around 1.4 hours of the message of reproduction.

I regularly asked for updates like around in 3 days interval and after 7 days they replied :
They just sent me the message of my bug being triaged(First experience to get double triage messages.)

And after waiting for about a month they rewarded me with bounty of $500 and $25 as a bonus of being delayed.

And yeah I thanked them:).

Timeline:

Reported — Friday, July 30, 2021

Reproduced & Triaged —Tuesday, August 3, 2021

Fix claimed from their side — Thursday, September 9, 2021

Bounty Rewarded — Thursday, September 9, 2021
