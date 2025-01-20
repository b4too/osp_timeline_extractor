# osp_timeline_extractor
## Allows easy timeline extraction from OSP project

I had to write a little something to recover an OpenShot project that I could not open anymore.

This allows to do that by loading the project file and giving you the different files used in the project and the timeline, thus allowing you to do it again in another project, or another app, which is why I also included an option to export the data in a Kdenlive-friendly format.

This only needs the standard library of Python, that you can get [here](https://www.python.org/downloads/) if you don't have it already.

Then, simply download the `OpenShotTimelineExtractor.pyw` and execute it.

If you are on linux don't forget to `chmod +x OpenShotTimelineExtractor.pyw` to give execution right to the script.

I tested it on Python 3.11 on both windows 10 and a Ubuntu-based OS.

![Demo](/demo.gif)
