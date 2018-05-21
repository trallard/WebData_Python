# Working with Web Data in Python 🐍
Course materials for working with web data in Python. Originally developed for a 1 full-day course at the Methods Institute @Sheffield

---

## About the course
This course will show how one can treat the Internet as a source of data.


What will be covered?
- Use Python to scrape, parse and read web data
- Understanding Application Programming Interfaces (APIs) and use them to collect data
- How to query APIs using the appropriate requests (case studies: GitHub, Twitter)
- Commonly returned data formats: HTML, JSON, XML
- Programatic web data collection and streams
- Regular expressions 📃
- Plotting web data

The materials are split into broad sections containing exercises, explanations and most of the information you need to complete them. The material covered is far from exhaustive. Instead, we try to provide enough information and tasks to get you started and we hope to get you quickly to a level where you are then capable of continuing to use Python to collect and handle web data.

## Pre requisites
For you to be able to follow along the course you need to have a basic knowledge of Python as well as a basic understanding of:
- Functions
- Loops
- Nested data structures
- Variables assignation and types
- How to import modules in Python
- Basic HTML tagging


## Software requirements
We recommend using the Anaconda distribution of Python. It's free and comes with a large number of additional modules included ready for importing into your scripts, IPython shell and notebook interfaces, a powerful Python text editor (Spyder), and a good package manager, conda, for updating and installing packages.

You need to have the following installed in your laptop for the course:
- Anaconda (get it from [here](https://www.anaconda.com/download/#macos))
- Python > 3.5
- pip
- Jupyter notebooks (already installed with Anaconda)
- beautifulsoup4
- requests
- scrapy
- lxml
- shell (we recommend using git bash: installed with Git or [cmdr](http://cmder.net) )

✨ The easiest/fastest way to get this is to download and install Anaconda. Make sure to add it to your Path during installation.
Once you have Anaconda installed open your shell (terminal/command line) and clone this repository:
```bash
$ git clone https://github.com/trallard/WebData_Python.git
```

Then navigate to the directory containing the materials for the session. So if you have them in Documents/WebData_Python you'll type:
```bash
$ cd Documents/WebData_Python
```

Next, we'll use conda environments to install all the needed packages we need for the course:
```bash
$ conda env create -f environment.yml
```

Finally, you need to activate the environment you just created:
```bash
$ source activate webdata
```
 To deactivate the environment you can do it like so:
 ```bash
 $ source deactivate
 ```

 # Course content

 1. [Introduction to regular expressions]:

 ## Acknowledgements

 The development of this material was funded by [OpenDreamKit][odk],
 a [Horizon2020][h2020] European [Research Infrastructure][res-inf] project ([676541][odk-grant]) that aims to
 advance the open source computational mathematics ecosystem.

 <div align="center">
 <img src="assets/opendreamkit.svg" alt="OpenDreamKit logo" height=200em />
 </div>

 ---
 <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


 [odk]: http://opendreamkit.org/
 [h2020]: https://ec.europa.eu/programmes/horizon2020/
 [res-inf]: https://ec.europa.eu/programmes/horizon2020/en/h2020-section/european-research-infrastructures-including-e-infrastructures
 [odk-grant]: http://cordis.europa.eu/project/rcn/198334_en.html
 [uos-rse]: http://rse.shef.ac.uk
