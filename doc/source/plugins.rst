Plugins 
========== 

Target
------

Ideally we want to allow users to include plugins that are capable of getting the following information from `VideoTagger`:

    * Video files
    * Extracted Features
    * Current annotations
    * Plugins should be stand-alone if executed as Python script



Current Status
--------------

Plugins can be implemented, by using the quite rudimentary `pyTools.system.ClassificationPluginBase` class. We are hoping to include more and more common functions to make it easier to use the plugin functionality. Particulary, we are aiming to reduce the amount of boiler-plate code.

Plugin Tutorial
---------------

A plugin is loadable into `VideoTagger` if it is a class that inherits from `pyTools.system.plugins.PluginBase`. A more convinient class to inherit from is `pyTools.system.plugins.ClassificationPluginBase`. Fully working examples of plugins doing classification are in `pyTools.plugins`. We will use the `SimpleHistogramPlugin` as basis for this tutorial.


Basic function overview
```````````````````````
The `ClassificationPluginBase` class is initiated by `VideoTagger` by calling the `runPlugin()` function. This function calls the 4 functions that have to be implemented by any class that inherits from `ClassificationPluginBase`:

* `extractFeatures()`
* `trainClassifier()`
* `classify()`
* `generateFDVT()`

To inherit from the `ClassificationPluginBase` one has to implement these functions.


ExtractFeatures()
'''''''''''''''''

* *opt:* setup progress bar with `self.setStatus()`
* iterate through videos in `self.videoListRel`
      - for each video, setup a `videoExplorer` and iterate through frames
      - *opt:* check whether features were already computed, if not:
      - extract features for each frame
  





