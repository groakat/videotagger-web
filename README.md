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
- anything in the video can be tracked by following it with the mouse
- labels can be easily modified (move, resize, rename) with the mouse
- externally computed trajectories can be imported
- thumbnails of adjacent frames are shown that make it easy to see what happens in the previous and following frames

## Visualize

It is a challenge to visualize long continuous data. With annotations, this becomes more and more challenging the longer the video is, as one has to decide between detail or scope of the plotted graphs. As a solution to this problem, we implemented an interactive hierarchical visualization of the annotation data.

- stacked bar-plot for days, hours, minutes and frames
- each class is represented by a color
- Each bar-plot is the detailed view of the selected element in the bar-plot above.
- the plot is navigatable. The user can click on any bar to select it

![Animation of Visualization](https://github.com/groakat/videotagger/raw/gh-pages/support/FDV.gif)


# Installation

# Documentation

## Plugins

## Contribute


