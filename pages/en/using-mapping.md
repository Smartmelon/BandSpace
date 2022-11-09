---
layout: en_default
title:  BS Beatmap Editor
tagline: 
language: en
---

# Using Mapping
Now that you've launched the Superstring Editor and have your audio files ready, let's start designing the sheet music.  

## Create a new spectrum file
Before we start the design, we need to create a file to store spectrum information.  
Click the "New" button on the startup page, enter the song name and artist name, and finally click "Create".   
You will now see the Spectral Information Edit page.  

## Edit basic information
Now you can import the audio file you prepared earlier into the spectrum. Click the "Import Songs" button, find the audio file in the pop-up window, and click "Open". Again, only files in the .ogg format are currently supported, and other formats will not be displayed in the window.    
Then you also need to add a cover image to the sheet, usually we will use the album cover corresponding to the song. Currently uploading images in .png format is supported, and 100x100 resolution images are recommended for the best visual effects in the game. The process of importing covers is the same as importing songs.    
Finally, choose an environment for your sheet, which determines the space you will be in when playing the sheet. We have selected the "Desert" scene for you by default, which you can modify by clicking this button.    
As for the "Generate Light" function at the bottom, there is no need to worry, we recommend to deal with it after the spectrum design is completed. First click the "Edit" button on the left side of the editor to design the spectrum.  

## Set song time
### Confirm Song BPM
BPM is the number of beats per minute, which is the full song speed mark. It is a speed standard that is independent of the score. Generally, one quarter note is a beat, and 60BPM is an average of 60 quarter notes per minute. This means that every song has this parameter. If you do not know the BPM of the audio file you are using, you can help you measure it through some online websites, such as [vocalremover](https://vocalremover.org/key-bpm-finder) and [AudioDirector](https://directorsuite-online.cyberlink.com/en/audio-editor/vocal-remover). Just upload your audio file, wait a little, and you will see the BPM of the audio. Fill in the "BPM" column with this value.  

## Align songs
The editor defaults your audio file to start with the first beat, but most audio files start with a small space.    
We have two ways to solve this problem.    
The first is to use tools such as [Audacity](https://www.audacityteam.org/) or [FormatFactory](http://www.pcgeshi.com/index.html) to pre-trim the audio file, cutting out the beginning of the blank segment.    
The second method is to fill in the offset value for the audio file, and the offset value is the blank time at the beginning of the audio file. You can measure the blank time by yourself through the familiar audio software and fill it in the "offset value" column without cutting the audio file.  

## Design beatmap
In order to design more efficiently, before we start, let's take a closer look at the user interface.
### Understand the basics of music note editing
Place music note: According to the time/beat point of the audio, left-click on the note cell of one of the tracks horizontally to place the music note, and right-click on the music note to delete it.  

Undo: The "Undo icon" in the lower left corner can undo the changes you just made. Before you close the editor, the editor will record all editing operations, and you can undo back to the original editing state of the sheet.  

Save: "Save" button in the lower right corner to save your editing data. The editor automatically saves data every two minutes, and closing it will lose all unsaved data. So remember to save your creation before closing.  

Empty the sheet: The "trash can" icon in the lower left corner can empty all the music note data at one time, remember to be careful.  

### Choose which instrument to make the sheet for
Super String Band supports four instruments to play: guitar, bass, keyboard, and drums. Even if it is the same song, the beatmap of the four instruments is relatively independent. You can make a total of 4 maps for all instruments for your song, or you can choose your favorite 1-3 instruments to design. This does not affect the operation of the beatmap file in the game, you can play only the instrument that you have designed beatmap for.  

Because each instrument's gameplay is different, their map editing interface is a little different, you can find the instrument you need below to understand.  

#### Guitar
Music note tracks: The guitar has a total of 3 sets of music note tracks, each track corresponds to a lateral instrument position, 1, 2, and 3 tracks from left to right. Each set of tracks is divided into left and right tracks, which correspond to the two buttons of the left-hand handle (Trigger and Grip). There can only be at most one music note on the same beat point in guitar's map.  

**Single finger/double finger** : Toggle single finger/double finger editing mode, only one can be selected  

**Single finger** : A single-finger music note occupies only one track. The two tracks in each group are the left-index-finger button (Trigger) and the right-middle-finger button (Grip).  

**Both finger** : The width of a two-finger music note is equal to a set of tracks. Playing requires pressing the index finger button (Trigger) and the middle finger button (Grip) at the same time.  

**Short/Long** : Click to switch short/long editing mode, only one can be selected
Short play (strummed once): In short edit mode, click to place a short music note in note cell.  

**Long play** (strumming once and holding or moving the left hand position): In long play mode, click the first time to place the head note in a note cell, then click the second time in another note cell to place the end note (you can change the track, but you cannot change the button of the finger halfway, for example, trigger to trigger, grip to grip, both fingers to both fingers).  

#### Bass
Music note track: Bass has a total of 4 music note tracks, 1, 2, 3, and 4 tracks from left to right, each track corresponds to a lateral instrument position. There can be at most one music note on the same beat point of bass.  

**Short/Long** : Click to switch short/long editing mode, only one can be selected  

**Short play** (strummed once): In short edit mode, click to place a short music note in note cell.  

**Long play** (strumming once and holding or moving the left hand position): In long play mode, click the first time to place the head note in a note cell, then click the second time in another note cell to place the end note (track can be changed).

#### Keyboard
Music note track: The keyboard has a total of 7 music note tracks, 1, 2, 3, 4, 5, 6, and 7 tracks from left to right. At most two music notes can exist on the same beat point of the piano at the same time, but note that the width of the music note of the keyboard is greater than 1 track, so the distance between two music notes on the same beat point must be greater than one track.  

**Short/Long** : Click to switch short/long editing mode, only one can be selected  

**Short play** (key play once): In short edit mode, click to place a short music note in note cell.  

**Long play** (play the key once and hold or move the position): In long play mode, click the first time to place the head note in a note cell, then click the second time in another note cell to place the end note (track can be changed).  

#### Drum
Music note tracks: There are a total of 6 music note tracks on the drum, 1, 2, 3, 4, 5, and 6 tracks from left to right. There can be up to two music notes at the same time on the same beat point of the drum. Note that the corresponding drum pieces and percussion heights of each track in the game are different. The 1 and 6 tracks on the left and right sides are the highest hanging hats, the 2 and 5 tracks are the lowest drum surfaces on the left and right, and the 3 and 4 tracks are the two drum surfaces with medium height on the chest.  

**Normal Hit/Slam** : toggle tap/tap edit mode to select only one of them  

**Normal Hit** : Hit at any intensity to score.  

**Slam** : Requires the player to tap hard to get full scores, but as long as they hit, they will be scored based on the strength of the tap.  

**Short/Long** : Click to switch short/long editing mode, only one can be selected  

**Short play** (tap once): In short edit mode, click to place a short music note on the corresponding track note cell.  

**Long play** (tap and play any number of times until the end of the music note, according to the number of times, there are different score limits for different durations): In long play mode, click the first time to place the head note in a note cell, then click the second time in another note cell to place the end note (you can change the track).  

### Difficulty of Setting beatmap
There are 5 levels of difficulty, from easiest to hardest: EASY, COMMON, HARD, EXPERT, EXPERT+  

You can set the difficulty information for the beatmap, which can be modified in the drop-down box in the upper right corner. Under the same song file, the beatmap of different instruments can be set to different difficulty levels, and the difficulty information will be displayed on the song selection page.

## Generate lighting effects for spectral surfaces
Remember the cool lighting effects you saw when playing the official beatmap? You can also add the same effect to your own beatmap!  

And no complicated operations are required, just go back to the "Song" page and click the "Generate Lights" button at the bottom. It should be reminded that the current lighting arrangement refers to the beatmap of the instrument "drum", and if you have not designed the beatmap for the "drum", you will probably not be able to get a good lighting effect.  

Through the processes above, you have already finished making a beatmap.  

You can now go to the file path prompted when saving, move the beatmap to `Steam\steamapps\common\Band Space\BandSpace_Data\AutoCreateData\SongData` in the installation path of the game. Then start the game, and select to play the song in SOLO Performance mode.

If you like to have a more efficient mapping experience, please try our [advanced-operation](advanced-operation). 