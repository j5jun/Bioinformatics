# Put title here (title should be informative, not copied from the tutorial title!) (0.5 pt)
##### your name

## Abstract (0.5 pt)

## Introduction (2 pts)

2-3 paragraphs max
* What question(s) sare we trying to answer?
* Why is this question important?

## Methods (2 pts total)

Break your methods section into subheadings for each of the following 3 topics, with 1 paragraph for each:

### RNA-seq datasets (0.5 pts)
* Describe the datasets you're working with. What tissues were the RNA-seq datasets from? How many reads were in each experiment? What read lengths? Paired or single end?
* Describe and interpret anything flagged by `fastqc`.
* WHat reference genome was used throughout the lab? This is always important to note for enabling other people to reproduce your analysis

### RNA-seq analysis (1 pt)
* Describe how you used kallisto to quantify transcripts. What version did you use? What non-default parameters did you use and why?
* Describe how you used sleuth to identify differentially expressed transcripts. What False Discovery Rate (q-value) threshold did you use?

### Enhancer analyses (0.5 pts)
* Describe the datasets you visualized on IGV. 
* What tools did you use for the multiple sequence alignment and visualization? Mention any non-default parameters.
* What tool and database did you use for motif identification.

## Results (2 pts total)

Break your methods section into subheadings for each of the following two topics. You may have 2-3 paragraphs max for each. Make sure each figure is clearly referenced in the text.

### RNA-seq analysis (1 pt)
* How comparable were the RNA-seq replicates? Which 2 tissues were most similar? Include a figure or table summarizing your pairiwse analysis of each RNA-seq dataset.
* How many diffentially expressed transripts did you find? Include screenshots of several examples from IGV.

### Enhancer analysis (1 pt)
* Describe the general signal you see for H3K4me1 and H3K27ac. Where do these marks tend to fall? In introns? beginning of genes? end of genes? Do they look different between the different samples? Hypothesize why. Similarly describe the PhyloP track.
* Describe the pattern of these signals in the ZRS region.
* Provide a figure for the MSA results. Are there any sequences missing in snakes that are present in all other animals analyzed?

## Discussion (2 pts)
* Summarize your analysis of the ZRS region and your interpretation of its involvement in determining whether an organism develops limbs or not.
* We identified the ZRS region based on knowledge from previous literature. Are there other enhancers that appear to be both limb-specific an highly conserved nearby Shh? If you wanted to identify these regions computationally how would you do it?
* Do you have any hypotheses about why the identified mutations might lead to a loss of legs in snakes? What further experiments or analyses could be done to determine the function of this sequence?

## Citations (1 pt)
Include at least one citation

