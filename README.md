# Attentional-Blink-Task
PsychoPy RSVP task for my psychology dissertation
How to Cite: [![DOI](https://zenodo.org/badge/1422592796.svg)](https://doi.org/10.5281/zenodo.23424979)

## Overview
This repository contains a PsychoPy-based Rapid Serial Visual Presentation (RSVP) paradigm designed to measure visual temporal attention and the "Attentional Blink" effect. It was originally developed as part of an undergraduate dissertation investigating the impact of academic burnout on cognitive processing speed.

## Task Description
Participants monitor a rapid stream of central letters to identify two target numbers (T1 and T2) embedded within the stream. 
* **Stimuli:** Rapidly presented letters and numbers.
* **Lags:** The task measures accuracy of T2 detection at various lags (e.g., Lag 2 vs. Lag 8) following T1.
* **Practice:** A short 4-trial practice block is included to familiarize participants with the keyboard responses before the main task.

## Repository Contents
* `AB paradigm.psyexp`: The main 80-trial experimental task.
* `Practice_RSVP.psyexp`: A short 4-trial practice version of the task.
* `conditions.csv`: The conditions file dictating the target lags and timing.

## How to Run
1. Download or clone this repository to your local machine.
2. Ensure you have [PsychoPy](https://www.psychopy.org/) installed.
3. Open `Practice_RSVP.psyexp` in PsychoPy Builder to run a participant through the practice trials.
4. Open `AB paradigm.psyexp` in PsychoPy Builder to run the main data collection phase.

## Author
**Tamanna Joshi**  
B.A. (Hons.) with Research in Psychology, Banasthali Vidyapeeth

## How to Cite
If you use this paradigm in your research, please cite it using the Zenodo DOI badge at the top of this page.
