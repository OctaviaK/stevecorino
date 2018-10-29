---
title: NASA's Long Dead 'Photo' Satellite is Alive
date: 2018-9-09 10:00:00
category: Riddles In The Sky
---

![](/images/8.jpg)

Over the past week the station has been focused on an S-band scan looking for new targets and refreshing the frequency list, triggered by the latest launch of the mysterious ZUMA objective. This tends to be a semi-annual activity as it can eat up a whole lot of observing information despite having much of the data gathering automated the info reviewing is tedious.

<!-- more -->

Upon reviewing the info from January 20, 2018, I noticed a curve regular with an satellite in High Earth Orbit (HEO) on 2275.905MHz, darn not ZUMA. This is simply not uncommon during these searches. Therefore, I set to work to recognize the source.

A quick identity scan using 'strf'(sat tools rf) revealed the signal to result from 2000-017A, 26113, known as IMAGE.

## IMAGE 'Found in Space!'

UPDATE: January 26, 2018 - NASA Confirms Photograph is indeed alive!
From Richard (GSFC):

Engineers at GSFC experience acquired the suspect S-band source using the 4m CTA (Compatibility Check Antenna) at GSFC (.jpg attached no I'M not in the picture). They obtained the signal as the focus on was on ascent at about 2RE. Center regularity (CF) was between 2272.478 and 2273.418. The difference between Photograph documented CF of 2272.5Mhz can be attributed to expected Doppler. Subcarriers will be visible as well 1.7Mhz from CF needlessly to say. The signal durability was oscillating. Plots will become forthcoming. The oscillation isn't unexpected given IMAGE's lack of spin balance.

All indications so far suggest that is, actually, IMAGE.

### IMAGE Calling Residence, is Anyone Listening?

I didn't think of it a lot more and went about my data review seeking for any evidence of ZUMA. But as I examined another chunk of spectrum a lttle bit lower in frequency I was greeted by a much more robust carrier and what were data side bands.

The above images shows the data (+ 1.7MHz) near the top of the plot and the carrier devoted to 2270.505MHz in the lower end of the plot, there is also a data part band at -1.7MHz, not shown for clarity. With a properly equipped surface station, telemetry would definitely be possible to backup.

CLARIFICATION, January 25, 2018 - To greatly help clarify the data part band observations please examine the photo below while the classified STSS Demo 2, [2009-052B, 35938], mission in low earth orbit (LEO) also offers a data area band on or about IMAGE's. Note the longer duration of the IMAGE data area band corresponding to optimum elevation and closest method of my surface station vs. the comparatively simple one from STSS Demo 2. This can even be observed in the plot above but just isn't that clear no identification of the indicators was presented.

Just what exactly was IMAGE? I did so just a little Googling and found out that it turned out 'Shed in Space' since December 18, 2005 after only dropping off the grid all of the sudden. The mission was made to photograph the magnetosphere, additional information about that are available in the press kit.

NASA considered the spacecraft a total loss because of a style flaw that manifested while the spacecraft was in its extended objective. The NASA inability review did nevertheless conclude that it had been easy for the spacecraft to come to be revived by permitting a 'transponder SSPC reset' after it exceeded through eclipse in 2007. One must believe that didn't occur in 2007 and they gave up.

## IMAGE Even now Spinning Near Operational Value

Hence with an undead satellite television to monitor, I used the duty of collecting more info about it and allow system carry on without me found in the seek out ZUMA for a few hours. Based on facts in the NASA inability article and eoPortal the nominal spin amount of the spacecraft was observed as around 0.5 rpm that's a period around 120 seconds. By monitoring with my real-period receiver (observe below) I could notice both a delicate period in the transmission amplitude and frequency that were coincident.

### IMAGE Doppler Data Complements SpaceTrack TLE

As your day progressed the Doppler info made it crystal clear this is the lost IMAGE mission.

A fit without performing any in shape capabilities and the curve obviously follows the behaviour of IMAGE's TLE as supplied by SpaceTrack.

### IMAGE Monitor from COSPAR 8049

Below is the monitoring plot from my surface station for the move this data was first collected from. As you can plainly see around 17:17UTC on January 20, 2018 it passed correct overhead of me creating an extraordinary signal in my own omnidirection search antenna.

### IMAGE Basking in sunlight

IMAGE was positioned into an interesting HEO with a 90 degree inclination. Periodically the spacecraft will enter an eclipse and NASA surmised that may result in it to restart and apply electricity back again to the communications program. That appears to have took place!  As you will take note from the plots below sunlight angles are presently best for IMAGE and it could merely stay operational for some time to come.

### IMAGE Reboot?

Like ISEE3 is it feasible for Picture to be rebooted and managed again?  Maybe, since it seems that the primary known reasons for it not calling house before possess resolved themselves at least temporarily.

A few major queries remain about the fitness of the spacecraft:

- What is the condition of the battery made to power IMAGE during eclipse?
- What is the condition of the science payloads? Did the heaters keep doing work while interaction was out?
- Can IMAGE even so accept commands and does it's telemetry help to make any perception? I.e. has long years in the severe space environment damaged the computers and other hardware because of extremes of temperature and radiation?

At the minimum it produced for an interesting Saturday afternoon in the air room.

## IMAGE a Study in Space Salvage Functions?

After creating this blog page and posting it I noted it just appeared to draw the attention of some of my fellow satellite television tracking enthusiasts.

I quickly realized a number of tweets was not going to draw the interest of the people that could take action to see if Photograph could be recovered.  So I have some further exploration and found the contact information for the Photograph principal investor, Dr. James L. Burch, Director at the Southwest Analysis Institute.

Below is a good chronological presentation of most correspondence somewhere between myself and NASA and other folks with primary information.

January 24, 2018
08:38 06:38 UTC - I get in touch with Dr James L. Burch the Photograph principal investigator with reports of my observations.

09:41 UTC - Dr. Burch responds and advises he's 'very excited' and will get back to me with updates.

12:39 UTC - Richard J. Burley, former IMAGE Ground System Supervisor and Mission Director contacts me after staying alerted by Dr. Burch and indicates JSPoC and DSN have already been alerted. He as well confirms my knowledge of the possible failure setting IMAGE experienced.

January 25, 2018
00:13 UTC - Mr. Burley responds to a post I built on Seesat-L and copied to him to the amateur satellite television tracking community to carefully turn their gaze on IMAGE to greatly help collect any details we can to support recovery efforts. He does not have any schedule improvements as the team gets arranged to respond and a wonderful accounts of IMAGE's past successes:

Thank you intended for your entire efforts for Photograph. IMAGE made ~39 different discoveries about the Earth's magnetosphere and plasma-sphere. At the time it halted radiating, NASA HQ rated IMAGE as the next most valuable space-physics objective flying. A follow-on objective named MMS, with a 4-spacecraft constellation happens to be flying, in component, to follow through to these discoveries.

January 26, 2018
16:55 UTC - Mr. Burley reports that engineers at Goddard Space Flight Center (GSFC) have detected a signal regular with IMAGE, below is the workforce of GSFC engineers huddled around their equipment acknowledging the moment with a photo.

18:37 UTC - Mr. Burley and I discuss that I have begun a review of my info archive. I share this details with Dr. Cees Bassa who also offers data archives. NASA does not have any way of being aware of when IMAGE's transmitter started to be energetic again. He provides complex facts on IMAGE's behaviour after reboot:

- 'When the Spacecraft Control Device (SCU) reboots, the s/c clock gets reset to zero. The order watchdog timer is 72 hours. Thus, if it doesn't get yourself a command within 72 hours it'll reboot once again, and reset the clock back to zero again'.

21:12 UTC - Mr. Burley advises two more floor stations have independently verified position and RF qualities of the object believed to be IMAGE.

January 27, 2018
07:59 UTC - I complete an assessment of my info archive and send leads to Mr. Burley, which ultimately shows IMAGE was alive on May 4, 2017

January 30, 2018
NASA officially confirmed IMAGE is the object talked about in this blog.

NASA was waiting to base final confirmation on reception of telemetry.  Once in a position to obtain body lock they decoded the spacecraft ID, 166, which is IMAGE's.

Only 1 way communication was accomplished with the capture of data frames to ensure that analysis of the health of the spacecraft bus can be performed allowing next steps to be planned.

NASA has a lot of hard work ahead of them. They need to get a temporary tracking and control terminal up to carry on with deciding the status of Graphic. Based on the health of Impression they will have to recreate a mission control center from 13 years back, obtain staff and procure funds to transport on with a content recovery extended mission.

One thing is usually for sure, no one ever organized backward compatibility for a mission thought to be dead. Conceivably it is the beginning of a fresh way of thinking about archiving mission equipment and program when failures seem to be to have a possibility of getting recovered in the distant potential. Humanity's potential in space will demand us to take into account compatibility with components that people let slip apart for long periods of time and somehow discovers its way home and also listening for that hardware so we know when wayward missions get back to us.

One key win was NASA's foresight to publish an extremely detailed and honest failure review. For me, it saved Picture. NASA left helpful information to prepare a head to see IMAGE once again.

'In neuro-scientific observation, chance favors the prepared mind'. Pasteur.

I would like to thank the NASA staff that worked to recognize Impression and confirm my observations, the IMAGE workforce because of their overwhelming outpouring of support and enjoyment at the news headlines of the recovery, Dr. James Burch and Richard Burley for believing that an amateur could donate to their wonderful work and go back their lost friend to them.