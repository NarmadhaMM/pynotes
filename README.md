# PyNotes for Environmental Scientists

A hands-on set of python notebooks intended for students that have little or no programming experience and are interested in acquiring basic programming skills. The Python notes focus on understanding programming logic by developing codes for automating and increasing the reproducibility of common tasks in plant and soil sciences.

## Interactive resources

[Documentation](https://andres-patrignani.github.io/pynotes)

[Interactive notebooks](https://mybinder.org/v2/gh/andres-patrignani/pynotes/master?filepath=notebooks)
(It make take few seconds to few minutes to load the interactive notebooks. For a quick reference consider exploring the Github repository or the PyNotes documentation.)


## Loading datasets

The real datasets used along these notebooks can be found in the `/datasets` directory. Throughout the examples it is assumed that the Python interpreter of the Jupyter Lab is in the `pynotes/notebooks` directory, reason why the exercises load datasets as `pd.read_csv("../datasets/file.csv")`. 

If you want to follow along an exercise without forking the entire material or downloading the datasets, you can always read the data directly from the Github repository, just make sure you get the URL link for the "Raw" data. FOr example:

`pd.read_csv('https://raw.githubusercontent.com/andres-patrignani/pynotes/master/datasets/anscombe_quartet.csv')`

Follow this video to learn how to obtain the link for the raw data.

<video controls="controls" width="800" height="600" 
       name="Video Name" src="get_raw_url_link_dataset.m4v"></video>

## Feedback

- For bug reports, code suggestions, and topic requests please open an issue in the [Github repository](https://github.com/andres-patrignani/pynotes/issues).

- For other related issues feel free to contact me at andrespatrignani@ksu.edu


## Support

The content of this website is used as a foundation for a gradaute level course in Scientific Programming and Reproducible Research offered every Spring semester within the Department of Agronomy at Kansas State University.

This initiative is partially supported by the Kansas State University [Open/Alternative Textbook Initiative](https://www.lib.k-state.edu/open-textbook)

## License
All the code in these Jupyter notebooks has been written entirely by the author unless noted otherwise. The entire material is available for free under the Creative Commons Attribution-NonCommercial-ShareAlike ([CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)) license
