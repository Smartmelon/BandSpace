---
layout: en_default
title:  BandSpace Mapping
tagline: A user-friendly beatmap tool for BandSpace VR
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
The first is to use tools such as [Audacity](https://www.audacityteam.org/) or [格式工厂](http://www.pcgeshi.com/index.html) to pre-trim the audio file, cutting out the beginning of the blank segment.    
The second method is to fill in the offset value for the audio file, and the offset value is the blank time at the beginning of the audio file. You can measure the blank time by yourself through the familiar audio software and fill it in the "offset value" column without cutting the audio file.  
