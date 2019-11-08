# Joint Analysis of Functional Genomic Data and Genome-wide Association Studies of 18 Human Traits

## DOI

https://dx.doi.org/10.1016%2Fj.ajhg.2014.03.004

## Journal

AJHG

## Problem

Incorperating multiple types of annotations to re-discover GWAS signals.

## Method

Related to Veyrieras et al (2008) (Stephens lab), but

- Formulating with Wakefields's approximate BF calculations
- Adding in a shrinkage penalty to the logistic link for annotations and use a 10-fold CV for it
    - And also additionally use some heuristic rules to select the model
- Posterior is given as Maller et al (2012)

For data analysis

- Use GWAS summary data and ImpG (Pasaniuc B et al) to impute summary stats

## Result

More interesting to read the application of fGWAS to 42 traits at https://dx.doi.org/10.1038%2Fng.3570

## Comment

1. As with many similar approaches (eg Wen 2016 AoAS) the selected annotations are not identifiable and interpretable themselves when they are highly correlated.
    - The author indeed discussed this issue in a section "Conditional analysis"

## KW

Joe Pickrell, BVSR, annotation