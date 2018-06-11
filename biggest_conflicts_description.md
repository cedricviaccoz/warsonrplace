# Biases  & Limitations :
* Bots are more efficient than humans in attacking/defending a piece of art. However this would pose no real problem for our research, as those bots are just enhanced versions of human contribution. The intent of protecting and/or attacking a zone still come from a human decision, wether the user actually does it, or program a bot in order to do it.  

* We take as the absolute truth the "corrected" version of the canvas, in order to decide which pixel are correct or not. It needs to be considered that the correct version only depicts the ideal version at the last moments of the canvas, some artwork evolved during the whole place existence. For example the denmark flag used to have a muche smaller are of occupation until the last day, where this community decided to expand beyond its region. Thus for the denmark flag, part of its existence would be considered as "incorrect" or highly vandalised according to our tools. Fortunately, most of the artworks (would need number to be computed!) from the canvas got their final form pretty early in the existence of r/place, thus diminishing this bias toward this conflict study.


* The way we consider communities conflicts as positive and negative contribution : Communities could have only negative contributor, or separation of roles between attacker and defendant. Such behavior can not be observed with our tools.


* Why we need computational tools to observe conflicts on a website with persistent database : Verbal traces exist of these conflicts, as threads arose on the different subreddits about the subject during the  whole experiment duration. It would be however harder to detect those conflicts out of those threads because 1. it requires filtering out threads about r/place from the others 2. doing some textual classification/processing in order to correctly extract wether a community decided to attack/vandalise another one. (it's definitely not impossible with today ML and NLP techniques, but out of the scope of what we can do for this project)

# Conflicts Type

### _Spatial_
An artwork takes too much place on the canva, thus some communities feel some injustice about the zone repartition. Out of jealousy, they attack the more greedy community.

Examples : Osu, Americanflaginplace

### _Contextual_
One community has some behavioural rules or goals which leads them to override or destroy other artwork.

Examples : theblackvoid, /r/ainbowroad


### _Expansion (Expansional ?)_
One artwork seeks to expand its territory past its preceding boundary, and thus overrides some artwork from other communities.

Examples : Norway over Texas, Germany over France


### _Ideological_
There is an pre-existing ideological difference between two communities that get translated into conflict of vandalism between the two corresponding artworks on the canva.

Examples : Sweden vs Denmark, The_Donald vs TheFarLeftSide

# Ranking of biggest conflicts : 
__TODO__: Add the reverse conflict on the results table, so the unilaterality of the attacks can be clearly seen. (as it was done for sweden and denmark) + For OSU and AFIP, collect tables (or compute number) which compiles all the subreddit they attacked, and how many subreddit they were attacked by. 

AREA RESULTS W/OUT MULTIPLE AREA CONSIDERATION :

* "americanflaginplace" is 12116.0
* "sweden" is 18047.5
* "denmark" is 1012.0
* "norge" is 11788.5
* "thefarleftside" is 1091.5
* "theblackvoid" is 3103.0
* "europe" is 3294.0
* "ainbowroad" is 87371.5
* "de" is 6480.0
* "placede" is 6480.0
* "stlouisblues" is 1752.5
* "ireland" is 10050.5
* "purplepixels" is 3740.00
* "osugame" is 6204.5

W/ MULTIPLE AREAS CONSIDERATION :

* "americanflaginplace"'s area is 12116.0
* "sweden"'s area is 18047.5
* "denmark"'s area is 7443.5
* "norge"'s area is 11788.5
* "thefarleftside"'s area is 1091.5
* "theblackvoid"'s area is 11122.5
* "europe"'s area is 4830.0
* "ainbowroad"'s area is 105079.5
* "de"'s area is 18806.5
* "placede"'s area is 18806.5
* "stlouisblues"'s area is 1752.5
* "ireland"'s area is 10050.5
* "purplepixels"'s area is 4978.0
* "osugame"'s area is 6204.5


Note that some entries of the listing are false duplicated, as they occupy the same zone on the canvas, and thus characterizes the same conflict (for example the 8th entry, /r/de and /r/placede are two different subreddits but intrasically linked in a way they defend the same zone, in this case, the german flag), they were thus put in the same line.
Also note that included in the ranking are some other interesting conflict which help characterizes big event of r/place's history. (Such as the counter attack on the void anihilation of the american flag)

OC stands for "Opposite conflict", so each line also contains the amount of reverse conflict that happened too.

| Rank | Positive contribution on | Negative contribution on | user # | OC Rank | OC user # |
| ---- | ------------------------ | ------------------------ | ----------------------------------------- | ------ | ------ |
| 1 | /r/sweden | /r/denmark | 382| 603 | 10 |
| 2 | /r/americanflaginplace | /r/ainbowroad | 247| 28 | 84 |
| 3 | /r/osugame | /r/placestart | 171 | 296 | 18 | 
| 4 | /r/osugame | /r/stlouis | 154 | > 1000 | < 7 |
| 5 | /r/americanflaginplace | /r/thefarleftside | 146 | 75 | 48 |
| 6 | /r/americanflaginplace | /r/norge | 136 | 597 | 10 |
| 7 | /r/osugame | /r/stlouisblues | 136 | > 1000 | < 7 |
| 8&9 | /r/placede & /r/de | /r/europe | 127 | 458 | 13 |
| 10 | /r/americanflaginplace | /r/purplepixels | 117 | 899 | 7 |
| 11 | /r/americanflaginplace | /r/ireland | 114 | 464 | 13 |
| ... | ... | ... | ... | ... | ... | ... |
| 15&16 | /r/americanflaginplace | /r/theblackvoid & /r/thegreatblackhole | 93 |  105 | 37
| 17&18 | /r/de & /r/placede | /r/americanflaginplace | 92 | 69 | 52 |



## SWEDEN VS DENMARK
##### R/DENMARK :

SUBCOUNT : probably between 71’152 ([31.03.17 - 14h38:52](https://web.archive.org/web/20170310143852/https://www.reddit.com/r/Denmark/)) and 75’470 ([23.04.17 - 17h32:09](https://web.archive.org/web/20170423173209/https://www.reddit.com/r/Denmark/))

AREA : 1012 pixels

##### R/SWEDEN :
SUBCOUNT :  probably between 154’586 ([16.03.17 - 10h14:18](https://web.archive.org/web/20170316101418/https://www.reddit.com/r/sweden/)) and 157’871k ([03.04.17 - 00h56:54](https://web.archive.org/web/20170403005654/https://www.reddit.com/r/sweden/))

AREA : 18047.5 pixels

r/sweden attacks r/denmark unilaterally. 384 users with positive contributions to Sweden have negative contribution to Denmark. While in the other way it is only 10 people. Why is this penomenon so unilateral? Sweden has more subscribers, and a bigger area, both seems to imply that more swedes were invested in r/place. Both actual countries have been at war against each other for centuries, but they come to peace since the XIXth century. Still some sort of rivalry and mockery exist between the two nations. This [reddit comment](https://www.reddit.com/r/sweden/comments/22aksj/why_do_swedes_and_danes_seem_to_hate_each_other/cgkxdch/) highlights how on the website the mockery/rivalry still exists.

What is interesting however, is when looking at the evolution of the flag, it can be seen that it was temporarily taken over by r/sweden and transformed into the swedish national flag during the first day of r/place. Such a takeover has probably been eased by the similarity of both flags, as they both depict two crossing line of the same color above a uniform background from another color. Only the colors change between the dannish and swedish flag. This means for the average /r/sweden subscriber attacking /r/denmark, he only had to change white pixels of the danish flag into yellow, and red pixels into blue. Thus such 

__Reason of conflict__: Ideological




## IMPORTANT ATTACKS BY AMERICANS SUBREDDITS

#### R/AMERICANFLAGINPLACE :
SUBCOUNT : Created on the 1st of April, at the end of the experiment, had surpassed 500 subscribers (src : http://redditmetrics.com/r/AmericanFlaginPlace)
#### R/THE_DONALD: (they helped building and defending the flag according to the r/place atlas)
SUBCOUNT : between 385’685 ([31.03.17 - 22h38:51](https://web.archive.org/web/20170331223851/https://www.reddit.com/r/The_Donald/)) and 387’242 ([04.04.17 - 00h12:02](https://web.archive.org/web/20170404001202/https://www.reddit.com/r/The_Donald/))

AREA : 12116 pixels


### VS R/AINBOWROAD :

SUBCOUNT : Created on the 31st of March, at the end of the experiment, had surpassed 5000 subscribers ([source](http://redditmetrics.com/r/ainbowroad))

AREA : 87371.5 pixels

Interesting as both subreddit emerged from the canvas itself. The conflict came largely from the last day of r/place, where the american flag got destroyed by the void, and the rainbow road which was adjacent, took just the newly « blank » place to expand on it (comes from r/ainbowroad philosophy of filling every empty places of the canvas with the rainbow (need source for that)). Once AFIP got back on its feet, it reinstalled the flag at the center of the canvas.

__Reason of conflict__ : Expansion (rainbow road expanding because it was close to it) && contextual (rainbow road took the place to avoid the void keep on expanding)

### VS R/THEFARLEFTSIDE

SUBCOUNT : Created on the 31st of March, at the end of the experiment, had surpassed 1000 subscribers ([source](http://redditmetrics.com/r/TheFarLeftSide))

AREA : 1091.5 pixels

The "far left side", which also stemmed from the canva, is, as its name imply, a zone located on the far left side. However the name also stands for the political orientation, as people of this community are united under ideologies coming from the far left side of the political spectrum (the place they occupied on the canvas is known for having the communist emblem "the hammer and sickle" in yellow above a red background).
According to the table above, they have been attacked by the communities build around the american flag. This conflict might come from the political opposition between this community and r/the_donald, who is famous for hosting many reddit users with far-right ideologies. Even without the implication of r/the_donald, it is reasonable to think that the average american patriotist would be again such a community, as the country has historically always been opposed to communism.

__Reason of conflict__ : Ideological

### VS R/NORGE

SUBCOUNT : 
AREA : 11788.5 pixels

The attack of the americans on the flag from Norway seems to be quite inexplicable, as no real tensions seemed to exist between the two nations, and the place each artwork occupy are far apart so no neighboring expension could explain such conflict. The truth however lies in a information that can not be seen on the raw final result of the canvas. Looking on the r/place atlas, a [small rectangular zone can be highlighted on the center top part of the Norvegian flag](https://draemm.li/various/place-atlas/?id=1302), doing so display the following bit of information :
_"The original location of the Texas flag before Norway's flag expanded and eventually consumed it."_

Thus, it can be safely assumed the american attack was actually an effort into preventing the norvegian flag to override a flag from one of the state from America.

__Reason of conflict__: Expansion


### VS R/PURPLEPIXELS
SUBCOUNT : 
AREA : 3740 pixels

What is purplepixels ? [According to the atlas](https://draemm.li/various/place-atlas/?id=1158) : _"This area was originally black in background, but after /r/purplepixels distanced itself from /r/purplecorner for reasons that caused the purple corner to fall, /r/purplepixels relocated to this area to ensure that purples would be represented on the final canvas."_ The zone it occupies is a small rectangular area around the top left corner, far appart from the american flag. So no obvious reasons for this conflict... Even considering r/purplepixels as the remnants from the purple corner, such corner did never reach the place the american flag would occupy.

__Reason of conflict__: ?

### VS R/IRELAND
SUBCOUNT :

AREA : 10050 pixels

Ireland mainly had a vertically stretched out nationl flag located under the center of the canvas. Integrity over time graphs (would need to show them for both of the countries) shows that the flag of Ireland predated the american flag but took a long time to reach its final form. Inspecting the timelapse shows the ireland flag took a slow ascent to the north until reaching the american flag where it stopped its northern expansion. During the void total annihilation of the american flag, the Irish flag restarted its northern expansion, which was rejected back to its original border once the American flag reconquered the center of the flag.

__Reason of conflict__: Expansion

### VS R/THEBLACKVOID AND R/THEGREATBLACKHOLE
SUBCOUNT : ([source](http://redditmetrics.com/r/theblackvoid))

AREA : 3103 pixels

This conflict is kind of a counter attack from the american after the void annihilated the American flag. The american factions simply took back the place they used to occupy before the attack.

What is surprising though, is that only the counter attack was correctly recorded by the tools used. One might ask why the first attack by r/theblackvoid did not get an equivalent place as the reverse on the classement. This come from the contextual foundation 

__Reason of conflict__: Expansion (but comes from the contextual previous attack of theblackvoid)

## IMPORTANT ATTACK MADE ON THE AMERICAN FLAG/CANVA CENTER

### R/DE AND R/PLACEDE VS AMERICA
#### R/DE
SUBCOUNT : Between 55'125 ([26.03.2017 - 15h45:39](http://web.archive.org/web/20170326154539/reddit.com/r/de/)) and 57'188 ([14.04.17 - 16h55:09](http://web.archive.org/web/20170414165509/https://www.reddit.com/r/de/)) but more likely around 56'282 ([02.04.17 - 14h14:40](http://web.archive.org/web/20170402141440/https://www.reddit.com/r/de/)

#### R/PLACEDE 
SUBCOUNT :  Created on the 1st of April, at the end of the experiment, had surpassed 500 subscribers ([source](http://redditmetrics.com/r/placede))

AREA : 18806.5 pixels

Germany on r/place was really active, as can be seen by the relative important area it successfully occupied and the many subscriber it held on the main subreddit /r/de. The only reason for such an attack on the american flag might come out of jealousy of the center spot american took, or out of german americanophoby (but is it something that should have some source backing some kind of american aversion by germans redditor)

__Reason of conflict__: Maybe spatial or ideological.


##GERMANY VS FRANCE

#### R/FRANCE

SUBCOUNT : likely between 134'215 ([31.03.17 - 15h00:02](https://web.archive.org/web/20170331150002/reddit.com/r/france/)) and 135'183 ([03.04.11h00:02](https://web.archive.org/web/20170403131102/https://www.reddit.com/r/france/))


AREA DURING THE ATTACK : 4830 pixels


This is one of the most well-known conflict of the canvas, yet it does not appear in the classement above, because the zone that used to hold the french flag on the canvas was replaced by the european flag by the end of the experiment. Considering the fact the atlas used the final version of the canvas as a basis to distinguish the different zones, and the fact that France successfully relocated after this attack, this explains why this conflict is categorised between Germany and Europe.
What happened early after the establishment of the German flag, was an horizontal (to follow the lines of the flag) expansion mainly to the right. France was farther away on this trajectory, and got overriden by the german flag, only to survive by expanding vertically to the top (again, following the lines of the flag which are conveniently perpendicular to the one from Germany's flag). After a few time of german establishment on the zone, an alliance was made with the French to build an european flag at the intersection of the two flags, where France used to be. ([official source showing a timelapse of the event described](https://redditblog.com/2017/04/18/place-part-two/))

__Reason of conflict__: Expansion motived by a bit of ideological/contextual goals (the comical aspect of invading France _again_).


## OSU! The game

#### R/OSUGAME

SUBCOUNT : Likely between 33'855 ([20.03.17 - 15h02:44](http://web.archive.org/web/20170320150244/reddit.com/r/osugame)) and 35'527 ([05.04.17 - 07h36:30](http://web.archive.org/web/20170405073630/https://www.reddit.com/r/osugame/))

AREA : 6204.5 pixels


### VS R/PLACESTART

#### R/PLACESTART 

SUBCOUNT : 

AREA : 

/r/placestart was another one of the community that stemmed out of the canvas. The user united under this community had a was pretty simple goal: to build a mockup of the windows 95 start toolbar on the bottom of the canvas. Starting from the lower left corner, they built the toolbar during the second day of the experiment up until three quarter of the canva's bottom. On the way of their left to right expansion, they crossed the bottom part of the round "Osu!" logo. Although an agreement was eventually made in order to allow r/placestart to cross the logo, the osu community tried to avoid the lower part of their logo to be vandalise, thus creating this conflict.

__Reason of conflict__: Contextual (r/placestart had as a goal to occupy most of the canva's bottom).

### VS R/STLOUISBLUES

