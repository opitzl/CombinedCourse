# Exercise III – Quantification & Differential Expression

1. Select dataset from STAR mapping (STAR_...) in Sushi and run ‚FeatureCountApp’ with default options.

![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E3_S1.png "Screenshot1")

2. Run CountQCApp on resulting dataset with option runGO=true

![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E3_S2.png "Screenshot2")

3. Explore resulting ‚Static Report’:

 Are the samples clustering by biological condition (dendrograms in ‚Sample Clustering’)? 

 Is it worth to generate more reads for underrepresented libraries?
  
  Hint: Compare under Count Statistics ‚totalReads’ vs. ‚GenomicFeaturesWithReadsAboveThreshold’ 

4. Run EdgeRApp on featureCounts-dataset with options

 sampleGroup=Glyc_Eth 

 refGroup=Glucose 

 runGO=true

 It will compare Glyc_Eth vs. Glucose.

5. Explore ‚Static Report’:

 How many genes are regulated with FC>2 & pValue<0.001 in comparison to all present genes?

 Are more genes up- or down-regulated?

 What is foldChange and pValue for YHR094C (HXT1, Glucose Transporter)?
