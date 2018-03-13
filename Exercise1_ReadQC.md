# Exercise I – ReadQC

1. Navigate to Sushi Demo Server: http://fgcz-sushi-demo.uzh.ch
2. Enter your project ID in the field: e.g. 1001, 1002 etc.
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S1.png "Screenshot1")
3. Select „DataSet“ to get a listing of existing DataSets in your Project. 
There should be only one dataset which contains the meta-information of the raw data:
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S2.png "Screenshot2")
4. Click on the name of this dataset to see the details, to list all Apps and to select FastqcApp
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S3.png "Screenshot3")
5. Keep default options and continue with ‚Next’:
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S4.png "Screenshot4")
6. Start the actual job with ‚Submit’: 
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S5.png "Screenshot5")
7. Go back to main page via ‚Today’s Menu’:
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S6.png "Screenshot6")
8. Repeat Step3 and explore the new dataSet ‚Fastqc_....’ . After 1-3 minutes a link to the FastQC-report should be available. Select this link to open the report
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S7.png "Screenshot7")
9. Explore the FastQC-Report
![alt text](https://github.com/opitzl/CombinedCourse/blob/master/images/E1_S8.png "Screenshot8")
10. Questions: 

Quantity:

* Are there under/overrepresented libraries?

Quality:

* Are there differences in quality scores across all bases?

* Was an adapter contamination detected? Are there differences across the libraries?

* Do you see a relationship between GC-content and adapter content/primer dimers?

→ What could be a good preprocessing strategy for our data?
