---
layout: default
title: 
---  


* TOC  
{:toc}  
  

## Project Description

Written in C, records radio stations 24/7. The backend machine records several local over-the-internet stations, keeping 34 minute chunks of overlapping chunks of audio and text archived locally on an 8T hard drive. Each machine also sends a copy of the text in smaller overlapping chunks to the database server for searching by the SE app.


[Repository](https://github.com/hbremers/Radio)

## Project Goals

1.	Make sure the C compiler and all dependencies are up to date, documented and put on github in a timely manner.
2.	Add a new process to monitor all processes and restart them if any of them fail.
3.	When the archive disk is purged of old records, make the DB move the purged record data of the corresponding closed captions records to a new archive table.
4.	Improve speech-to-text. (There will be a 2nd semester team working on this starting in August for both radio & TV.)
5.	Add successful & unsuccessful table/s to capture information about what did/didn't record properly.
6.	Add over-the-air stations.
7.	Add Satellite Radio.










1. 
Fix request service
Work on https://hbremers.github.io/dcWeb/requestservice
put on Digi-Frontend and  put on GITHUB and move from
www.omnis.com
to AWS Amazon Lightsail for
www.digiclisinc.com.
http://www.digiclipsinc.com/requestservice

2. 
Fix Search page http://3.13.169.109:4200/search
- fix log in page
http://3.13.169.109:4200/
Move Accept Terms one space to the right. 

First
put on digi-frontend debug with both Henry and Bob then put on GITHUB then put on AWS Amazon Lightsail
http://3.13.169.109:4200/  

SEARCH
PAGE: http://www.digiclipsinc.com/digiview/DigiClips_Search.htm 

Click
on the report to go to the segment should come out something like this. 

Radio: 
http://www.digiclipsinc.com/digiview/Radio_Image_05.png 

Radio: 
the text you see is speech to text - we need some improvements on this to make it more readable. Plus changing the tape recorder picture to another something different to be able to click on and play the segment.   

Maybe
on this part just make it a general search through the internet instead of our processes data, and then the user can choose to go to the OPTIONS page and become much more specific.   Similar to
www.duckduckgo.com
our own DigiClips browser. 

OPTION
PAGE:
http://www.digiclipsinc.com/digiview/DigiClips_Search_Option.htm

NOTE: 
Delete bottom for Email Alerts

NOTE: 
Make improvements much more user friendly 

3.
Fix reports
like competitors with improvements like these. 

http://www.digiclipsinc.com/digiview/SampleReports_webpage.htm  

Click
on segments and stream the segments the television and radio data has been taken down, there are changes and improvements needed.

Work
on digi-frontend debug put on github then on AWS Amazon Lightsail  

4.
Email Alerts
http://www.digiclipsinc.com/digiview/DigiClips_EmailAlerts.htm

Develop
on digi-frontend test debug then put on GITHUB and put on AWS Amazon Lightsail http://3.13.169.109:4200/emailalerts 

5.
Language Translations

http://www.digiclipsinc.com/digiview/DigiClips_Language_Translator.htm 
needs some work and improvements on the digi-frontend debug test put on GITHUB and then on AWS Amazon Lightsail. 

6.
Data processing
Television – Radio – Newspaper – Magazine – Social Media – Blogs – Web Media - Podcast - Sirius Radio 

Needed
processing of Cable TV Sirusxm Radio Podcasts 

Television
– 1. Closed Caption 2. Speech to Text Stereo Left Channel Right Channel 3. Video Text Recognition 4. Image Recognitions 5. Lip Read To text (NOTE in order of priority to be done). 

Radio
Speech to text with making better readability with spell checker - grammar checker - punctuation checker. Speech to Text Stereo Left Channel Right Channel. 

Television
Radio streamed change at top TABS to

PREVIOUS
SEGMENT - NEXT
SEGMENT - MEDIA
ANALYTICS - EDITOR
- TRANSFER  

Previous
Segment needs to go back to other segments in 10 minute chucks.

Next
Segment needs to go forward to the other segments in 10 minute
chucks.

Media
Analytics goes to Audience Number Hits on Web pages, Media
Values, Publicity Value, Length ( In seconds), Tone Positive Negative Neutral, Graphs and Charts.

Editor: 
For editing both TV (video) and Radio (audio). http://www.digiclipsinc.com/digiview/VideoAudioTextEditorDescription.htm 

DigiTransfer:
For transfer of data similar to www.wetransfer.com
TAB: TRANSFER NOTE:
for now www.digiclipsinc.com/digitransfer
- through http://3.13.169.109:4200/ 

TV
– Radio needs to be with both Video Audio and Text in 10
minute chunked data.

Newspapers
Probably done through
www.duckduckgo.com
Administration to add on more Newspapers. Need to capture and save segments. 

Magazines
Probably done through
www.duckduckgo.com
Administration to add on more Magazines. Need to capture and save segments. 

Social
Media Needs much more work with twitter - youtube - facebook
- linkedin and others probably be done through a customized browser similar to
www.duckduckgo.com
Need to capture streams and save segments.

Blogs
Needs to be created - probably go through
www.duckduckgo.com
develop a browser similar to www.duckduckgo.com
Need to capture and save segments.

Web
Media Needs to be created - probably go through
www.duckduckgo.com
- develop a similar browser to www.duckduckgo.com.
Need to capture and save segments.

Podcast
Needs to be created to capture and process the data. To create reports to go to the segment and edit and download segments.  

Sirius
Radio Needs to be created to capture and process the data.
To create reports to go to the segment and edit and download segments.  

Capturing
downloading streams of Video and audio something similar to this but making it easy and user friendly
https://applian.com/replay-video-capture/ 

Develop
on digi-frontend debug test out put on GITHUB and then put on AWS Amazon Lightsail. 

7. 
Media Analytics 

http://www.digiclipsinc.com/digiview/DigiClips_Media_Analytics.htm

Needs
a little more work - is on Github put on digi-frontend test debug then put on GITHUB and AWS Amazon Lightsail.  TAB – MEDIA
ANALYTICS 

8.
Television Radio Editor 

http://www.digiclipsinc.com/digiview/VideoAudioTextEditorDescription.htm

Needs
to work with the streamed Television and Radio Data with a tab EDITOR. 

Github
put on digi-frontend test debug then put on AWS Amazon Lightsail

TAB
EDITOR 

9.
Transfer of data
like
www.wetransfer.com
make it like www.digiclips/digitransfer 

Through
the tabs from the steamed television and radio segments. TAB TRANSFER

Put
on digi-frontend test debug then put GITHUB and on AWS Amazon Lightsail 

10.
Administration there
are much more needed improvements.  Develop on digi-frontend test and debug put on GITHUB then put on AWS Amazon Lightsail Administration http://3.13.169.109:4000/ 

Develop
put on digi-front – via Chrome Remote test and debug then
put on GITHUB then put on remote AWS Amazon Lightsail
http://3.13.169.109:4200/search
for further testing and debugging. Administration put onhttp://3.13.169.109:4209/.
Then email me at bobshapiro40@gmail.com and hbremers@gmail.com
we will login and test debugging and let you know what needs to be fixed.  
