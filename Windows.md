# *Windows*

# ARCamera Window
Had copter style control elements (hidable/detachable)
Each control element has Bind button 

# HeadCamera window

Shows head mounted camera output, has aperture/exposition etc controls 

# Command Pallete

On the left hand of the  ***Wearer**** there is a **Command Pallete**. It has **CommandTextField** and **CommandTreeView** - first widget fiters second, responds on Enter. **CommandPallete** can be moved to any ***device***, such as ***laptop*** or ***tablet***.

**SkillCommands**, **UserCommands**, **BodyCommands**, **SpaceCommands***, **ProjectCommands**, **SequenceCommands**, **ItemCommands** are visually differentiated and can be filtered out per **Command Pallete** instance.

When **Command** is selected in **Command Pallete**, **HumanActor** starts immediately execute it.

# Bind dialog

When small **BindButton** next to the **Command** in **Command Pallete** is pressed, **BindDialog** pops out. It informs ***Wearer*** that any button or axis of any ***controller device*** connected to any of the connected computers can be used to bind on this **Command**.



# Timeline

Has time marks in Horizontal direction.
Vertically, there are names of the items/actors who have actions in scene/all actors in scene (checkbox filter)


command from command pallete can be drag and dropped to the sequence timeline
It can be inserted in tho the end or between other clips on the timeline. The length of the clips on the timeline might be adjusted.

Time scaling is reexecution of the commands with new set speed. It depends on the command - some will change animation according to set speed (walk versus run). Beginning and end pose/transform of character is guaranteed to be the same in clip regardless of it's new legit 


# mp3 file player

Responds on bindable Commands. Like all items can be recorded in sequence



# File dialogs

## Save


## Open

Has a text field for entering a directions. Makes request to Codex API for translating those instructions to JS into editable field. Has button execute.
