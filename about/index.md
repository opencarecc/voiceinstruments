---
layout: default
title: About
published: true
ref: about
lang: en
---

# About page
<b>Voice Instrument</b> is an open source interface designed for speaking numeric values and service messages to meet the needs of people <b>unable to read</b> or  in contexts where it is <b>uncomfortable to use the display</b> to read values on a monitor.
<br><br>
The project was born because working in a chemistry lab I felt the need to build a <b>talking PH-meter</b> whose technology could be included in other contexts and allow others to connect devices to the voice interface.

<img src="https://github.com/opencarecc/voiceinstruments/blob/gh-pages/assets/VI-home-img.jpg" alt="VI-home-img">
<blockquote><i>Voice Instruments' first pH-meter prototype</i></blockquote>

### SCENARIO
The majority of electrical equipment currently available on the market consists of a <b>visual output device</b>, that communicates and interacts with the user through a visual display.
<p>
Some devices, however, are also equipped with a <b>voice interaction system</b>, that allows users to utilize this technology without using their sight.
Nevertheless, the totality of these electrical devices equipped with an alternative interface is very narrow and confined and is often regarding popular customary appliances, such as smartphones, domestic or medical scales.
</p>
In Italy, therefore, finding <b>“voice instruments”</b> (as weather stations, domestic thermostats, washing machines or digital multimeters) is quite difficult, if not impossible.

# Journey
Initially, while working in a chemistry lab, I thought about building a measuring instrument particularly useful in these contexts: a speaking pH-meter.
During the opencare Maker in Residence programme I produced, together with WeMake staff and makers, the first prototype of the speaking pH-meter, according to the requirements that we defined at the beginning of this journey. In addition we developed two complete guideline libraries to manage the enunciation of the numerical values and service messages, functioning with the most common audio modules, that can be used with the majority of sensors and devices available on the market.

In order to develop the first prototype of the speaking pH meter we analysed the test project and, subsequently, we conducted market researches in order to select the most suitable components to the final aim and finally, according to them, we designed the PCB.
After defining the PCB specifications we designed a case that could contain the PCB itself and the components.
The current version of the case was realized in lasercut plywood. This material has been chosen mainly because of its cheap price and it’s acoustic affinity.
The libraries have been conceived in order to read numeric values and service messages, and in order to function with two of the most common audio modules. The algorithm that has been used to read the values, however, could function with any other module.

# Next steps
Currently these numeric values are read by this interface in Italian language. Future developments of this project, however, involve using innovative components, adding support for foreign languages and, possibly, realizing a real speech synthesis system, based on a micro controller.

# Team
My name is Giulio Berretta, I am 27 years old, graduated as an Industrial Chemical Engineer and with a Master of Science degree in Electronic Engineering at the Politecnico di Milano. I work as a teacher in a chemistry and physics lab. Since 2008 I am a member of the Italian Union of Blind and Visually Impaired, since 2017 I am honorary member of the Academy of Light.
