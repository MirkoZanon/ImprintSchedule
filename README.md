# ImprintSchedule

ImprintSchedule is a custom graphic user interface written in Matlab (Matlab R2019a, The MathWorks Inc., Natick, Massachusetts, USA) and exploiting Psychtoolbox-3 (the Psychophysics Toolbox extensions; Brainard, 1997; Pelli, 1997) to set and control screen presentation during behavioral experiments.
The program is designed mainly for experiments with chicks, exploting the imprinting period and allowing the test of animals with a dual choice paradigm. 
 
This tool allows researchers to create their custom protocol of stimuli presentation to imprint and test animals, in a versatile but standardized and precise way without requiring computational skills.

Briefly, three different groups of PNG images can be loaded in ImprintSchedule: the first group represents what we call the ‘imprinting set’, while the other two are the ‘test sets’. The images loaded within the ‘imprinting set’ are presented to the animal one at a time on one of the two screens while the other is dark. The images loaded within the two test sets are displayed simultaneously, one per screen, allowing the animal to freely approach either one of them. 
Note that in the absence of an imprinting phase, the images loaded in the test sets can also be used to investigate the animals’ spontaneous preferences.
The presentation can be split into different steps, reported as days and sessions: the number of days and sessions per day can be set up, like the inter-trial intervals between them. If multiple images are loaded in one set (to present different stimuli during each phase), a new random stimulus image will be displayed during each different session. The order of presentation of the stimuli and the timing and screen positions are saved in an Excel file at the end of the experiment. 
To minimize any position bias, all the presentations on the two different screens can be controlled in a pseudo-random way, balancing the amount of time the same set of stimuli is presented on each side.
Since motion attracts the chick's attention, the program can display moving stimuli, creating a perceptively richer artificial environment. We implemented two different movements: a translatory motion, which consists of a horizontal oscillation of the image with a speed following a sinusoidal function (from which the amplitude and period of the oscillation can be controlled); a flickering motion, which consists of an appearance/disappearance of the image with user-defined timing. Even the vertical position of the image can be adjusted.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
RUN THE PROGRAM
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Requisites:
- Matlab (with Statistics and Machine Learning Toolbox installed)
- Psychtoolboox-3

Make sure to have a recent version of Matlab (2019 or later) and Psychtoolbox-3 (http://psychtoolbox.org/) installed.

In order to open the programs just drag and drop the file of interest in the Matlab terminal.
(If instead you want to visualize and modify the code, type ‘appdesigner’ in Matlab terminal and open the file of interest in the Matlab program that will appear).

If you find some bugs or you have suggestions to improve the program, please contact me: mirko.zanon@unitn.it

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
CITATION
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Please note that ImprintSchedule is based on a publication. If you use it successfully for your research please be so kind to cite our work:

Zanon M, Lemaire BS, Vallortigara G. Steps towards a computational ethology: an automatized, interactive setup to investigate filial imprinting and biological predispositions. Biol Cybern. 2021 Jul 17. doi: 10.1007/s00422-021-00886-6. Epub ahead of print. PMID: 34272970.
