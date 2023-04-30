# TW_Auto_Karma
Automatic fill of Karma bot 

There are 2 approaches.
  1) One uses TWAAP - an old, well known adobe air desktop application to extract your mass planner.
     - Doing a **simple export**
     - Paste the results in _initial_plan.txt_
     - Run _TWAAP TO JSON_v0_7 test.ipynb_ 
     - A text file will pop up, with the equivalent planner in json format.
     - Import this to Karma bot and your plan is ready to be executed.
  2) The other uses https://devilicious.dev/ to export the initial file.
     - Once you have your planner as indicated in the [picture](https://github.com/GioPetro/TW_Auto_Karma/blob/main/devilicious%20formats.png)
     - Paste the results in _initial_plan.txt_
     - Run _Devillicious TO JSON_v1_2.ipynb_
     - A text file will pop up, with the equivalent planner in json format.
     - Import this to Karma bot and your plan is ready to be executed.
<br>
The latter approach is much more recent, as such I have added a few attributes extra, as seen within the code. Any information about the server, world and land time of the plan, are simple string variables inside the notebook. There is not any kind of UI as I find it unnecessary - it's not for comercial use.
<br>
Of course, this requires Karma installed, which is not my property to share.
<br> Keep in mind, the game does not allow such mechanisms, therefore the risk of **getting banned** with severe in-game penalties are always a possibility.
<br> It's something I've created for fun, parsing through some input to get a desired output.

