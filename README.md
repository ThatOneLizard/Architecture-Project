# Architecture-Project
Repository for my 2026 Architecture class project

This project will involve using an Oz64 dev board along with a camera to run an AI model that I will train from my laptop first (since the board itself does not have a lot of space for training and will run very slow) to recognize specific objects. I'll also be adding a button that's hooked up to the GPIO to trigger the detection. For this project, I'll be using twenty sided dice from my D&D dice collection, since they come in a variety of shapes and colors that would help train the model to do better at detecting them.

## Timeline
10-16-2026 (Check in #2 (week 2?)): I have the parts I'll need to complete this assignment, as well as the AI model downloaded and ready to begin training.

10-27-26 (check in #3 (week 3)): I was under the impression last week that the model was ready to train, but I stood corrected. I needed to install a couple of extra packages in a virtual environment. This week I also gathered a dataset to train with (both image files and reference files to give the dimensions in the photos where the dice were).

11-4-2026 (Check in #4 (week 4)): This week's submission is the files created during last week's training session. I was preoccupied with exams and did not make much progress.

Check in #5 (: Haven't had the most amount of time to complete the project over the last few weeks, but have put several hours over the course of the last few days trying to finish up proper model training. The model is now in a state of working 95% of the time with proper lighting. Camera now detects dice and usually does not recognize other objects as dice. Most recent data set trained the model with roughly 8600 images. (See link in dataset_link.md for most recent dataset.)

In the coming week until the next (and final?) checkpoint, I plan to move the model to the board and revise bugs in code. Hopefully hooking it up to a button to run in this time as well.
