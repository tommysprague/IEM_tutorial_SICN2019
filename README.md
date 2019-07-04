# IEM_tutorial_SICN2019

Tutorial code presented at 2019 Kavli Summer Institute in Cognitive Neuroscience on July 4, 2019 with Justin Gardner

For data - please visit https://osf.io/wtmg2/ and download files into a "data" directory at the same level as the root folder of the repository

Tutorial files (the github repository) should be within a folder called IEM_tutorial_SICN2019; at that same level, there should be a folder called "data" with subfolders called "fMRI" and "EEG"

For any questions, please contact organizers Tommy Sprague (github.com/tommysprague) and Justin Gardner (github.com/JustinGardner)

We'll cover:
1. How to build an encoding model (`IEM_tutorial_walkthrough.mlx`)
2. How to fit that model to data (`IEM_tutorial_walkthrough.mlx`)
3. How to invert the encoding model to reconstruct channel response profiles (`IEM_tutorial_walkthrough.mlx`)
4. How to _decode_ feature values from channel response profiles (`IEM_tutorial_advanced.m`)

There are lots of topics we won't have time to cover in the tutorial session - these are covered in more detail in `IEM_tutorial_advanced_full.m` 

Students will have two options - they can either follow the tutorial available at http://gru.stanford.edu/doku.php/tutorials/channel, which involves writing simulation and analysis code from scratch, or follow the 'walkthrough' tutorials included here, which involve less coding and spend more time walking through implementation details. Feel free to switch, try both, etc! If you're getting bored with the _walkthrough files, try out the _advanced.m and _advanced_full.m files - those cover topics in much more detail, and allow you to step through different aspects of the analysis.

## FILES:
- `IEM_tutorial_walkthrough.mlx` - interactive MATLAB "live notebook" of tutorial on fundamentals of implementing IEM analyses in fMRI or EEG (includes recommended exercises - will not run without completing these exercises) - look at `IEM_tutorial_walkthrough.pptx` for step-by-step narration
- `IEM_tutorial_walkthrough_withAnswers.mlx` - 'complete' version of above, with 'answers' to exercises - will run as downloaded
- `IEM_tutorial_walkthrough_script.m` - same, as .m file (in case using older version of matlab)

- `IEM_tutorial_advanced.m` - ready-to-go set of advanced analysis routines - should run as downloaded (covered in SICN 2019)
- `IEM_tutorial_advanced_full.m` - even more analyses - includes several topics not addressed during SICN 2019 course

We won't cover this explicitly, but for an example of how to simulate data from multiple conditions and compare results across conditions (and across arbitrary transformations to the basis set), see:
- `IEM_sim_simple.m` - copy of code in github.com/JohnSerences/iem_sim which implements fixed encoding models and differences across conditions, as well as invertible linear transforms applied to basis sets (see Gardner & Liu, 2019, eNeuro and Sprague, Boynton & Serences, pp2019, bioRxiv)

(participants who complete the web-based tutorial on gru.stanford.edu will simulate data themselves as well)