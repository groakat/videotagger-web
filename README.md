# VideoTagger

## Summary

VideoTagger is a program that helps scientists to analyze videos. This includes fast-forwarding through videos to quickly identify if the video contains useful information, functionality to annotate stuff and to visualize annotations that span over a long period of time. Additionally, plugins allow for integration of machine learning algorithms that automate tasks.

## Explore

If confronted with a long video, extending over hours, if not weeks or months, it becomes quickly untractable to watch significant parts of the dataset. 

- VideoTagger can speed up and reverse videos up to 60x their original speed. Still, frame-by-frame stepping is possible for precise navigation through interesting frames.

- VideoTagger can concatenate shorter videos to infinitely long video sequences.

## Annotate

To quantify findings in the video, annotations are necessary.

- VideoTagger supports infinite label classes and infinite users
- Each user can customize the colour appearance of each class
- Anything in the video can be tracked by following it with the mouse
- Labels can be easily modified (move, resize, rename) with the mouse
- Externally computed trajectories can be imported
- Thumbnails of adjacent frames are shown that make it easy to see what happens in the previous and following frames

## Visualize

It is a challenge to visualize long continuous data. With annotations, this becomes more and more challenging the longer the video is, as one has to decide between detail or scope of the plotted graphs. As a solution to this problem, we implemented an interactive hierarchical visualization of the annotation data.

- Stacked bar-plot for days, hours, minutes and frames
- Each class is represented by a color
- Each bar-plot is the detailed view of the selected element in the bar-plot above.
- The plot is navigatable. The user can click on any bar to select it

![Animation of Visualization](https://github.com/groakat/videotagger/raw/gh-pages/support/FDV.gif)


# Installation

Install scripts are available for OSX and Windows (64bit). We provide a conda package for Linux users.

## OSX Yosemite
- Please download and install [Anaconda Installer](http://continuum.io/downloads "Anaconda"). 
- Download and run our [OSX Yosemite Installer](https://dl.dropboxusercontent.com/u/45267030/secretCode/Installvideotaggerviaconda.dmg "OSX Yosemite installer")

## Windows (64 bit)
- Please download and install [Anaconda Installer](http://continuum.io/downloads "Anaconda"). 
- Download and run our [Windows Installer](www. "Windows (64bit) installer")

## Linux
- Please download and install [Anaconda Installer](http://continuum.io/downloads "Anaconda"). 
- Then run in a terminal:

```
conda config --add channels https://conda.binstar.org/groakat
conda install videotagger
```

# Documentation

## User Guide

We have an ever growing [User Guide](www.userguide.co.uk "Plugin Guide") which should help you getting started. If something is missing, please do not hesitate to write to the [VideoTagger Google Group](https://groups.google.com/forum/#!forum/videotagger "mailing list").

## Plugins

A great and light-weight way of increasing the functionality of VideoTagger is to write a plugin. Please consult our [Plugin Guide](www.pluginguide.co.uk "Plugin Guide") on how to get started.

## Contribute

We are always looking for contributions. Feel free to browse the code on github and engage with us on our  [VideoTagger Google Group](https://groups.google.com/forum/#!forum/videotagger "mailing list"). We are glad to help you getting started and we look forward to your pull requests.


## Support
### F.A.Q.

### General Questions

Please use the [VideoTagger Google Group](https://groups.google.com/forum/#!forum/videotagger "VideoTagger Google Group") to contact us.

### Reporting Bugs

If you find a bug in VideoTagger, please open an [Issue on Github](https://github.com/groakat/videotagger/issues "issue on github").


