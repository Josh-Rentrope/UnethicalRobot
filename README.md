# UnethicalRobot
A project to show good code design patterns and practices in Unreal.

The quick setup is to download UE 5.6+, clone this repo (or unzip a zip from the [releases page](https://github.com/Josh-Rentrope/UnethicalRobot/tags)), open the UnethicalRobot.uproject at the root of the project, and then open the MainLevel.umap. 

The game mode should be set to "FunctionalGameTestMode", as the controller and pawn that spawns will have most of the functionality needed.

Inside is a demo of a minimal game that allows you to interact with a RobotActor. Each limb gets a component created that will allow a player to highlight the mesh. 

Certain meshes can also be flagged as detachable, which will allow a user to click and drag on the part to move it.

There are comments in the code with minimal coupling to allow for easy modifications.
