# What it can do?
It's a bot which can host an Auction for you. A few fun commands are also added into it. So let's have a look at it's commands briefly.
## Auction commands
These are the commands by which you can run an auction in your server.
### setpurse
This is the command by which you can set purse of a user.
<br>**Required Arguments** :- <user> <purse>
Purse can be in million or billions so your ease I have added m and b feature, let's say you want to set my purse in millions so you will type [prefix] setpurse @Khawer#6683 3m. It should set my purse as 3millions. If you use prefix setpurse @Khawer#6683 3millions, it will break.
<br>**Aliases** :- sp
<br>**Required Permission/role to run this command** :- You need administrator permission or Auctioneer(case sensitive) role to be able to run it.
### setlogchannel
This is the command by which you can set the logging channel where the bot will type all the logs of your auction.
<br>**Required Arguments** :- <channel>
You need to provide a logging channel or I'd of that channel..
<br>**Aliases** :- slc
<br>**Required Permission/role to run this command** :- You need administrator permission or Auctioneer(case sensitive) role to be able to run it.
### bal
This is the command in which you can check your or anyone's purse.
<br>**Required Arguments**: [member](this is an optional argument)
<br>**Aliases**:- b, wallet
<br>**Required Permission/role to run this command**:- None
### sell
This is the command where you start the auction on a player.
<br>**Required Arguments** :- <player to sell> <baseprice> [increment] 
I.e $sell Kohli 4m 3m. It has a simple problem which can solved by a simple act of you. Like if you sell a player who has two names i.e Babar Azam then it will break so it's adviced to use slash command /sell.
<br>**Aliases**:- None
<br>**Required Permission/role to run this command** :- You need administrator permission or Auctioneer(case sensitive) role to be able to run it.
### bid
It's a command where players can bid using it.
<br>**Required Arguments** :- None
<br>**Aliases**:- None
<br>**Required Permission/role to run this command** :- None
### setdifference
It's the command where you can set difference/increment.
<br>**Required Arguments** :- <difference>
Difference can be added with m and b i.e setdifference 4m.
<br>**Aliases**:- sd
<br>**Required Permission/role to run this command** :- You need administrator permission or Auctioneer(case sensitive) role to be able to run it.
### leaderboard
It's a command where a leaderboard will appear of your own server. Want to delete someone's name from it? simply set his purse to 0
<br>**Required Arguments** :- None
<br>**Aliases**:- lb
<br>**Required Permission/role to run this command** :- None
### sold
once a bid is concluded on player, you can end the bids on a player using this.
<br>**Required Arguments** :- None
<br>**Aliases**:- None
<br>**Required Permission/role to run this command** :- You need administrator permission or Auctioneer(case sensitive) role to be able to run it.
### squad
You can see your bought players or another user's.
<br>**Optional Argument**:- [user]
<br>**Aliases**:- None
<br>**Required Permission/role to run this command** :- None
### delete
You can delete a player from someones squad or even all players.
<br>**Required Arguments**:-<player><index>
Index can be all, everyone or max. Want to delete a specific player? Check that player's index by squad command and set index to that index.
<br>**Required Permission/role to run this command** :- Administrator
### set_automatic_sold_time
It's an slash command, Only members having Administrator permission can use it. What it does is it sells the player automatically after x seconds. X seconds can be defined by this command. You can disable this feature by giving 0 as a value. However it's adviced to not give a value of minimum than 5. It's a kind of pro command. You need to invite 5 people to support server to get it activated in your one server.
# Management Commands
### prefix
It's a command where you can your server's prefix for the bot. Default is $.
<br>**Required Arguments** :- <prefix>
<br>**Aliases**:- None
<br>**Required Permission/role to run this command** :- You need administrator to run this command.
# Other Commands
### Vote
You can vote for the bot on top.gg.
#### Perks 
A supporter role in support server.
