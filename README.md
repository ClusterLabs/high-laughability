# High-lAughability - Quotes from our HA overlords

## Funny, insightful, or otherwise interesting things said by members of the team. Reverse chronological order, like a blog.

### We have no secrets
````
18:16 < illustris> We'll start testing probably by early next week. As for remote access, I personally fully trust you guys, but remote access to a company datacenter will be really tough 
                   to sell the higher ups on XD
18:16 < illustris> I can push corosync debug logs and core dumps to an AWS server outside our infra for you to access.
18:27 < ^C> I've to go, thank you and see you next week. Bye!
18:38 < fabbione> illustris: ack i understand.. well you can always make the case: "Well those are the same guys that write kernel patches.... we run their code no matter..." :P
18:38 < fabbione> illustris: just joking... btw your credit card num is...
18:39 < illustris> haha... screenshotting and sending to my manager
18:39 < fabbione> LOL
18:39 < ^C> LOL
````

### Answer to the ultimate question of life, the universe, and everything
````
<illustris> I'm still not sure why there is a spike in backlog only when some nodes are added. 42 caused it, 43 didn't, and 44 did again
<honzaf> I would understand 42, but not 44 :)
<honzaf> (The Hitchhiker's Guide to the Galaxy)
<honzaf> no matter what, I would bet it has something to do when token/messages get lost or not.
<honzaf> if nothing get lost it behaves orderly. If something is lost, it starts resending things and more packets get lost
<illustris> So the answer to the ultimate question of life, the universe, and everything justhappens to be the number of nodes corosync can support on default conf? Interesting...
<honzaf> lol
````

### Someone is not taking his meds
````
08:39 < fabbione> that said.. i think, we our approach, we can change onwire at any 
                  time
08:39 < fabbione> even mid release
08:39 < fabbione> as long as we don´t bump +2 within the same major release
08:39 < chrissie> I think the RHEL overlords would be unimpressed with that
08:40 < fabbione> it doesn´t matter the slightest if it´s a config option
08:40 < fabbione> as long as we don´t break compat
08:40 < fabbione> and maybe we can support X to X+2 or even X+3
08:40 < chrissie> NURSE - HE'S OUT OF BED AGAIN!
````

### Fabio is super
````
10:50 < fabbione> I clogged CI :)
10:50 < chrissie> congratulations
10:50 < chrissie> call a plumber!
10:51  * fabbione dresses as Mario Bro
10:51 < chrissie> ROFL
````

### Who's the weakest link?
````
13:51 < chrissie> honzaf: I suppose if there's a node running the old corosync then 
                  crypto reload should be disabled
13:52 < chrissie> otherwise it's going to be removed from the cluster anyway!
13:52 < fabbione> "you forgot to update your corosync. GOODBYE!"
13:52 < chrissie> lol
13:52 < fabbione> that's worse than a MS licence expiration warning
````

### hold it
```
15:39 < fabbione> hmmm why is covscan failing?
15:39 < fabbione> it shouldn´t
15:40 < chrissie> you didn't breathe on it did you?
15:40 < fabbione> LOL
````

### It's not a game (or is it?)
```
13:24 < chrissie> Ok, proved that the new code has no impact on the knet manpages
13:27 < fabbione> nice :)
13:31 < chrissie> but feel free to add @notes :)
13:56 < fabbione> was not planning to :)
13:56 < fabbione> @notes GET A LIFE INSTEAD OF PLAYING KNET 3D
13:57 < chrissie> lol
13:57 < chrissie> I need to get a life and stop playing doxygen2man 2D
13:57 < chrissie> it's curiously compelling
13:57 < fabbione> ROFL
````

### You don't act like a scientist, you're more like a game show host
```
11:17 < fabbione> i am going back to the first patch and debug from there.....
11:18 < fabbione> crypto is witch hunting anyway
11:19 < chrissie> almost ghost hunting
11:19 < chrissie> who ya gonna call?
11:19 < fabbione> GHOSTBUSTERS!!!!!
````
![alt text](https://raw.githubusercontent.com/ClusterLabs/high-laughability/master/pictures/Cryptobusters.png "Cryptobusters")

### it´s all in your mind

```
09:40 < chrissie> This just gets wierder. If I build libqb & corosync in mock then they work. so it seems to be environmental - with the emphasis on MENTAL
```

### What HA is not

```
13:28 < fabbione_prepto> unless you are really scared that some sysadmin can mingle with it
13:29 < cedric> fabbione_prepto: :) ""unless you are really scared that some sysadmin can mingle
                with it"" ... murphy's law! ;)
13:29 < fabbione_prepto> it's the same as rm -rf /
13:30 < fabbione_prepto> at somepoint, somebody, will expect pacemaker to intercept that
13:30 < fabbione_prepto> i can provide HA
13:30 < chrissie> hehe
13:30 < fabbione_prepto> i can't fix your fingers or the engine that is supposed to move them
13:30 < chrissie> We are selling High Availability, not Low Stupidity :P
```


### FF (fabbione facts)

```
09:38 < fabbione> sorry but I only have today and tomorrow left
09:38 < fabbione> i'd like for a change to have 2 days off for real this time :)
09:38 < fabbione> and yes i do take pto once in a while too :D
09:38 < chrissie> good!
09:38 < fabbione> somebody said the other day
09:39 < fabbione> ""yeah it's 9pm and fabbione is around""
09:39 < fabbione> ""fabbione is around at 9pm on all timezones at once""
09:39 < chrissie> haha
09:40 < jpokorny> we should start ""fabbione facts"" doc to track these
09:41 < jpokorny> FF for short
```

### Hiring Requirements

```
10:00 <@fabbione> to make HA right
10:00 <@fabbione> you need 2 things
10:01 <@fabbione> 1) insanity, big ego, being a bit of an a**
10:01 <@fabbione> 2) lots of whiskey
10:01 <@fabbione> i fit the profile
```

### Are you a magician or something else?

```
<Al Kari> You guys are magicians!  I don't know how you do what you do, but this is great!
<fabbione> It comes from 11 years of being an asshole.
```

### she can be really dangerous

```
<FOO> So BAR, what do you think of this meeting with potential cluster customer?
<BAR> I had to wash the blood out of my hands....

(anonymized to protect her secret identity)
```

### Nordics

```
<fabbione> honzaf: i don't know i can ask one of the veritas developers .. there is one living 10 minutes walk from here
<honzaf> fabbione: really?
<fabbione> yes
<honzaf> cool
<fabbione> he is one of the cluser/kernel core engineers
<fabbione> there must be a relation between cluster developers and nordics
<fabbione> i guess it takes a lot of alcohol to deal with both
```

### Cluster is pure poetry

```
All Hail the single-node cluster! It keeps our deployers unflustered. You may think this is all bluster, but hail the single-node cluster!
```

### The boss has been totally out-smarted

```
10:10 < jkortus> 4pm and almost dark...
10:12 < swhiteho> 3pm and almost dark :-)
10:12 < fabbione> it's dark....
10:12 < fabbione> already
10:12 < fabbione> what do I win? :)
10:12 < chrissie> a light bulb
10:12 < fabbione> ROFL...
10:12 < fabbione> can i quote that?
10:13 < chrissie> You can, but plugging it in might be more useful :P
10:13 < jkortus> hehehe
```

### baseOS and food

```
<customer> Grappa is at the base... just like bind..
```

### corosync.org domain expired

```
05:53 < fabbione> NOTICE: This domain name expired on 04/05/2013 and is pending renewal or deletion.
05:55 < fabbione> honzaf: worst case we can get corosync.xxx .... it's sexy code afterall
05:57 < honzaf> exactly. It also give us great possibility to change dirrection a little bit and make business in XXX. Corosync powered video streming technology, ...
```

### Upgrading vs Stability

```
09:49 < sbradley> fabbione: no worries, i was working with lon on this before you became lon 2.0
09:50 < fabbione> at best I am lon 1,9 Alpha release
09:50 < fabbione> it's hard to be lon GA
09:51 < sbradley> fabbione: i hear that, he was a like a an old punch card computer. YOu say ""lon what is deal with X"" and lon 1.0 will output the answer
09:52 < bob> lonbot
09:53  * sbradley says we need to put lon 1.0 in the Bletchley Park Museum
```

### Product requirements and chemistry

```
< lon> ""implement self fencing""
< lon> ""ok, I rigged up the breeze from the fan to prevent a pile of sodium from falling in to a jar on top of the server, so if the fan shuts off, an explosion occurs on top of the computer, destroying it""
< lon> ""That's self fencing, is that what you wanted?""
```

### excitement over gcc on netbsd

```
[08:28am] fabbione: honzaf: it works! it works!!!!
[08:28am] fabbione: honzaf: i almost lost hope :)
[08:37am] • sbradley is excited but does not know what works now
[08:38am] fabbione: sbradley: gcc on netbsd
[08:38am] honzaf: ;)
[08:38am] • sbradley says ""oh""
[08:38am] fabbione: sbradley: so does corosync btw
[08:38am] sbradley: ah
[08:39am] fabbione: yeah it's a nice cluster of netbsd, openbsd, freebsd and openindiana
```

### config options are not an opinion

```
02:56 < honzaf> version like 0, 1, 2 is also weird
02:56 < honzaf> good for IBM products
02:57 < honzaf> it's like ""open manual on page 4566454568756789 and there you will find explanation""
```

### libqq vs Star Wars

```
tests/check_log.c:603:  qb_log(LOG_INFO, ""Yoda how old are you? - %d"", __LINE__);
```

### Evil Nature

```
09:26 < Madkiss> hello dabio
09:26 < Madkiss> err
09:26 < Madkiss> hello fabbione
09:26 < fabbione> hi Madkiss
09:26 < digimer> dabio? personal pet name? ;)
09:26 < Madkiss> no.
09:26 < Madkiss> tpyo.
09:26 < Madkiss> as in
09:26 < Madkiss> typo.
09:26 < fabbione> i read diablo for a second.....
09:26 < Madkiss> y'know?
09:27 < fabbione> the true evil in e
09:27 < fabbione> me
09:28 < digimer> lol
09:28  * digimer has had so little sleep in the last five days... is in a thoroughly silly mood now.
09:30 -!- ignarps [~M@pdpc/supporter/active/ignarps] has quit [Quit: Leaving]
09:31 -!- palli1 [~palli@pat.ok.is] has quit [Quit: Leaving.]
09:32 < dakini> fabbiablo, the evil that emerges in fabbione when he hasn't had enough coffee
09:32  * dakini is almost always in a silly mood ;)
09:32 < fabbione> ahahaha
09:33 < fabbione> add that to the quotes page :)
09:34 -!- ignarps [~M@pdpc/supporter/active/ignarps] has joined #linux-cluster
09:36 < digimer> as you wish, my lord...
```

### Brain Games

```
[14:31] <fghaas> danfrincu: last I check, having two interface definitions in corosync.conf, without specifying rrp_mode, it would default to none and that would throw a configuration error[14:31] <danfrincu> fghaas: I see, thanks
[14:32] <fghaas> danfrincu: welcome, and grammar mistakes ignore please, me write confused today
[14:33] <beekhof> i thought it was a new encryption scheme
[14:33] <danfrincu> fghaas: you know people only read the first and last letter of a word, so as long as those are correct, peolpe sitll undresatnd what you write
[14:34] <beekhof> is t..t r..y t..e?
[14:34] <danfrincu> yes
[14:34] <beekhof> smartass :)
[14:34] <fghaas> taht is crocert, but it dsone't mkae tnghis esaeir to raed
[14:35] <andreask> depends
[14:35] <fabbione> s...w y.u a.l
[14:35] <bassliner> semes lkie thta's jsut waht i watned to do on a lzay mndoay
[14:36] <danfrincu> fghaas: is that some welch dialect?
[14:36] <fghaas> thanks for chiming in with your world renowned charm fabbione
[14:36] <fabbione> fghaas: it's monday... since hwen i am polite on a monday.... :)
[14:37] <fabbione> first batch of integration tests makes me wish that maya did kick in in 2011 instead of 2012
[14:37] <fghaas> s/monday/$dow/, hardcoding variables is terrible style
[14:37] <danfrincu> for i in ""tuesday wednesday thursday friday saturday sunday"" ; do sed ""s/monday/$i/"" ; done
[14:37] * danfrincu :D
[14:38] <beekhof> fabbione: whatcha testing?
[14:38] <fghaas> danfrincu: I'm sure lge can put a hack around date(1) in there that will make you wet your pants
```

### Experts

```
11:00 < digimer> speaking of specialties, morning to our resident wise-ass. :P
11:01 < danfrincu> fghaas: well, she hasn't blogged about this yet, only about performance tuning 10Gb NIC's
11:01 < danfrincu> fghaas: so I wanted to kinda be on point
11:02 < danfrincu> + what I wanted to suggest isn't all that sane ...
11:02 < fghaas> coming from you I wouldn't have expected it to be :)
11:03 < danfrincu> gee, I'm touched
```

### On self-deprecation...

```
15:30 < digimer}fly> PXE <4
15:30 < glb> I found Andrew Beekhof's tutorial for pacemaker and was trying to follow that.
15:30 < digimer}fly> <3 *
15:30 < beekhof> that guy is an asshole
```

### Wrong priorities.... wrong priorities....

```
08:30 <digimer> ok, I'll file the bed now before going to bug
```

### #linux-ha? No, this is Madness!

```
17:53 < lge> beekhof: just for fun, cibadmin -Q in bash:
17:53 < lge> mkdir dont-try-this-at-production
17:53 < lge> cd dont-try-this-at-production/
17:53 < lge> mkfifo in out
17:53 < lge> nc -q1 -U /var/run/crm/cib_callback <in >out &
17:53 < lge> (while read f; do [[ $f = ""(1)cib_calldata=""* ]] || continue; x=${f#""(1)cib_calldata=""}; echo ""$x"" | base64 -d | bunzip2| xmllint --format - > cib.xml && break; done ) <out &
17:53 < lge> Q=$'>>>\n__name__=cib_command\nt=cib\ncib_op=cib_query\n<<<\n'; l=$[${#Q} +1 ]; (printf ""%02x %02x 00 00 cd ab 00 00"" $[l & 0xff] $[(l >> 8) & 0xff]  | xxd -p -r ; printf ""%s\x00"" ""$Q"" )
             >in
17:53 < lge> wait
17:53 < lge> cat cib.xml
17:53  * lge runs and hides
17:54 < beekhof> wtf is wrong with you?  :)
```

### Sith Lord

```
14:16 < russellb> sdake: what kind of phone are you on
14:16 < russellb> i can't understand a word
14:17 < fabbione> he is wearing Darth Vader helmet
14:17 < bob> fabbione: lol...Dake Vader!
14:19 < bob> ""I find your lack of faith in corosync disturbing.""
```


### military ranks

```
(14:23:29) lmb: Some of the conversation of this channel reminds me of a Captain Obvious versus Sergeant Sarcastic death match
(14:26:02) fghaas: lmb, who would you be? Admiral Arrogant?
(14:26:56) lmb: fghaas: I don't want your title, I'd be happy with Colonel Cynic ;-)
(14:27:34) Slydder: great. I knew I shouldn't have bothered answering. now I get added to one of the strange irc chat log comedy sites. grrrr.
(14:28:07) ***danfrincu all we miss now is a General Grievous to take the chain of command by the horns
```

### new unmanned coffee´ly weapons

```
(13:35:00) Slydder: great. now my config is wrong. seems the params for pingd have changed as well as a few other things.
(13:38:21) Slydder: fghaas: so now pingd is just a fire and forget with no real control.
(14:18:58) fghaas: fghaas: pingd is not a guided missile; care to elaborate?
(14:19:11) ***fghaas clearly hasn't had enough coffee today
(14:19:18) ***danfrincu clearly
(14:19:19) fghaas: Slydder: pingd is not a guided missile; care to elaborate
(14:20:00) Slydder: Slydder: forgot about the trailing d
(14:20:34) ***Slydder forgot about the trailing d
(14:20:44) ***Slydder also forgot about /me slon Slydder
(14:20:50) fghaas: want some of my coffee Slydder?
(14:20:59) Slydder: just got a cup.
(14:21:20) Slydder: my boss made it. so it's strong enough to float horse sh**
```

### New HA solutions

```
14:05 < fabbione> ""I placed 2 servers one next to the other.. one is running Centos 5 and the other Gentoo... why don't they cluster themselves? they share a common UPS!""
[http://www.fabbione.net/Futurama-Farnsworth-IDontWantToLiveOnThisPlanetAnymore.png how users make me feel]
```

### Some never forgive

```
from #linux-ha
06:03 < fghaas> yeah, where is lmb come to think of it?
06:04 < danfrincu> sharpening his katana probably
06:04 < danfrincu> for when someone says o/
06:04 < tserong> stateside
06:04 < tserong> not sure if he's armed ATM
06:05 < fghaas> I think they've disliked armed germans over there since about '41
```

### From the depths of #drbd

```
16:24 < digimer> the sun, it burns!
16:24 < Patrickdk> but really, need something more flexable than lvm/ext
16:25 < Patrickdk> fghaas, hmm, sun is dead
16:25  * digimer likes the victorian hue geek skin has
16:25  * Patrickdk would make a good mirror
16:25 < Patrickdk> not currently though, wife forced me to like every themepark in the east coast this summer :(
16:26 < fghaas> ""victorian hue"" ... anyone ever anticipate to read those words in a freenode channel?
16:26 < Patrickdk> victorians scare me
16:26 < fghaas> I must concede, m'dear, I am marvelously delighted
16:26 < Patrickdk> no idea how they don't get heat stroke in the summer, or even in the fall
16:26 < digimer> :D
16:27 < TrevorH1> they only went in for black in a big way after albert died and the old biddy went into 40 years of mourning
16:28  * digimer is wondering just what the hell can has been opened...
16:28 < Patrickdk> I mean the whole, we won't show any flesh, except our cheeks, the rest of the body will be completely covered up, and sealed shut
16:29 < fghaas> digimer: /nick pandora
16:29 < fghaas> too bad fabbione isn't here to record
```

### Useless attempt to save a picciotto

```
09:37 < fabbione> cmaiolino: be careful... you start hacking on anything that is cluster related and all of a sudden you wake up in a mental hospital ;)
09:37 < fabbione> cmaiolino: you are still in time.. save your soul!
09:38 < bob> Not to mention the occasional horse-head you find in your bed when you wake up.  ;7)
09:38 < cmaiolino> bob: Did you get it from The Godfather?
09:39 < bob> No, from FedEx!  ;7)
09:39 < cmaiolino> lol, hacking++ hopefuly I can do something useful at the same time I learn
09:39 < fabbione> ROFL
09:39 < cmaiolino> bob: FedEx?
09:39 < cmaiolino> I really have seen it on The Godfather, but on FedEx???? lol
09:39 < bob> special delivery.
```

### I hope so too

```
11:49 <bossdog> Hi lon , hope I'm not disturbing
```

### Nothing lasts forever

```
10:02 < lon> fabbione: that's the first API addition to libcman in like 7 years
10:03 < lon> it makes quorum devices the most dynamic ""member"" of the cluster :o
```

### Patience young padowan

```
10:10 Guest34393: is the first time I use irc. danfrincu what would you recommend?
10:11 ***danfrincu recommends patience on IRC :)
```

### On Success Return Wisecrack

```
23:50  * digimer now has a fully HA network config for her cluster. :D
23:51 < sdake> cool what was the trick
23:51 < sdake> rm -rf corosync ? ;-)
```

### The Master Fails His Own Lesson

```
12:14 -!- russellb is now known as keyboard-pwnage
12:28 < digimer> keyboard-pwnage: I'm guessing there is an interesting story behind that nick change
13:52 -!- keyboard-pwnage is now known as russellb
13:52 < russellb> digimer: Ha, my friendly coworkers visiting from Canada keep screwing with me when I leave my office.  :-)
13:53 < russellb> I used to be able to trust everyone around here ... *looks around suspiciously*
13:53 < digimer> canadians can never be trusted.
13:53 < digimer> ever.
13:53 < russellb> agreed
13:59 -!- leifmadsen [~Leif@asterisk/documenteur-extraordinaire/blitzrage] has joined #linux-cluster
13:59 < russellb> leifmadsen: <---- EVIL CANADIAN NICK CHANGER
14:54 -!- leifmadsen is now known as I_Eat_Babies
15:09 -!- I_Eat_Babies is now known as leifmadsen
15:19 < digimer> russellb: was that you getting some sweet revenge on leifmadsen?
15:19 < leifmadsen> digimer: it was ;)
15:19 < digimer> ++ if so. :P
15:19 < leifmadsen> I went to the washroom, and I did not learn from my own teachings
```

### Cisco <3

```
11:21 < fabbione> hsrp -> Ho(s)t Standby Rout(er|ing) Protocol
11:21 < fabbione> like a virtual ip moving very fast between 2 routers
11:27 < digimer> ah, sounds neat
11:28 < fabbione> no it's not neat.. it's proprietary cisco protocol
11:29 < fabbione> fghaas: i have too much experience with Cisco.... i wish i could forget
11:29 < pyco> :(
11:30 < pyco> silence!
11:30 < fabbione> cisco support: ""Yes you need to try this release x.y.z.... to address that bug""
11:30 < fabbione> me: ""but it's not available for download.. i can't find it on CCO""
11:30 < fabbione> cisco support: ""DO YOU WANT TO GIMME 2 MORE MINUTES TO FINISH THE BUILD?""
11:30 < pyco> hahahaha :D
11:30 < fabbione> me: ""so much for QA/QE...""
11:31 < fabbione> this IOS going on a core production router.....
11:37 < fabbione> ""A reboot a day, keeps the Cisco TAC away""
```

### end of the world and fairy princesses

```
11:59 < lmb> it's a bloody nuisance
11:59 < fabbione> it's fine grained control to pave the way of user insanity
11:59 < fabbione> oh wait.. users are already insane... nevermind
12:00 < lmb> nonono, users are just stupid, developers are insane
12:00 < fabbione> i guess that's a way to look at it :D
12:02 -!- rascasoft [~rascasoft@78.4.107.99] has left #linux-cluster []
12:06 < e_> now you've offended that user
12:06 < e_> i hope you are ashamed of yourselves
12:10 < e_> hehe
12:21 < lmb> e_: Of course I'm ashamed of fabbione, whom do you take me for!
13:12 < fabbione> lmb: e_ wrote ""yourselves"" plural.. ok I am big and all.. but rarely can be confused for 2 people ;)
13:12 < fabbione> i doubt there is even enough space for 2 of me in the same universe (mass wise) ;)
13:18 < DanFrincu> fabbione: :))
13:18 < e_> he heh..
13:18 < DanFrincu> don't go supernova on us now ;)
13:21 < fabbione> only in 2012... need to be patience for the end of the world
13:22 < beko> end? reboot!
13:23 < DanFrincu> fabbione: ah, and how is it going to SIGSEGV, planet nibiru comes along and shifts the magnetic poles, aliens take over the planet, any chance of happy ending ? :D
13:25 < fabbione> DanFrincu: we will all be living in a beautiful garden dressed as fairy princesses covered in flowers.....
13:26 < DanFrincu> ah crap
13:26 < DanFrincu> just had a mental picture of me dressed as a fairy princess
13:27  * DanFrincu rofl
13:28 < beko> pics or it did not happen :>
13:31 < fabbione> http://tinyurl.com/3juv3tu
13:31 < fabbione> beko: does this one count?
13:31 < beko> aw so cute
```

### no s**t

```
15:17 < hetii> process of setting cluster is a painfull
15:18 < fghaas> hetii: water is wet!
```

### god or nuclear power?

```
15:36 < sdake> anything is possible in software
15:37 < fghaas> the definition of ""possible"" is ""feasible while maintaining economic viability"", otherwise it would be ""possible"" to heat your home with a hydrogen bomb
```

### politics takes cpu power

```
09:31 < chrissie> ""sdake takes 100% CPU' would be about you
09:32 < sdake> sdake does take 100% cpu
09:32 < chrissie> and quite impressive
09:32 < sdake> i spin 24/7
09:32 < chrissie> ah, you're in the government ?
```

### are you sure they are your kids?

```
09:30 < sdake> the only things relating to me are snide comments
09:31 < sdake> ""corosync takes 100% cpu""
09:31 < sdake> ""corosync takes 100% cpu when dong ring recovery""
09:31 < sdake> etc
09:31 < chrissie> to be fair that's not about you ... just about your progeny
09:31 < sdake> my kids aren't ugly damnit!
```

### Burning sensation

```
14:45 < fghaas> yaaaaaaaaaaaay. as soon as I start my second node with RR recovery enabled, CPU is 100% on both nodes
14:54 < fghaas> I do have to concede a configuration error was involved as well (no ip address available in configured bindnet), but still...
14:57 < fghaas> oh wow. mine eyes've seen the glory o' the coming o' the lord
14:57 < tserong> fghaas, it was clearly just trying really, really, really hard to find an ip address
14:57 < fghaas> I just saw ring recovery happen before my very eyes
14:57 < fabbione> ahahha
14:57 < fghaas> after being told for three years straight it wasn't possible nor needed
14:58 < fabbione> fghaas: you're lucky.. the first people that witnessed that had their eyes bursting in flames!
14:58 < fghaas> what's that burning sensation I'm feeling in my head?
14:58 < fghaas> I ... I ... I can't see!!!!
```

### Feature Set

```
20:58 < asalkeld> beekhof, how do I come up with crm_feature_set?
20:59 < beekhof> cat /dev/random
```

### fence with a rusty spoon

```
09:36 < verwilst> can i fence my dual server drbd setup with iptables? :D
09:38 < fghaas> verwilst: can you scoop your eyes out with a rusty spoon? sure you can, but the experience will be painful and it'll be unlikely to help you achieve any significant goal
09:40 < aypea[0]> well, (s)he'll have shown themselves to be an individual of great testicular fortitude...
09:41 < fghaas> aypea[0]: I believe ""testicular fortitude"" biologically excludes the (s) before he
```

### bad eating habits ===

```
tserong: speaking of kids, a former coworker's wife just gave birth to twins a couple weeks ago.
***tserong predicts not fun
fghaas: tserong: the wife of a former coworker, or the former wife of a current coworker? I love the english language's proneness to ambiguity
tserong: ""current wife of a former coworker""
fghaas: I see
[...]
tserong: we ship dlm_controld.pcmk in libdlm.rpm - sorry can't comment on specifics (busy, having guests over for dinner)
tserong: (guests are coming over and we will eat dinner with them, not we will be eating guests when they arrive, before you ask, fghaas)
fghaas: :D
```

### it´s all about first time IMPRESSion

```
19:13 < digimer> fabbione: I can't open that file for some reason
.. time passes ..
19:16 < digimer> impress wasn't install. >_<
19:16 < digimer> got it open now
19:16 < digimer> Madkiss: o/
19:16 < digimer> <- alledged documentor, nice to meet you
```

### cluster is all about documentation

```
***fghaas recommends that tuxick read the ""dual primary: think twice"" tech guide before proceeding
***womble heads off to write the ""Cluster filesystems: drink heavily"" tech guide
```

### Perfect engineering problem solving

```
* fabbione didn't start a good day
04:49 < digimer> more coffee
04:49 < digimer> seriously, it fixes everything
04:49 < fabbione> i just started with coffe...
04:49 < fabbione> it's 4:30am
04:49 < digimer> another
04:49 < digimer> one for each hand
04:49 < fabbione> can I finish the first one first? :D
04:50 < digimer> you can't solve problems with a coffee in either hand, thus, problems don't exist whilst coffees exist.
04:50 < digimer> My logic is flawless
```

### in `God^WDRBD` we trust

```
atarakt: I knows, but my boss do not want to use drbd, for him it's to risky
atarakt: so, I have to find an other solution
fghaas: sure it's awfully risky, it's been in production for about 10 years and it's in mainline
atarakt: I know that, it was my first choice
fghaas: where's the risk then? dilbert boss?
... almost 9 minutes later ...
atarakt: ok, thanks
```

### time to face your worst nightmare?

```
< digimer> fghaas: o/
< fghaas> digimer, please stop typing o/ -- I always picture lmb with his katana chopping someone's head off when I see that
```

### Perry on fear of bonding

```
< pmyers> please get a failure scenario from them
< pmyers> that we can address
< pmyers> i can't address 'fears' but I can address failure scenarios :)
```

### plans and food

```
< aypea[0]> hmm. i am armed with a cunning plan and a sandwich. tomorrow. is a good day to die.
```

### Lars explanation of Linux HA Clusters and actually sticking to the requirements

```
yang: is linux ha about having webserver deployed over multiple hosts for redundancy?
lmb: yang: no
lmb: or, well, rather, not just that
yang: wgat is it about in two sentences
lmb: About clustering several Linux systems to provide high-availability for services
lmb: I recommend google
```

### Tim finally figured it out

```
tserong: note to self: read before speaking
rasto: what a nonsense
```

### Lazy Robots

```
beekhof: how do i disallow everything with .rpm ?
fghaas: %postinst
fghaas: rm * -f /
fghaas: will disallow pretty much everything on that machine
beekhof: smartass
fghaas: care to rephrase the question?
beekhof:  /*.php$
fghaas: you mean, how do you disallow access to all files ending in "".rpm"", in a robots.txt???
beekhof: yes, and i found the answer
beekhof: i was being lazy
```

### anonymous and fictitious

```
15:04 <XXXXXX> ""why I love corosync to use 100% cpu, cause then at least I know it ain't dead""?
```

### Lawyers and fence agents

```
10:15 < lon> in the same way that ""suicide"" is legally not ""murder"", ""watchdog"" is not ""Fencing""
```

### Scary thoughts

```
13:22 < lmb> fabbione: I can figure it out, but I think there's some massive
             complexity issues being glossed over, and striving to get all that
             in ~10kloc is, uhm, beyond my cynical horizon
13:29 < chrissie> anything that's beyond lmb's cynicism is something I don't
                  want to contemplate
```


### Fabio learns some maths

```
13:50 < fabbione> NOTE TO SELF: 8 cores are not enough to handle 256 VMs
```

### Universal truth about clusters

```
08:46 < pmyers> ""For HA purposes don't power off all of your cluster nodes at the same time, if you do that you'll lose all of your services"" :)
```

### THE mob is growing

```
10:13 < chrissie> ""it would be a shame to see anything happen to your cluster now, wouldn't it ... ?""
```

### We are honest people

```
09:01 < chrissie> you might as well replace it with a script that does ""echo your config file looks OK, I think. To be honest I didn't look that closely""
```

### Linux is full of Zombies

```
13:09 < fabbione> http://fedoraproject.org/wiki/PackageMaintainers/PackageEndOfLife
13:10 < pmyers> fabbione: thx
13:10 < fabbione> i'll need to figure out how to revert that process for rgmanager :)
13:11 < pmyers> lol
13:11 < pmyers> rgmanager will be undead
13:11 < pmyers> we killed it and it came back
13:11  * pmyers gets his silver and garlic
13:11 < fabbione> and it will have to die again
13:11 < pmyers> ROFL
```

### Only toys for boys have 100% uptime

```
15:22 < chrissie> all my VMs on the noisy box are 1G
15:23 < chrissie> noisy one is switched off at the moment
15:24 < chrissie> I know you have a problem with concept of a computer that's switched off ... I'll explain if necessary ;-)
```

### Lon uncovers a plot ... we think

```
14:53 < lon> No... it means that fabbione and beekhof have been secretly
             plotting for some time.  beekhof takes the hooves for cluster-glue
             and fabbione takes the heads to deposit in our beds.
14:54  * beekhof barfs
```

### We're not sure that Fabio is totally on-message

```
14:50 < fabbione> chrissie: it doesn't bother me that the cluster doesn't start
```

### Andrew on rawhide & the Plague

```
08:07 < beekhof> omg! i think i just got rawhide to install
08:07 < chrissie> :)
08:07  * beekhof might erect a plague to honor the moment
```

### Lars on SELinux

```
08:07 < chrissie> ivoks: have you checked SELinux ?
08:07 < chrissie> lol
08:08 < ivoks> chrissie: i don't have selinux
08:08 < lmb> be careful, selinux is a STD and might interfere with regular operation
8:08 < lmb> (Security Targeted Development, not what _you_ were thinking)
```

### warm and fencing

```
09:46 < fabbione> it's so incredibly warm here today
09:47 < chrissie> yes it's very humid here
09:47 < chrissie> I have a guy coming to put up a new fence
09:47 < chrissie> so with any luck he'll get his shirt off :P
09:49 < fabbione> ahhaha
09:49 < fabbione> <g>bad girl</g> ;)
09:50 < chrissie> tee hee
09:51 < chrissie> it could be the first time that I find fencing interesting ;-)
```

### Steve celebrates national poetry week ... buy AndyP is unimpressed

```
08:57  * swhiteho gently tiptoes around the great tip git tree
08:58 < swhiteho> (say that quickly 10 times!)
08:58 < AndyP> that quickly 10 times
08:58 < AndyP> :)
08:58 < swhiteho> theres always one :-)
09:01 < swhiteho>  ...when all at once I saw a crowd, a host of golden tracing
                  patches
```

### gfs upstream on gfs hangs

```
17:52 < dct> no, gfs hanging is very very common
17:54 < bob_home> I don't think gfs hanging is common at all.  It's just that we tend to hear about it when it happens.
```

### leak here.. leak there

```
19:08 < sunilm> naah... it's userspace... kill the app and let the kernel clean up your leaks ;)
```

### to rabbit or not to rabbit

```
15:34  * lon just got 3 hours a week of his life back
15:34  * lon puts on a rabbit costume and hops around
15:34  * rpeterso tries to think of a snappy come-back.
15:34  * fabbione quotes all of the above...
15:35  * rpeterso wonders if lon's three hours was time feeding his horses.    ;7)
```

### fence_mafia

```
< jparsons> When those two (godfather and fabbione) arrange for a node to leave a cluster, they don't just evict the node - they send 408V to the  node, and make it look like an accident!
```
[fence fail 1](pictures/fence_fail1.jpg) | [fence fail 2](pictures/fence_fail2.jpg)

### Helpful hints on choosing a source code management system

```
< chrissie> In a short phrase: ""git was written by an autistic sadist who
            couldn't design a user interface for a stapler""
* chrissie feels better for that
```

### American Paranoia

```
<lon> Can we drink a beer outside on the street?
<honza> yes of course
<lon> Are you kidding me?
<honza> no
<lon> Are you sure?
<honza> We don't have Big Brother here on the streets
```

### riley talks about being ill

```
16:19 < riley_dt> sorry missed meeting guys i was pretty ill last night and the
                  day before
16:19 < riley_dt> feeling a little better now
16:19 < lon> glad to hear you're feeling better!
16:19 < riley_dt> not feeling better just a little better :)
16:19 < lon> well
16:19 < lon> when you're at the bottom...
16:19 < lon> nowhere to go but up
16:19 < riley_dt> explosion at both ends has stopped
```

### glocks...

```
12:04 < swhiteho> how many glocks would a glock doc doc, ifa glock doc could doc glocks?
12:04 < swhiteho> (now repeat it faster...)
```

### to wall or not to wall?

```
09:47  * chrissie looks for something else to do other than ldap
09:47 < beekhof> head + wall + repeat ? :)
09:48 < fabbione> chrissie: do you feel like playing with strings?
09:48 < fabbione> (static buffers, no malloc)
09:48 < beekhof> thats just cruel
09:49 < beekhof> at least my way one has unconsciousness to look forward to
09:53 < chrissie> fabbione: try me ...
09:58 < fabbione> chrissie: specially in the xmllite code.. we need a better tokenizer for xml queries and do some sanity checks
09:59 < chrissie> hmm, so I have a choice between a parser & a ldap
09:59 < chrissie> suddenly this wall looks very appealing ;)
```

### stdaro shares his wisdom about Lustre

```
16:38 < lon> I think they are using Lustre for the root file system
16:38 < lucianodrosda> Thank you for helping me!!! Good evening for you (here
                       are 17:40)! =)
16:38 < lon> good night =)
16:38 < stdaro> good luck :)
16:39 < lon> stdaro: wow, says they have process migration working on openssi
             now :o
16:39 < stdaro> lustre is scary enough by itself, root on lustre is like an HPC
                Friday the 13th meets nightmare on elm street
```

### when you discover you are a lord, is too late

```
Date: Thu, 27 Mar 2008 11:43:43 -0400
From: jim parsons
To: fabbione

Hello sir,
```

### Branches and BDSM.. the missing link

```
19:21 < lon> nah, it's not hard to track them all ;)
19:22 < fabbione> lon: can i quote that? :)))))
19:23 < fabbione> the next one that's going to miss a git push to stable2, i will cross burn him alive with that printed on top of the cross in place of I.N.R.I. ... like Jesus
19:23 < lon> I don't think that's a function of my cvs/git usage, however.  I think it's because I forget about them all the
             time, and I need someone like you to whip me every time I forget.
19:23  * fabbione is already dressed in black leather
```
