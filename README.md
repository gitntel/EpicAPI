# Latest edit:
* I've made some files with appropriate names to clean all the code
This is a shitty file i put together that does stupid things

To run this, run EpicData.py
and follow what it says, unfortunately I don’t have a working Auth that I can add to my EpicData.py file so, you have to do it manually IK it sucks I’ve looked into it but if you know how to fix it please dm me or open a pull request!
The Problem:

    I can’t seem to figure out how Epic knows your logged in, I’m assuming it’s a cookie, but I don’t know witch one

Description oon what this does:

    It will give you the news from the Website for Fortnite
    It will give you Free Games that Epic is giving away!
    It will give you SAC data for e.g FortniteDATA.GetSACinfo(Code="Tfue") #Returns the account name that the Code belongs too in this case: Tfue
    It will give you Challenge data with FortniteDATA.Challenges.Get_Challenges(Week="3")
    Added some Third Parties partially because my auth won’t work.

Also thanks to This Nils#0001 You can use a replay parser,. :I’m still testing this but as a test do ReplayData.GetReplayData()
Tested functions:

from EpicTest import *
#GetEpicData.Get_News()

ReplayData.GetReplayData()

GetEpicData.GET_WEBSITE_FN_NEWS()
GetEpicData.Get_Free_Game_Info()

FortniteDATA.Challenges.Get_Challenges(Week="3") #Returns the challenges for week# e.g: 4
FortniteDATA.Get_Ingame_News()
FortniteDATA.GetSACinfo(Code="Tfue") #Returns data for the inserted parameter
FortniteDATA.GetFNVersion()

Stats.GetPlayerStats(PlayerName="Ninja")

Redeem_Code(code="Jaws")
