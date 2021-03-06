### Research & Planning Log
#### 2/18/22
0800 - 1000: Read through language documentation and tutorials on [C++](www.cplusplus.com) while writing small programs in Visual Studio to test my learning.

1030 - 1050: Prepared [README.md](./README.md) and [capstone-proposal.md](./capstone-proposal.md)

1050 - 1200: Continued with documentation and tutorials on [C++](www.cplusplus.com).

1520 - 1550: Reviewed some example plugin source code for [iPlug2 library](https://iplug2.github.io/) to see how well I could decipher it with some understanding of C++. Read the [iPlug2 whitepaper](https://raw.githubusercontent.com/iPlug2/iPlug2/master/Documentation/Papers/WAC2018.pdf) which gives a high-level view of the library's capabilities.

1600 - 1645: Worked through [getting started tutorial](https://github.com/iPlug2/iPlug2/wiki/02_Getting_started_windows) for iPlug2. Succesfully opened example project in Visual Studio and built standalone and VST3 plugins from the example project.

1645 - 1700: Explored various examples included in plugin repo to try to get a grasp on general structure of a plugin and some of the parameters used.

##### Hours 2/18: 5:00

#### 2/20/22
1300 - 1415: Read about digital sound processing (DSP) techniques and filter design from [Computer Music](https://www.amazon.com/Computer-Music-Synthesis-Composition-Performance/dp/0028646827), one of my college textbooks, to refresh my memory on some concepts.

1415 - 1505: Worked through example plugin project and referenced against [iPlug2 documentation](https://iplug2.github.io/iPlug2/index.html) to better understand how parts of the solution are connected to eachother to process signal flow.

1900 - 2000: Creative exploration / analyzed and "broke down" the parameters of physical guitar pedals and listening to effected sound samples to think about possible ways to recreate the effects in a digital plugin.

##### Hours 2/20: 3:05

#### 2/25/22
0910 - 1135: Finished reading through the tutorials / language introduction on [C++](www.cplusplus.com).

1215 - 1330: There are no tutorial series I can find for iPlug2, so I worked through the [tutorials for the original iPlug library by Martin Finke](http://www.martin-finke.de/blog/tags/making_audio_plugins.html). This was time consuming - there are a lot of differences in the basic structure of a plugin between versions.
* 1315: Got simple digital distortion to work.

1600 - 1715: Continue working through tutorials. Trying to add an oscillator but version differences in file structure make it confusing.

##### Hours 2/25: 4:55
---
_At this point, I decided to explore an alternate framework with better documentation._

---

#### 2/28/22
1240 - 1310: Worked through installation and [getting started tutorial](https://docs.juce.com/master/tutorial_new_projucer_project.html) for [JUCE](https://juce.com/), an alternate C++ audio plugin framework.

##### Hours 2/28: 0:30

#### 3/1/22
1225 - 1300 Started working through [basic plugin tutorial](https://docs.juce.com/master/tutorial_create_projucer_basic_plugin.html) using JUCE, reviewed template code for a basic plugin to try to parse meaning.

##### Hours 3/1: 0:35

#### 3/4/22
1015 - 1115: Continued with [audio plugin tutorial](https://docs.juce.com/master/tutorial_create_projucer_basic_plugin.html) for JUCE. Succesfully completed tutorial for linking a slider to modify incoming midi messages. Learned about Visual Studio debugger and build configuration.

1420 - 1530: Continued with tutorials (topics: audio processing blocks, white noise generation, sine wave generation using std::sin).

##### Hours 3/4: 2:10

#### 3/6/22
1030 - 1130: Practiced implementing code I'd reviewed: added a new slider for level to an example project and implemented frequency and level smoothing through interpolation.

1140 - 1200: Worked through tutorial on adding parameter control to a plugin (allows host application to automate plugin values over time for expression).

1400 - 1500: Worked through additional [demo plugin tutorials](https://docs.juce.com/master/tutorial_plugin_examples.html) and began [introduction to DSP tutorial](https://docs.juce.com/master/tutorial_dsp_introduction.html) which explains how to do several DSP things including filters.

1900 - 2010: Continued with DSP tutorial.

2245 - 2315: Mocked up plugin GUI design in Figma.

##### Hours 3/6: 4:00

#### 3/7/22

0900 - 0930: Thought about design of capstone plugin and made a list of items to implement. Updated plugin GUI design accordingly.

0930 - 1000: Read about comb filter design, reviewed examples.

##### Hours 3/7: 1:00

#### 3/8/22

0830 - 1030: Read tutorial about delay in JUCE (essential element for comb filter design).

##### Hours 3/8: 2:00

#### 3/9/22

0830 - 1015: Read tutorials on FFT and how to make a display of frequency spectrum analysis.

1145 - 1200: Reviewed some tutorials on JUCE components (display and control items).

##### Hours 3/9: 2:00

#### Cumulative Hours: 25:15