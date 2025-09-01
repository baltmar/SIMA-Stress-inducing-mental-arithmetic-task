# SIMA: Stress-inducing mental arithmetic task

## Overview



This repository contains the materials for a stress-inducing task named **"SIMA: Stress-inducing mental arithmetic task"**, developed by Margarida Baltazar and Marianne Taipale at the University of Jyväskylä.

The task runs locally (offline) and aims to induce stress in participants for various experimental purposes in lab settings. The stressors in the task are: arithmetic cognitive load, time pressure, task difficulty, and negative feedback.

It was created using PsychoPy Builder (v2024.1.1), but it also includes code components.



## Features of the task



* Arithmetic questions on screen.
* Timed answers with visible timer.
* Increasing difficulty.
* The answer is given by typing on the keyboard and pressing enter.
* If time runs out or the answer is incorrect, participants receive the feedback: Incorrect
* The task is programmed to end after 5 minutes, regardless of how many questions are left.
* If the participant goes through all the questions in 5 minutes, the test shuffles through the same question bank until the time is up.

*\[Note: There are 85 questions in the file 'conditions\_math\_A.xlsx' (and in its B version, 'conditions\_math\_B.xlsx'), which would take 14 minutes to complete when spending 10 seconds per question. It would require a participant to take less than 3.5 seconds per question to be able to finish all under 5 minutes.]*







## Contents

* SIMA\_task.psyexp: The PsychoPy Builder file.
* conditions\_math\_A.xlsx: The arithmetic questions presented during the task.
* version B: Folder containing the files that allow a second stress induction in the same session, with the same participants.

  * SIMA\_task\_B.psyexp: The PsychoPy Builder file set to call the version B stimuli (questions).
  * conditions\_math\_B.xlsx: A different, but similar, set of arithmetic questions presented during the second run of the task.
  * README.md: Readme file for version B.

* images: screenshots of the math task
* LICENSE.txt: applicable license to this software
* README.md: This file.
* .gitignore



## Requirements

* PsychoPy Builder \[version has been locked to 2024.1.1 to be sure that any new version will be able to run this program as intended].
* conditions\_math\_A.xlsx or conditions\_math\_B.xlsx: the stimulus file needs to be downloaded to the same folder and linked to the experiment.



## Running the Experiment

1. Download 'SIMA\_task.psyexp and 'conditions\_math\_A.xlsx' and save them on the same folder
2. Open 'SIMA\_task.psyexp' in PsychoPy Builder.
3. Ensure all stimulus paths are correct.
4. Click **Run** to start the experiment.



## Language



The test is in English, but minimal language knowledge is needed.







# Funding and research project



This program was developed as part of the MUSICONNECT project, funded by the European Research Council (ERC) under the European Union’s Horizon Europe research and innovation programme (grant agreement No 101045747).





# Citation

Baltazar, M., \& Taipale, M. (2025, September 1). SIMA: Stress Inducing Mental Arithmetic task. Retrieved from [osf.io/5t2yh](osf.io/5t2yh)









## Related work



This task was initially developed for the study "Music listening for stress alleviation: A mixed method experiment"
[Project's page in osf.io](https://osf.io/vdyg8/)

[Study's registration](https://doi.org/10.17605/OSF.IO/MF68A)





# Contact



margarida.baltazar@jyu.fi

