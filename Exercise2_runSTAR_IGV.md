# Exercise II – run STAR Mapping and explore Alignment with IGV

1.	Select again initial raw dataset (NextSeq500...) in Sushi and select ‚STARApp’
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/E2_S1.png "Screenshot1")
2.	Select specific parameters for the reference and preprocessing options:
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/E2_S2.png "Screenshot2")
3.	Start job via ‚Next’ and ‚Submit’

4. Navigate to IGV Website and launch IGV with 750 MB option: 
http://software.broadinstitute.org/software/igv/download

![alt text](https://github.com/opitzl/CombinedCourse/blob/master/E2_S3.png "Screenshot4")

5.	Select corresponding reference in IGV:

*	If available  use ‚S. cerevisae R64’ otherwise ‚S. cerevisiae (sacCer3)’ 
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/E2_S4.png "Screenshot5")
6.	Load BAM-File(s) into IGV:

*	Copy URL for BAM-File from Sushi
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/E2_S5.png "Screenshot5")
*	Paste URL into IGV via File → Load from URL:
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/E2_S6.png "Screenshot6")
*	Repeat ‚Copy & Paste’ with another sample of the other condition to load one file per biological group (glucose & glycerol eth) 

7.	Search for Gene ‚YHR094C’ (=HXT1) and explore result

8.	Questions:

Is there a difference in gene expression for ‚YHR094C’ between the conditions?

What is the orientation of the reads in comparison to the reference (color alignment by read strand)?

(Are there genes with more than one exon in Yeast?)
