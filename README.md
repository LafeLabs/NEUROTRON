
# [TRASH MAGIC NEUROTRON](https://github.com/LafeLabs/NEUROTRON)

We aim to build a civilization centered on the living soil, in which all organic waste created by humanity is converted into soil with intention of creating a society where everything is free for everyone everywhere right now and where we shape the future of the climate by shaping the future of the soil.  To this end, we aim to build as many cybernetic feedback loops as possible between humanity and the soil.

We know that plants and fungi send very slow(seconds/minutes/hours) electrical signals to each other through the soil.    This is a system for using any regular old computer running any regular old operating system to record and publish signals detected in the living soil.  We avoid any kind of specialized data acquisition hardware by using the built in audio input and output that come with any modern computer. 

We use the [p5js](https://p5js.org/) [JavaScript](https://en.wikipedia.org/wiki/JavaScript) library to both create the sound and detect the response.  This library uses the [Fast Fourier Transform](https://en.wikipedia.org/wiki/Fast_Fourier_transform) to extract the power of the response as a function of frequency. 

The signal sent into the soil is a 1000 [Hz](https://en.wikipedia.org/wiki/Hertz) [sine wave](https://en.wikipedia.org/wiki/Sine_wave). If this signal goes into a [linear](https://en.wikipedia.org/wiki/Linear_system) medium with no noise, we will see only a response at 1000 Hz. If, however, there is some kind of [nonlinearity](https://en.wikipedia.org/wiki/Nonlinear_system), we can see mixing between the signal input into the soil and both much lower and much higher frequency signals. This can be seen as a kind of [parametric amplifier](https://en.wikipedia.org/wiki/Parametric_oscillator#Parametric_amplifiers), where the parameters of an oscillator are modulated in some way that gets amplified by the oscillation of the system.  Other examples of parametric amplifiers include [lasers](https://en.wikipedia.org/wiki/Laser), [masers](https://en.wikipedia.org/wiki/Maser), and [skateboard half pipes](https://en.wikipedia.org/wiki/Half-pipe) as well as numerous natural phenomena.

To run this system, first install the free web servers software [XAMPP](https://www.apachefriends.org/) on your computer, then make a subdirectory to the folder  in "C:\xampp\htdocs\"(this is for Windows, I'm not sure what it's called on mac or Linux) called NEUROTRON, and then copy the zip of this repository into that folder. Or, if you have Trash Magic installed, fork a folder with the following replicator link:

### [https://raw.githubusercontent.com/LafeLabs/NEUROTRON/refs/heads/main/php/replicator.txt](https://raw.githubusercontent.com/LafeLabs/NEUROTRON/refs/heads/main/php/replicator.txt) 

Then take the output of the audio of your computer and plug it into the soil, and connect from the output to either a microphone input or a speaker pointed at the microphone with minimal interference in a quiet place.  Ideally, you'll have just wires from the computer sound output to the soil and from the soil to the input. This way your web browser is directly connected to the living soil!  And by probing for nonlinearities, you can hunt directly for where you should get the most sensitivity. 

Once all this is set up, go to 

### [http://localhost/NEUROTRON/]

And click on the screen to start the 1000 Hz sine wave.  Try this right away, before getting the wiring set up!  You should see that you have built a primitive sonar, that waving your hand around by the speaker can be sensed by the response!

You can set how many points are taken in each plot and also how many averages per point there are to set the data rate. For testing, I usually start with 100 points an 1 average so that I can get data very fast. But for real data sets on plant and fungal systems, we probably want to slow down to more like 1000 points and 30-100 averages so that each data run is somewhere in the range of an hour. Then if you take data for a couple days, which is probably what is appropriate, that's only a couple dozen files. 

Files are saved as .svg files that can be seen by clicking the link to DATAFEED.  Also, you will want to [install Anaconda](https://www.anaconda.com/download), which is a system useful for scientific [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) that a huge range of science software exists for.  

Once Anaconda is installed, open an Anaconda prompt and run a Jupyter notebook as follows:

```
jupyter notebook --notebook-dir=C:\\xampp\\htdocs\\NEUROTRON
```
and then click on the file neurotronplots.ipynb from the Jupyter browser window to open the notebook. Then you use shift-enter to run the code cells to plot the data. My plotting routines are very primitive now, and this will need active research to get to where we have the routines we need to start analyzing large amounts of data. 

To publish your data, you can clone the repository into a local folder in the web folder and either publish to your own github repository or do a pull request and add it to this one. If we all publish data and teach other people how to publish data, we can build one giant networked data set that can be mined the same way that [SETI](https://en.wikipedia.org/wiki/Search_for_extraterrestrial_intelligence) mines astrophysical data.  But unlike in SETI, we know signals will be there, and there is already data in the scientific literature of some of what we are looking for. And also unlike SETI we can apply and observe various stimuli and observe resonses!

As all this scales up, we want to be building trash magic servers for media and other science which are used to get billions of these data sets at the global level as well as to run algorithms that blend the flow of data through the soil with the flow of data through society to build a more organic society based on more organic algorithms. Ultimately, this organic cybernetic system can be used to build a global organic civilization which can reverse climate change and build a sustainable civilization.


This documentation is woefully incomplete!  As we get more people interested, they can massively expand this!  This will only work if we can find ways to scale up to very large numbers of people and machines. Building this onto private windows and mac machines is how we start this but ultimately we want this to be all on Trash Magic servers outside of the system of private machines and property.


## USEFUL LINKS AND FILES

 - [datafeed.html](datafeed.html)
 - [gihtub repository](https://github.com/LafeLabs/NEUROTRON)
 - [hyperspace.html](hyperspace.html)
 - [index.html](index.html)
 - [editor.php](editor.php)
 - [webeditor.html](webeditor.html)
 - [edit.html](edit.html)
 - [fork.html](fork.html)
 - [neurotronplots.ipynb](neurotronplots.ipynb)
 - [http://localhost](http://localhost)
 - [dirt wizard on mastodon](https://cyberpunk.lol/@dirtwizard666)


[![](images/qrcode.png)](images/qrcode.png)
[![](images/qrcode-page.png)](images/qrcode-page.png)

## SYSTEM ELEMENTS
 
 - NEUROMORPHIC COMPUTING
 - LINGUISTIC CONTENT OF FUNGAL SIGNALS
 - PARAMETRIC AMPLIFIERS
 - NEURONS
 - MYCELIUM 
 - SOIL
 - TREES
 - P5JS
 - P5.SOUND
 - TRASH MAGIC
 - JAVASCRIPT
 - HTML
 - JUPYTER
 - PYTHON
 - NUMPY
 - MATPLOTLIB
 - PHP
 - JSON
 - XML
 - SVG
 - MARKDOWN
 - SHOWDOWN.JS
 - MATHJAX.JS
 - FFT
 - FOURIER TRANSFORM
 - QRCODES
 - QRCODE.JS
 - CSS
 - UNIX EPOCH
 - MIXER
 - HZ
 - GITHUB
 - XAMPP
 - GITHUB DESKTOP


