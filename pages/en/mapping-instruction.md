---
layout: en_default
title:  BandSpace Editor
tagline: 
language: en
---

# Mapping Instructions
## First Launch
The first time you launch the application, you will be asked to set the path for storing beatmaps and language, which can be modified at any time on the **Options** page.

### Create a New Beatmap
All your beatmaps in the storage path will appear on your song list page.  
Regularly created maps appear in song list under **Regular**. Click on Beatmap to proceed with editing.  
Creating maps under **MIDI Conversions** by importing MIDI file will automatically generate beatmaps. It requires that you prepare a MIDI file that matches with your audio file in advance. For details, please refer to [MIDI To Beatmap](midi-to-beatmap).

## Song Infomation
Before proceeding with editing proper, please fill out following information about song.

### Song Name, Artist, Map Author
Input name of song and artist , plus providing a signature identifying yourself as map's author.

### Cover Art & Audio File
Attach an image using **.jpg** or **.png** as cover art for this map − recommended to use a 1:1 album cover image corresponding to the song.   
Import prepared audio files using format **.ogg**.

### Preview Clips
Preview clips perform audio extracts when pre-selecting this music piece within game; After setting clips starting point and duration for previewing should press "play button" for audition preview section - Suggestion making climax sections within music piece as starting point; The length during preview period should range from 15-25 seconds.

### BPM
BPM (Beats Per Minute) is a unit of beat frequency per minute, which will affect the position of each major beat auxiliary line relative to the song in the editor.  
If you are unsure of the BPM of the audio file you are using, there are some online websites that can help you measure, such as [vocalremover](https://vocalremover.org/key-bpm-finder) and [AudioDirector](https://directorsuite-online.cyberlink.com/en/audio-editor/vocal-remover).

### Time Offset
The song time offset refers to the blank time between the start of your audio file and the first beat. The audio will play from position of offset value.  
Although this will influence where your audio starts from when editing beatmaps, in actual gameplay, it is playing at original start point.

### MIDI (Only for MIDI to Beatmap)
This option only appears after you choose to create a **new MIDI conversion** beatmap. It's used for importing MIDIs, see [MIDI To Beatmap](midi-to-beatmap).

### Environment and Lighting Style
There are currently 5 available scenes to choose from; each scene has different styles of lighting options.  
Whenever a scene and lighting style are chosen together within editor mode wherein each time saving conducted - it's automatic generating light file based on existed beats map information acquired.

### Video File
When **Concert** is selected as your scene, **.mp4** formatted video files can be uploaded (MAX 200MB); this video clip will play out on LED display located within the concert.  
If you don't have a video clip, don't worry just leave it blank that we'll automatically play the pre-arranged video instead.

### Instruments & Difficulty
BandSpace offers four instrumental gameplay: drums, keyboards,bass,and guitar. You can create a total four maps according to instruments or just features certain types among them.  
As each instrument has a different style of gameplay, their beatmap editing interfaces and rules also vary.  
Further reading approaches on difference across playable instruments beneath  **Beatmap Editing > Instrument Differences**.  

The difficulty of the beatmap is divided into 5 levels, from the simplest to the hardest:  
**Easy**, **Common**, **Hard**, **Expert** and **Expert+**  
You can set the difficulty by modifying it in the right bottom dropdown box. Different instrument can be set to different difficulty.

### Open Editor
After selecting the instrument you want to edit next, click the **Open Editor** button to enter the editing scene and start designing a beatmap for that instrument.

### Create Zip File
When you have finished creating beatmaps for all included instruments, click the Create Zip button. We will automatically create a zip file of the beatmap for you, and display its location to you. Follow the [Play Custom Map](play-custom-map) guide, place it into a specific location in the game and then you can play your own beatmap!  

Of course, we welcome and encourage you to upload your created maps to share on [Mod.io](https://mod.io/g/bandspace) community so all players can have access to your designs.

## Beatmaps Edit
### Basic operations
**Cursor Interval**: The cursor interval determines the number of segments evenly divided between the beats.  
If this value is **1/1**, there is only one segment between beats, and the note placed with the mouse will only adhere to the primary and secondary guide lines between two beats. If this value is **1/4**, each beat will be divided into four segments, placed notes will be attracted to nearest dividing auxiliary line.  

**Place Notes**: According to cursor interval, place specified note type on nearest track and guide line by clicking Left Mouse Button.  

**Move Notess**: Hover the mouse over an existing single note, use **Alt+Left Mouse Button** to grab and move the note, then release **Left Mouse Button** to place it in a new position.  

**Select notes**: Use **Shift+Left Mouse Button** to select a note; when notes are selected, use **Ctrl+A** to deselect all notes.  

**Link Long Notes**: While multiple notes are selected, you can use the shortcut key **L** to create long notes with these selected notes as nodes. Be aware of the different rules for long notes for different instruments; if these rules are not met, it may fail to generate.  

**Deletion**:  
Method 1. Use the Delete tool in the left toolbar to enter Delete mode. In this mode, click **Left Mouse Button** on a note to delete it.  
Method 2. When notes are selected, you can use the **Del** key to quickly remove all selected notes.  

**Save**: Closing the editor will lose unsaved data, so remember to save your work before closing. Use **Ctrl+S** to save the current beatmap data. You can also enable auto-save in the options, after which the editor will automate a save every five minutes.

### Instrument Differences
#### **Drums**
**Tracks**:  
The drums have a total of 6 tracks. Tracks 1 and 6 are for the left cymbal and right cymbal respectively; Tracks 2 and 5 are for the left low drum and right low drum respectively; Tracks 3 and 4 are for the left high drum and right high drum respectively.  
A maximum of two notes can only be played at one time on drums (since we only have two hands, right?).  

**Normal Notes**: Displayed in yellow, players can score by hitting with any force.  
**Thump Notes**: Displayed in purple, players need to strike harder to get full marks.  
**Long Notes**: Long notes can only be generated through linked notes within the same track. Players can strike any number of times until the note ends.

#### **Keyboard**
**Tracks**:  
The keyboard has a total of 7 tracks. At the same time, a maximum of only two notes can be on different tracks (similar to drums, because everyone only has two hands).  
Due to the keyboard's specificity, visually, notes are designed to be twice as wide as the track. This means that in actual gameplay notes will cover two adjacent tracks. For example, placing a note on track 2 would actually cover half of both track 1 and track 3.  
Therefore in map design it's recommended that notes at the same time are separated by at least one lane so visually they don't overlap. (Of course overlapping doesn't affect playability; it's just that if you put two handles too close together they might bump into each other.)  

**Normal Notes**: Players press the corresponding piano key when the normal note reaches the judgement line.  
**Long Notes**: Keyboard long notes can span across tracks. Players press and hold the piano key when long notes reach the judgement line and slide on it following its movement.  

#### **Bass**
**Tracks**  
The bass has 4 tracks. Only one note can be in any track at the same time (since only one hand is used to choose tracks on the bass).  

**Normal Notes**: The player uses one hand to slide to the track corresponding to the note and completes a strumming action with another hand when the note reaches judgement line.  
**Long Notes**: Bass long notes can span several tracks. Players perform a strumming action when notes reach judgement line, and with their fretting hand, slide along neck following movement of long note.

#### **Guitar**
**Tracks**  
The guitar has 6 tracks in total, with tracks 1, 3, and 5 being Trigger tracks (pressure from the index finger on the controller's trigger button), and tracks 2,4,and 6 being Grip tracks (pressure from middle finger on controller's grip button).  
When choosing double-finger notes we can place them on either of the lanes 1&2, 3&4, 5&6 for those notes that require simultaneous pressure of both trigger and grip buttons.  
A guitar can only have one single or double finger note at the same time (the same applies for bass, as there is only one hand to choose the track and press the key).

**Single-finger Notes**: The player uses one hand to slide to the track corresponding to the note, presses the specified key, and completes a strumming action with another hand when the note reaches judgement line.  
**Double-finger Notes**: The player uses one hand to slide to the track corresponding to the note, simultaneously presses both trigger and grip keys, and completes a strumming action with another hand when it reaches judgement line.  
**Long Notes**: Guitar long notes can span across multiple tracks but can only connect between notes of compatible triggers or grips.  
The player performs a single strum as long notes reach judgement line while consistently holding down indicated keys on fretting (note-choosing) hands following along pathway of continuous-long-note movement sliding on guitar's neck.

### Advanced Operations
Advanced operation techniques can assist you in achieving a more efficient editing experience.  

**Select**: Use **Ctrl+Left Mouse Button** to summon the multiple-selection box, and select multiple notes simultaneously.  

**Cut**: Use **Ctrl+X** to cut the selected notes from the beatmap and move them to clipboard.  

**Copy**: Use **Crtl+C** can copy selected notes onto clipboard.  

**Paste**: Use **Ctrl+V** to paste all the notes from the clipboard to the beatmap based on the red playback line.  

**Overwrite Paste**: Use **Ctrl+Shift+V** to overwrite paste all notes from clipboard onto beatmap based on red playline.  

**Undo**: Use **Crtl+Z** or **Ctrl+Shift+Y** to undo most recent operation or changes.  

**Redo**: Use **Crtl+Y** or **Ctrl+Shift+Z** to reapply most recently undone action.  

**Bookmarks**: Press **B** key to add a bookmark based on the time of the red playback line. Users can edit bookmark content and color. The bookmarks will appear on the song progress bar, click these bookmarks to quickly jump to corresponding time nodes.  

**Editor Scale**: Use **-** and **=** keys to control beatmap scale.  

**Song Speed**: Use **Up Arrow** and **Down Arrow** keys to control speed of song playback.
