# School_District_Analysis
## Overview of the school district analysis:
A hypothetical school board planning meeting is occuring that will hinge on Distric analysis. The analysis has been completed with data regarding school name, size, type, number of students, math and reading grades, and budget numbers. 

It was discovered that one of the school's, Thomas High School, 9th grade test scores have been manipulated. In this analysis, I've removed those Thomas High School 9th grade scores and re-run the analysis with final figures. 


## How is the district summary affected?
The District Summary was marginally affected. The percentage of students passing math decreased by .2% and the percentage of students passing reading decreased by .1%. The overall passing (both math and reading) decreased by .2%. The average reading and math scores were nominally effected in no statisically significant way. 


District Summary before:
<img width="1045" alt="Screen Shot 2021-05-09 at 6 01 56 PM" src="https://user-images.githubusercontent.com/14239715/117588348-b594ce80-b0f0-11eb-970c-4b498b2fae4c.png">

District Summary after: 
<img width="1109" alt="Screen Shot 2021-05-09 at 5 54 55 PM" src="https://user-images.githubusercontent.com/14239715/117588159-b24d1300-b0ef-11eb-9226-80e381185e34.png">




## How is the school summary affected?
### School Summary 
The school summary was only affected on Thomas High school. 
The overall passing percentage decreased by .3 percent from 90.95 to 90.6%
the passing math went from 93.27 to 93.18%
and the passing reading moved from 97.3 to 97.01%

before:
<img width="1029" alt="Screen Shot 2021-05-09 at 6 04 41 PM" src="https://user-images.githubusercontent.com/14239715/117588465-6d29e080-b0f1-11eb-9db2-52791b9f7c82.png">

after:
<img width="1109" alt="Screen Shot 2021-05-09 at 6 07 06 PM" src="https://user-images.githubusercontent.com/14239715/117588454-656a3c00-b0f1-11eb-955a-8c483b757b12.png">






## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Although Thomas High School's percentage have become slightly lower, it still ranks at the second best performing high school. 

before:
<img width="1098" alt="Screen Shot 2021-05-09 at 6 21 25 PM" src="https://user-images.githubusercontent.com/14239715/117588741-656b3b80-b0f3-11eb-9e85-39287d46a2ff.png">

after:
<img width="1113" alt="Screen Shot 2021-05-09 at 6 22 09 PM" src="https://user-images.githubusercontent.com/14239715/117588753-7e73ec80-b0f3-11eb-90dd-6f8bd6e3ed57.png">

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
As you can see in the third and fourth chart below, Thomas High School reading and math scores for the 9th graders are not-a-number. 

before:
Chart 1: <img width="551" alt="Screen Shot 2021-05-09 at 6 27 48 PM" src="https://user-images.githubusercontent.com/14239715/117588873-4f11af80-b0f4-11eb-96f5-512aed3cd395.png">

Chart 2: <img width="442" alt="Screen Shot 2021-05-09 at 6 26 21 PM" src="https://user-images.githubusercontent.com/14239715/117588874-4faa4600-b0f4-11eb-9455-4edfc0e9b1ec.png">

Chart 3: <img width="435" alt="Screen Shot 2021-05-09 at 6 24 21 PM" src="https://user-images.githubusercontent.com/14239715/117588795-ceeb4a00-b0f3-11eb-8635-a9afb5a19bbc.png">

Chart 4: <img width="455" alt="Screen Shot 2021-05-09 at 6 24 09 PM" src="https://user-images.githubusercontent.com/14239715/117588796-ceeb4a00-b0f3-11eb-909c-baaa47e945dd.png">

## Scores by school spending
When all of the schools are aggregated to 5 spend buckets, the change in Thomas High School no longer has any effect.  
before:<img width="865" alt="spending_before" src="https://user-images.githubusercontent.com/14239715/117589133-bda33d00-b0f5-11eb-8ca0-915b97546d25.png">


after:<img width="945" alt="Screen Shot 2021-05-09 at 6 32 47 PM" src="https://user-images.githubusercontent.com/14239715/117588981-fee71d00-b0f4-11eb-822d-c30d27981855.png">


## Scores by school size
School size is an even higher level of detail that school spending as the values are aggregated into three buckets. There is no effect.

before: <img width="887" alt="Size before" src="https://user-images.githubusercontent.com/14239715/117589145-cdbb1c80-b0f5-11eb-8628-6e6860d9d39b.png">



after:
<img width="886" alt="Screen Shot 2021-05-09 at 6 33 23 PM" src="https://user-images.githubusercontent.com/14239715/117588989-10302980-b0f5-11eb-8e95-6a4e72a108b9.png">



## Scores by school type
There are only two types of school, Charter and District. At this level of even higher aggregation, the Thomas School Grade shift also has no effect. 
before:
<img width="840" alt="Screen Shot 2021-05-09 at 6 31 53 PM" src="https://user-images.githubusercontent.com/14239715/117588955-dbbc6d80-b0f4-11eb-9f9c-8af0f72424c9.png">

after:
<img width="912" alt="Screen Shot 2021-05-09 at 6 33 59 PM" src="https://user-images.githubusercontent.com/14239715/117589005-250cbd00-b0f5-11eb-96f7-5ebb7b181ecb.png">


# Summary: 

When the Thomas High 9th grade grades were replaces with NaN, the only effects were shown at the lowest level of detail, of this analysis. 

Below I discuss these effects at the most specific level of detail first. 

The school summary the only change was visible specifically on Thomas High school. The overall passing percentage decreased by .3 percent from 90.95 to 90.6%
the passing math went from 93.27 to 93.18% and the passing reading moved from 97.3 to 97.01%

In the district analysis, the level at which all of the schools in the district were aggregated, the percentage of students passing math decreased by .2% and the percentage of students passing reading decreased by .1%. The overall passing (both math and reading) decreased by .2%.

As more values were aggregated into higher levels such as at the overall school level in comparison to other schools (Top 5 performing schools), At the 5 levels of budgetary spend (amount per student spent in comparison to grade success), three levels of school size (small, medium, large) or two levels of school type (Charter or District), the 9th grade Thomas High grades had no effect. 



