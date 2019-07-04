# IEM_tutorial_SICN2019

Tutorial code presented at 2019 Kavli Summer Institute in Cognitive Neuroscience on July 4, 2019 with Justin Gardner

For data - please visit https://osf.io/wtmg2/ and download files into a "data" directory at the same level as the root folder of the repository

Tutorial files (the github repository) should be within a folder called IEM_tutorial_SICN2019; at that same level, there should be a folder called "data" with subfolders called "fMRI" and "EEG"

For any questions, please contact organizers Tommy Sprague (github.com/tommysprague) and Justin Gardner (github.com/JustinGardner)

## FILES:
- `IEM_tutorial_fundamentals.mlx` - interactive MATLAB "live notebook" of tutorial on fundamentals of implementing IEM analyses in fMRI or EEG (includes recommended exercises - will not run without completing these exercises)
- `IEM_tutorial_fundamentals_withAnswers.mlx` - 'complete' version of above, with 'answers' to exercises - will run as downloaded
- `IEM_tutorial_fundamental_script.m` - same, as .m file (in case using older version of matlab)

- `IEM_tutorial_advanced.m` - ready-to-go set of advanced analysis routines - should run as downloaded (covered in SICN 2019)
- `IEM_tutorial_advanced_full.m` - even more analyses - includes several topics not addressed during SICN 2019 course

- `IEM_sim_simple.m` - copy of code in github.com/JohnSerences/iem_sim which implements fixed encoding models and differences across conditions, as well as invertible linear transforms applied to basis sets (see Gardner & Liu, 2019, eNeuro and Sprague, Boynton & Serences, pp2019, bioRxiv)