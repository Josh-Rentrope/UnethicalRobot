# UnethicalRobot
A project to show good code design patterns and practices in Unreal.

The quick setup is to download UE 5.6+, clone this repo (or unzip a zip from the [releases page](https://github.com/Josh-Rentrope/UnethicalRobot/tags)), open the UnethicalRobot.uproject at the root of the project, and then open the MainLevel.umap. 

There's also a [precompiled build](https://github.com/Josh-Rentrope/UnethicalRobot/releases/tag/v2.1.0) if you've already seen the source code, and would just like to try the latest revision


The game mode should now be set to "CustomGameMode", using the overriden Pawn and Controller.

For unit tests, you can go to "Tools > Session Frontent"
In the Seesion Frontent window, clicking on the Automation tab will bring up unit tests that can be run.

For this project, we built a test called "BP_UnitTest" which can be searched or accessed in "Project > Functional Tests > TestLevel > BP_UnitTest"
Hitting the play button will run these tests

## Changes from v1 to v2
There are a few fixes to the Limb attachment, mostly due to how the pawn actuates its movement. Most of the code around
UI has also been upgraded to be more accessible. Showing controls and statuses.

## What is this?
Inside is a demo of a minimal game that allows you to interact with a RobotActor. Each limb gets a component created that will allow a player to highlight the mesh. 

Certain meshes can also be flagged as detachable, which will allow a user to click and drag on the part to move it.

There are comments in the code with minimal coupling to allow for easy modifications.
