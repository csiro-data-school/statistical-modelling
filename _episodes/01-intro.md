---
title: "Statistical thinking"
questions:
- "Why do we need statistics?"
---

> ## Discussion
> Why do we need statistics?
> - not intended to confuse people
> - variation. Can't reliably get the same number when we measure something.
> - imagine a world where everything is deterministic. Then we could treat one plant to find out if a treatment works. Can't do this because of variation.
> - we quantify variation, we partition the variation we see in a response to genotypes. 
{: .discussion}

Statistics in biology is the study of biological variation. Statical ideas about biological variation inform the design of experiments. What are the sources of variation? Statistical thinking is an essential componet of scientific thinking. 

What are the sources of variantion? E.g. experiment on temperature ... humidity, environmental conditions, technician, instrument, chemicals or reagents, biological variation. 
What can we influence? WHich plants get which treatement. Begin by thinking about what are the potential sources of variation. E.g. position on field. Then think about how to design experiments to separate 

E.g. tomato plant. Have mutant that is drought resistant. Put mutant on bottom, wild type on top shelf. Enough samples to account for variation. BUt, fundamental mistake. Shelf is a source of variation. Can't separate the genotype effect from the shelf effect. Solution: randomise the location of the plants. Take home message: statistical ideas begin when we design the experiment, not when we get the data. 

We need to incorporate the design of the experiment in our analysis. 
Statistics is a framework, bones of scientific thinking over top of which you can apply your domain knowledge. Bring your data to dress the skeleton. 

History of stats. Goes back about 100 years to Fisher: 1890 to 1962. 'Statistical principles for Research Workers' (1925). 
Pictures and wiki link.

Was a mathematician. Fundamental contributions in statistics and genetics. Were really one field up until the 40s. Statistics is embedded in agricultural problems. Nitrogen and phospherous and field trials. Roots in places like CSIRO - used to be a place with a lot of statisticians. Came to CSIRO and spent end of his life in Adelaide. 

Common mistakes:
Many people know a little and have done a course of two in stats. However, lecturers don't really understand real-world problems in applied research institutes. This leads errors and misconceptions. 

1. A small p-value is not always evidence of a treatment effect. (research article - should we get rid of them?). What's at fault? The scientists (i.e. the interpretation). 

Insert P-value problem. 

Will adding rhizobacteria to soil improve N and phosphate absorption in roots?
* 8 plots / treatment
* take roots after 2 weeks
* pool samples, then sub-samples drawn
* outcome: relative mRNA expression of phosphate and N transporter genes in roots
* statistical method: t-test, Bonferroni correction p<0.05

What's the problem? A t-test compares the means. But, it's technical variation. Biological variation is bigger than technical variation. Technical variation will give us a smaller P-value. 

(image to show comparison of means)
how does it do this: look at sample means. Measure relative to amount of variation.

Problem: two different distributions, same means, what is the difference / which ones can you 

What are the words you need to understand?

* mean
* variation
* Standard Error: measure of uncertainty

2. p-values from simple comparisions cannot tell us when difference are 'different'.

Experimental set-up:
Are temperature mechanisms modified in a genetically modified tomato plant?
* Genotypes: WT/ Mutant
* Water conditions: Normal / Drought
* Leaf temperature measured. 

Two lots of t-tests to test effect of WT/ mutant by Normal / Drought.
