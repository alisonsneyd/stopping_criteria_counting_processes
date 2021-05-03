# stopping_criteria_counting_processes
This repository contains the code needed to run experiments in  the paper "Stopping Criteria for Technology-Assisted Reviews based on Counting Processes" by Alison Sneyd and Mark Stevenson, SIGIR 21.

Data is available at https://github.com/CLEF-TAR/tar. A copy of the file https://github.com/CLEF-TAR/tar/blob/master/2017-TAR/participant-runs/Waterloo/B-rank-normal.txt should be placed the directory data/runs2017_table3/Waterloo/ of this repository, and a copy of https://github.com/CLEF-TAR/tar/blob/master/2017-TAR/testing/qrels/qrel_abs_test.txt should be placed in data/relevance/. To replicate experimental results, the notebook run_stopping_point_experiments.ipynb should then be run.

Requirements:\
python==3.6.3\
numpy==1.19.5\
pandas==0.23.4\
scipy==1.5.4

