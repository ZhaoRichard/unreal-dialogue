# Blueprint-based Dialogue system for the Unreal engine

Installation:

	1. Copy the folder /BlueprintBasedDialogue/ and all files in it to the /Content/ folder under a project, so that the files are under <project name>/Content/BlueprintBasedDialogue/
	2. Under Project Settings, Maps & Modes, set Game Instance Class to DialogueGameInstance
	3. Choose the appropriate NPC template from /Content/BlueprintBasedDialogue/ :
		NPC :  for third person and first person camera.  For first person, need to additionally include the Third Person Character Mannequin.
		NPC-TopDown :  for top down camera.
		NPC-SideScroller :  for 3D side scrolling camera.
		NPC-2DSideScroller :  for Paper 2D side scrolling camera.
	4. Open the Event Graph of the appropriate NPC template, and copy the F key event and its associated actions to the Event Graph of the player character.

Usage:
	
	The player character should be able to approach an NPC with the Dialogue system and press F to start a dialogue. Each dialogue is stored on the NPC under the Start Dialogue function.
	

For citations:
	
	Richard Zhao, Blueprint-based Dialogue system for the Unreal engine, https://github.com/ZhaoRichard/unreal-dialogue
