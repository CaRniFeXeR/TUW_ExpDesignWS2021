
This is only a draft, the real report is on [Overleaf](https://de.overleaf.com/project/61e04c40bc88877b64d5e22d).

## The Analyzed Paper
- describe domain
- describe sampling strategy
- describe results (maybe include plot from original paper)

## The Original Paper
- describe domain
- describe sampling strategy
- describe difference to analyzed paper

## Found Resources 
- list and describe found / used resources

## Steps Taken
- used github code of authors
- collected correct package versions
- rerun provided code --> same results
- loaded original (last fm ) dataset
- reproduced authors sampling
- rerun provided code with reproduced sampling --> not same results
- defined percentile sampling and rerun provided code with reproduced sampling

We used the Jupyter Notebooks provided by the authors on GitHub to rerun their calculations. Since they only provided a list of used package without explicit package versions, we tried to reconstruct which versions were most likely used. The original paper was submitted on the 10th of December 2019. All versions of the required libraries were chosen to correspond to the latest stable version at this date. As python 3.8.0 was the latest major python release by the time the paper was submitted (https://www.python.org/downloads/) this version was chosen.

With the jupyter notebooks, external dependencies and the preprocessed data of the author provided on [Zenodo](https://zenodo.org/record/3475975#.YeBSdVkxlPY) we were able to execute the authors code. These results were the same as stated by the authors in their paper.

The first thing we noticed is that the sampling in the analyzed paper differs from the original paper. As described, above
they order the users by mainstreamness 
