```.hash <email address>```
**Users: Migrants/New Joins**
> Only works in @BasedCounter DMs, generates a SHA256 hash string from an email address

```.verify <hash>```
**Users: Migrants/New Joins**
> Uses generated hash string to find user's email address in the HOC subscription database

```.resetUser <@member>```
**Users: Border Patrol+**
> Resets a user to Migrant role

```.comrade <@member>```
**Users: Border Patrol+**
> Used after voice verification to accept new member into the server, gives Comrade role and removes previous roles. Use this if user has @Verify-VIP 

```.prole <@member>```
**Users: Border Patrol+**
> Used after voice verification to accept new member into the server, gives Prole role and removes previous roles. Use this if user has @Verify-PROLE 

```.viewLinkedID <hash>```
**Users: Border Patrol+**
> shows you the discord account ID linked to a HOC subscription. May show multiple times, if they aren't all the same then something's wonky innit

```.resetDiscordLink <hash>```
**Users: Stormtroopers**
> removes discord ID from HOC subscription so that it can be tied to a different discord account

```.prune```
**Users: Stormtroopers**
> Used to go through the member list and "de-comrade" anyone who is not actively subscribed to the website. These people, at staff discretion, may only need to re-subscribe without a second voice interview to get back in. A to-be-created bot command will eventually be able to tell whether a user's discord account is linked in the database already or not to help with that.
