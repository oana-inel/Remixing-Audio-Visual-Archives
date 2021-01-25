# Remixing-Audio-Visual-Archives

This repository contains the experimental results of a user study aiming to remixing archival video footage to create alternate stories. The user study has been published in the following paper:

> Oana Inel, Sabrina Sauer and Lora Aroyo: **[A Study of Narrative Creation by Means of Crowds and Niches](http://ceur-ws.org/Vol-2173/paper1.pdf)**. [WIP&Demo 2018](https://www.humancomputation.com/2018/index.html).


If you find the paper and the data useful in your research, please consider citing:

```
@inproceedings{inel2018study,
  title={A Study of Narrative Creation by Means of Crowds and Niches.},
  author={Inel, Oana and Sauer, Sabrina and Aroyo, Lora and Bozzon, Alessandro and Venanzi, Matteo},
  booktitle={HCOMP (WIP\&Demo)},
  year={2018}
}
```

The repository contains the following documents:

* [__Visualizing Amsterdam's Past - Example of Log File__](https://github.com/oana-inel/Remixing-Audio-Visual-Archives/blob/main/Visualizing%20Amsterdam_s%20Past%20-%20Example%20of%20Log%20File.xlsx): 
  * Contains the guidelines that the users had to follow when watching and remixing the video footage.
  * The spreadsheet contains a prefilled example to be followed by the user. 

* [__Experimental Results - Users Log Files__](https://github.com/oana-inel/Remixing-Audio-Visual-Archives/blob/main/Experimental%20Results%20-%20Users%20Log%20Files.xlsx): 
  * Contains all the log files from all the users that participated in the study, filled in using the guidelines mentioned for the previous document.
  * Each sheet represents a story of a user.

* [__List of Remixed Videos__](https://github.com/oana-inel/Remixing-Audio-Visual-Archives/blob/main/List%20of%20Remixed%20Videos.xlsx): 
  * A list of all the videos that have been remixed in the micro-stories.
  * For each video we have extracted the available metadata from the [OpenImages](https://www.openbeelden.nl) platform, such as: the keywords describing the video, the length of the video, people or locations mentioned in the video, among others. 

* [__Machine Processed GIFs - Clarifai__](https://github.com/oana-inel/Remixing-Audio-Visual-Archives/blob/main/Machine%20Processed%20GIFs%20-%20Clarifai.xlsx): 
  * Contains the visual tags and concepts of each sequence (keyframe or video fragment) that was used for generating a GIF. We used the [FFmpeg](https://ffmpeg.org) tool to extract the video stills (keyframes) and video fragments composing each GIF.
  * The tags and concepts have been identified by running the online tool [Clarifai](https://www.clarifai.com) that performs both image and video concept recognition.
  
* [__Analysis of GIFs__](https://github.com/oana-inel/Remixing-Audio-Visual-Archives/blob/main/Combined-GIFs-info-Student-Machine.xlsx): 
  * Contains the final analysis document, which combines the manual and atomatic processing of the keyframes and video fragments composing each GIF.
  
* [__List of Sequences Composing the GIFs__](https://github.com/oana-inel/Remixing-Audio-Visual-Archives/tree/main/Keyframes_Sequences)
