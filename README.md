# Stroop Task Analysis
A Python analysis of the classic Stroop interference effect, using _simulated experimental data_.

##What this project does

Here, reaction time (RT) data was simulated for a Stroop task with 30 participants (40 trials per condition). Interference effect was computed, followed by running a paired t-test. A graph visual was also produced.

##Key Result

Participants were significantly slower on incongruent trials (M ≈750 ms), than on congruent trials (M ≈650 ms), with a mean interference effect of ≈100ms. This result is consistent with the Classic Stroop finding.

##Methods
- Error trials excluded before RT analysis
- Absolute RT exclusions included <200 ms and >2000 ms
- Statistical tests used: paired-samples t-test (via scipy.stats)

##Tools used
- Python
- pandas
- numpy
- scipy
- matplotlib
- seaborn

##Background
BSc Psychology (Hons) with specialisation in Clinical. As my first Python project, I used a simulated Stroop task dataset to practice data generation, statistical analysis, and visualization using common scientific Python libraries.

##What I learned
- Simulating experimental data in Python
- Working with pandas DataFrames
- Computing descriptive statistics
- Running statistical tests via scipy.stats
- Visualising reaction time with matplotlib and seaborn
- - Structuring and documenting my first project on Google Collab and Github.
