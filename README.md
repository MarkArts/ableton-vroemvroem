# Ableton project for the amazing track vroemvroem
## Requirments
* Ableton 11.1
* Probaply windows

## Setup
After each pull run (double click) the `afterpull.cmd` file to generate the ableton project file.
Then open (double click) the `vroemvroem.als` file and you are ready to go

### Limitations
Because it's not possible to share plugins (vst2/vst3) with this git approach you are only able to use stock plugins.
Max devices should be able to be saved to repo and manually linked on startup.

## Before commiting
Before commiting there are 2 important steps to take:
1) Generate the audio files for the project `file -> export`(mp3/wav)
2) Save the project with `file -> collect all and save` and select all options. This will make sure that recorded samples and preset you use will be included in the folder
3) Run (double click) the `beforecommit.cmd` file to generate the xml file of the project to commit
