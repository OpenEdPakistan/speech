# Audio Content Creation using Microsoft Cognitive Services and Speech Studio
## Why?
_**Custom Development:**_ Developers typically write a Windows Forms or Console Application using C# to call the Microsoft Cognitive Services Speech API to generate audio utterances for their applications; refer to code in the _'Samples-Http'_ folder [here](https://github.com/Microsoft/Cognitive-Speech-TTS).
## What?
_**No Code:**_ The approach used by OPEN (Open Pakistan Education Network) and illustrated visually below, uses a no-code approach offered by the Speech Studio portal to create audio content for its knowledge content, so that Pakistani learners can get a clear Neural voice and not a robot-sounding voice in their courses.
![OPEN Workflow](images/OPEN-Workflow.png)
## How?
*The steps assume that you have public access to a Microsoft cloud subscription using the Azure Portal.*
1. Go to the [Speech Studio](http://speech.microsoft.com) and log in.
1. On the _'Audio Content Creation'_ page, click the _'Upload'_ button, select the text file (by clicking the _'Browse files...'_ button on the _'Upload file'_ dialog, navigating to the local .txt file, selecting it), check the _'Split input script...'_ checkbox, and click _'Next'_.
1. On the _'Split files'_ dialog, select the _'By paragraphs'_ radio-button, and click _'Upload'_.
