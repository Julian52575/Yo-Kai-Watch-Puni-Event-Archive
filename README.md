# Yo-Kai-Watch-Puni-Event-Archive
Archiving all events files of puni puni and wibble wobble.    
This game is a part of our childhood, we must preserve its history.    
Find here a nostalgia trip from the 1st events in 2016 to current day.    

## How to help

If you want to help me preserve the history of this game, here is how you can do it:

### Contribution rules

0. Be civil with other collaborators.    
1. If you want to share new information: [Open a new discussion](https://github.com/Julian52575/Yo-Kai-Watch-Puni-Event-Archive/discussions). Use explicit title and name the event you want to collaborate on.
2. Follow data download folder structure.^1
3. Cite your sources ! Sources vouch for information accuracy and can help other contributors find more !
4. Using lower quality images and screenshots are accepted **as placeholders** and **only if their filename contain the word "placeholder"**. 

^1: The folder structure is as follow, you can copy-paste the template and rename it for convenience:
```
~/Yo-Kai-Watch-Puni-Event-Archive$ tree e000-Template/
e000-Template/
├── README.md
├── gacha
├── image
│   ├── chara
│   ├── common
│   ├── item
│   ├── logstp
│   ├── map
│   ├── puzzleBG
│   ├── puzzleEvent
│   └── web
├── map
├── movie
├── sound
└── ywp_cud
```


### You are a motivated individual

Anyone can collaborate !    
There are plenty of work for motivated individual that have no archive !

Work to be done:
- Filter orphans: Do they belong to an event ?
- Confirm event assets: Was the event really using it ?
- Update event metadata: What was the release date or version ?
- Reuse hunt: What assets got reused on what event ? Was it updated or a straight copy-paste ?

Once collected, update the event's discussion with your findings:
[Open a new discussion](https://github.com/Julian52575/Yo-Kai-Watch-Puni-Event-Archive/discussions) and link your archive.     

#### Where to find information

Entire archive might not be available, but there are plenty of data available online !    
Sources includes:

- Archive.org, such as [Puni 4.117.1](https://archive.org/details/4.117.1), or wibble wobble archive like [NA Wibble Wobble](https://archive.org/details/NAYokaiWatchWibbleWobble.7z), [Taiwan Wibble Wobble](https://archive.org/details/TWPuniPuni.7z). Do note that these older dumps containt beta assets for puni puni events ! Also, the Korean version seems to be lost...
- Youtubers, such as [Robbett Watch](https://www.youtube.com/watch?v=Z76oVmjaUoY&list=PLHVfw4wEWpMjI58QOcg9gS86_6iUi8VUF&index=187) or [Doctor KONAN (has a 4500+ videos playlist on EVERY SINGLE EVENT since the game release](https://www.youtube.com/playlist?list=PLYl1hnwbzjwUe9jCptZvjwr7Zmi2-dokb)
- Dataminers, such as [Random dude on twitter](https://x.com/shinogu_ryo/status/857844835654422528)
- Blogs, such as [Personal blog on the 1st Inazuma Eleven collaboration](https://www.ge-mu.xyz/entry/2017/09/30/013934)
- Perhaps other sources I cannot think about right now.

### You are a dataminer

If you have older data download dumps, please archive them to archive.org (low upload speed, but once the archive arrives on their server it stays there forever).    
[Open a new discussion](https://github.com/Julian52575/Yo-Kai-Watch-Puni-Event-Archive/discussions) and link your archive.     
 
If you feel at ease with Github, you can fork this repository to update the archive folders, then open a pull request that I can review and merge here.    

## Event Ids

Ids are taken from the map_btn.    
Event are prefixed with eNNN where `NNN` is an event id.     
Events without ids (game first months) uses `XXX`.    
Unknow ids uses `UUU`.    
`e_g` are "global" or wibble wobble exclusive event, such as Libertynyan's Liberty Way.    

## What is included

All temporary files that were used for an event.     
3d models, sounds, images, ... whether or not they got reused later.    
Snipets for the ywp_cud data related to the event are included too, but have not been verified on a puniemu server.    
Wibble wobble events are separated from puni puni events.

### Reuse policy

Event folder should be standalone, so assets reused (ie: Inazuma eleven 1st event map) will be uploaded in each folder.    

## What is excluded

Permanent files (yokai models, item images, ...).

