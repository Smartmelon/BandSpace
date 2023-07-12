---
layout: en_default
title:  BandSpace Beatmap Editor
tagline: 
language: en
---

# Basic Instructions
Now that you've launched the Band Space Editor and have your audio files ready, let's start designing the beatmap.  

## **Create a new beatmap file**
Before we start the design, we need to create a file to store beatmap information.  
Click the "New" button on the startup page, enter the song title and artist(s), and click "Create".  
You will now see the beatmap Information Edit page.

## **Enter basic information about the song**
Now you can import the audio file you prepared earlier into the beatmap. Click the "Song" button, find the audio file in the pop-up window, and click "Open". Again, only OGG files are currently supported, all other formats will not be displayed in the window.  
Then you also need to add a cover image (jpeg, jpg and png formats less than 1MB). We normally will use the album cover of the song as the beatmap cover，and we recommend the image to be at 100x100 resolution for the best in-game visual effects. The step to importing the cover is the same as importing your song file.  
You can also improt a short preview audio for your beatmap to play when it is selected on the game menu, it is recommended to capture 15-30 seconds of the climax of the song as the preview audio.  
Finally, choose the game scene for your beatmap, which determines the time-space where you will be performing the song. The custom songs are only available in the scene of the Moon for now, scenes such as the Cyberpunk, Desert, Apocalypse, and Concerts will be available in the future.


## **Set song time**
### Find the BPM of the Song
BPM refers to the number of beats per minute, which is the speed mark of the song. It is a speed standard that is independent of the score. Generally, one beat is a quarter note, and 60BPM is an average of 60 quarter notes per minute. Every song has this parameter, if you don't know the BPM of the song, you can detect it through some online websites, such as [vocalremover](https://vocalremover.org/key-bpm-finder) and [AudioDirector](https://directorsuite-online.cyberlink.com/en/audio-editor/vocal-remover). Just upload your audio file, wait for a little, and you will see the BPM of the audio. After that, Fill in the "BPM" column with the correct value.  

## **Align the audio**
The editor defaults that your audio file starts with the first beat, but most audio files have a short silence before the sound comes in.  
We have two ways to solve this problem.  
The first method is to use tools such as [Audacity](https://www.audacityteam.org/) or [FormatFactory](http://www.pcgeshi.com/index.html) to pre-trim the audio file, cutting out the blank segment of the beginning.  
The second method is to set up an offset value for the audio file. The offset value equals the blank time at the beginning of the audio file. You can measure the blank time by yourself through the audio software as we have just mentioned, and just fill it in the "offset value" column with no need to cut the audio file.

## **Design the beatmap**
In order to design more efficiently, before we start, let's take a closer look at the user interface.  

### The basics of note editing
**Add a note:** Find the time spot(or subdivided beat point) in the audio where you want to insert your note at, then left-click on the aligned note cell on one of the tracks to place the note, and right-click on the note to delete it.  
**Undo:** The "backward curved arrow" button on the lower-left corner can undo the changes you just made. Before you close the editor, the editor has recorded all the edits you have made, allow you to undo many times until the beginning of the design.  
**Save:** "Save" button on the bottom-right corner to save your editing data, or you can press "Ctrl"+"S" on the keyboard to save your work. The editor automatically saves data every two minutes, and closing it will lose all unsaved data. So remember to save your creation before closing the editor.  
**Empty the beatmap:** The "trash can" icon on the bottom-left corner can empty all the note data at one time, remember to be careful. 

### Choose the instrument
Super String Band supports four instruments to play: guitar, bass, keyboard, and drums. Even in one same song file, the beatmap of the four instruments is relatively independent. You can make a total of 4 maps, one for each instrument for the song, or you can just choose your favorite 1-3 instruments to design. This does not affect the operation of the beatmap file in the game, just select the instrument that you have designed beatmap for when playing.  
Because each instrument's gameplay is different, their map editing interface is a little different, you can go to the instrument below to learn it.  


#### **Guitar**
Note tracks: The guitar has a total of 3 sets of note tracks (track no.1, no.2, and no.3 from left to right), and each of them corresponds to a lateral instrument position. Each set of tracks is divided further into left and right tracks which correspond to the two buttons on the left-hand handle (Trigger - Left and Grip - Right). There can only be at most one note on the same beat point for the guitar.  

**Single finger/double finger** : Toggle single finger/double finger editing mode, only one can be selected  

**Single finger** : A single-finger note occupies only one track. There are two tracks in each track group, the left one is for the Trigger button(index finger) and the right one is for the Grip button(middle finger).   

**Both finger** : The width of a two-finger note is equal to a set of tracks. Playing requires pressing both the Trigger(index finger) and the Grip(middle finger) buttons at the same time.  

**Hit/Hold** : Click to switch Hit/Hold editing mode, only one can be selected  

**Hit(strummed once)** : In hit note edit mode, click to place a hit note on a note cell.  

**Hold(strumming once and holding or moving the left-hand position till the note finishes)** : In hold note edit mode, click the first time to place the head note on a note cell, then click the second time on another note cell to place the end note (the end note can be on a different track on the same finger button, you cannot change the button of the finger during a hold note, so it has to be either Trigger track to Trigger track, Grip to Grip,or Goth Fingers to Both Fingers).  

#### **Bass**
Note track: The Bass has a total of 4 note tracks (Track no.1, no.2, no.3, and no.4 from left to right), and each track corresponds to a lateral instrument position. There can be at most one note on the same beat point for the bass.  

**Hit/Hold**: Click to switch Hit/Hold editing mode, only one can be selected  

**Hit (strummed once)**: In hit note edit mode, click to place a hit note on a note cell.  

**Hold (strumming once and holding or moving the left-hand position till the note finishes)**: In hold note edit mode, click the first time to place the head note on a note cell, then click the second time on another note cell to place the end note (track can be changed).

#### **Keyboard**
Note track: The keyboard has a total of 7 note tracks (Track no.1, 2, 3, 4, 5, 6, and 7 from left to right). At most two notes can exist on the same beat point for the piano. But note that the width of a keyboard note is greater than 1 track, so the distance between two notes on the same beat point must be greater than one track (Track no.1 & 3, Track no.2 & 4, etc.).  

**Hit/hold**: Click to switch Hit/Hold editing mode, only one can be selected  

**Hit (key play once)**: In hit note edit mode, click to place a hit note on a note cell.  

**Hold (play the key once and hold or move the hand position till the note finishes)**: In hold note edit mode, click the first time to place the head note on a note cell, then click the second time on another note cell to place the end note (track can be changed).

#### **Drum**
Note tracks: There are a total of 6 note tracks on the drum (Track no.1, 2, 3, 4, 5, and 6 from left to right). There can be up to two notes at the same time on the same beat point for the drum. Note that the corresponding drum pieces and their height in the game are different. Tracks no.1 and 6 tracks are the cymbals, they are the highest; tracks no.2 and 5 are the two drums on the bottom left and right, and tracks no.3 and 4 are the two drums that are just in front of your chest.  

**Normal Hit/Slam**: toggle Normal Hit/Slam edit mode to select only one of them  

**Normal Hit**: Hit at any intensity to score.  

**Slam**: Requires the player to hit hard to get full scores, but as hold as they hit, they will be scored based on the strength of the hit.  

**Hit/Hold**: Click to switch Hit/Hold editing mode, only one can be selected  

**Hit (hit once)**: In hit note edit mode, click to place a hit note on a note cell.  

**Hold (hit any number of times until the end of the note and score according to the number of times hit. The score limits are different for different note lengths, the holder the higher)**: In hold note edit mode, click the first time to place the head note on a note cell, then click the second time on another note cell to place the end note (you can change the track).  


### Difficulty of beatmap
There are 5 levels of difficulty, from easiest to hardest are: EASY, COMMON, HARD, EXPERT, EXPERT +  

The difficulty information of the beatmap is defaulted as EASY but can be modified in the drop-down box in the upper-right corner. In one song file, each of the 4 instrument map can be set to different difficulty levels, and the difficulty information will be displayed in-game on the song selection page.  


## **Generate lighting effects for beatmaps**
Remember the cool lighting effects when playing the official beatmaps? You can add the same effect to your own beatmaps! There is no extra operation required, the system will generate a suited lighting effect for you when saving the beatmap. But reminded that the current lighting arrangement refers to the beatmap of the drum, and if you have not designed the beatmap for the "drum", you probably won't be able to get a good lighting effect.  

## **Save your work!**
Lastly, Click the "Save" button on the bottom-right corner or just press "Ctrl"+"S" on the keyboard to save your work!  


Through the processes above, you have already finished making a beatmap.  

You can now go to the file path prompted when saving, move the created map to the game folder for playing (For detailed instructions, please refer to [Play Custom Beatmap](play-custom-map)). Then start the game, and select to play the song in SOLO Performance mode.



# Advanced Editing  

Advanced editing techinique could help you to have a more efficient mapping experience.

## **Number of Beats per bar**
The number of beats per bar (corresponding to the upper numeral of a time signature), this value changes the time sign count on the timeline and is displayed numerically in each bar.  

## **Beat breakdown**
The number of subdivided beat points per beat, you can see this as the average number of slices of a segment, this will change the density of the minimum beat point of a song (the granularity of the edit table), the larger the beat subscore allows you to write a more dense number of notes.  

## **Add a Bookmark**
Bookmarks can be used to mark key points on the beatmap, such as the beginning of a chorus, the beginning of an instrument's solo. Adding a bookmark makes it easier to find where you need the beatmap.  

You can move your mouse to the empty space between the edit grid and the page scroll bar. You will see an orange pen-like icon appear when you hover your mouse over it, then click to add a bookmark to the current position, type whatever you want to note down, and click on any blank area to save.  

If you want to change or remove an existing bookmark, find and click on the bookmark, type or delete and click on any space area to save.  

## **Batch selection**
In "Edit", you can select multiple notes by left-clicking on a bland space and dragging your mouse  over the notes, the selected notes will be highlighted in green. After at least one note has been selected, click the right mouse button to deselect them.  

### Batch copy
After selecting at least one note in the box, move the mouse to the position where the note can be added, left-click on a note cell again to copy all the selected notes, and note that your cursor point corresponds to the bottom-left-most note of all the notes selected (The bottom-left-most note will be pasted at your cursor point).  

### Batch deletion
After selecting at least one note in the box, use the keyboard's "Delete" key to delete all the notes selected.  

## **Autosave**
Accidentally closed the editor and forgot to save your changes? Don't worry, the editor has automatically saved the data every 2 minutes to prevent you from losing your dedicated work.