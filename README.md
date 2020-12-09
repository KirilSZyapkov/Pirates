# Pirates

Anno 1681. The Caribbean. The golden age of piracy. You are a well-known pirate captain by the name of Jack… Daniels. Together with your comrades Jim (Beam) and Johnny (Walker) you have been roaming the seas, looking for gold and treasure… and the occasional killing, of course. Go ahead, target some wealthy settlements and show them the pirate`s way! 

Description 

Until the "Sail" command is given you will be receiving: 

Cities that you and your crew have targeted, with their population and gold, separated by "||". 

If you receive a city which has been already received, you have to increase the population and gold with the given values. 

After the "Sail" command, you will start receiving lines of text representing events until the "End" command is given.  

Events will be in the following format: 

"Plunder=>{town}=>{people}=>{gold}" 

You have successfully attacked and plundered the town, killing the given number of people and stealing the respective amount of gold.  

For every town you attack print this message: "{town} plundered! {gold} gold stolen, {people} citizens killed." 

If any of those two values (population or gold) reaches zero, the town is disbanded. 

You need to remove it from your collection of targeted cities and print the following message: "{town} has been wiped off the map!" 

There will be no case of receiving more people or gold than there is in the city. 

"Prosper=>{town}=>{gold}" 

There has been a dramatic economic growth in the given city, increasing its treasury by the given amount of gold. 

The gold amount can be a negative number, so be careful. If a negative amount of gold is given print: "Gold added cannot be a negative number!" and ignore the command. 

If the given gold is a valid amount, increase the town's gold reserves by the respective amount and print the following message: "{gold added} gold added to the city treasury. {town} now has {total gold} gold."
