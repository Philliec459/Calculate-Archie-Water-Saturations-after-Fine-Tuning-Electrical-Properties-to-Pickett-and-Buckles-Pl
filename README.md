# Calculate-Archie-Water-Saturations-after-Fine-Tuning-Electrical-Properties-to-Pickett-and-Buckles-Pl
Calculate Archie Water Saturations after Fine-Tuning Electrical Properties to Pickett and Buckles Plots using Python’s Panel Library.

While experimenting with interactive python tools for our next GitHub repository, we came upon a python library called panel. Panel appears to provide the type of interaction that we need for our petrophysical analysis. This simple example represents work in progress, but we have placed this python tool in this GitHub repository for others to try use and hopefully improve upon what we have so far.

In the animated example below, we are calculating Archie water saturations from a Costa Field well. The panel tool shown below calculates a new water saturation as you vary the electrical properties (a, m and n) or Rw. The tool provides instantaneous results that are seen from from the changes in the saturation lines in the Pickett plot as well as the changes in BVW seen in the depth plot.

Panel provides the type of interactivity that allows the user to fine-tune their analysis using both the Pickett and Buckles plots. The Pickett plot is fundamental to our calculation of water saturations from conventional logs, and this tool allows you to build a better understanding of your data to develop a better feel for the sensitivity of each parameter used in the Archie water saturation calculation (a, m, n and Rw). 

In this example well, the interval at the bottom of the depth plot appears to be wet. However, is this interval at 100% Sw or does it contain some residual oil? We do not have residual fluid saturations from core to allow us to make that determination, so we have made the assumption that this intervals is 100% water saturated for now. 

In this example we adjust the m and Rw to give us 100% water saturations from logs for this lower interval. You can then adjust n to give you the expected BVW from the Buckles plot. We have added an Archie 'a' tortuosity parameter slider too for you to experiment with.
>---
>From Craig Phillips GitHub repositories: (https://github.com/Philliec459)
>---
>
>![Panel_log](pickett_log_sats3.gif)
>
---
