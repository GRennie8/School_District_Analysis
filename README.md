# School District Analysis

## Project Overview

The purpose of this project was to analyze the data of an entire School Districts' grade scores for math and reading. The data was broken down to provide insights into the relevance of funding, school size and type of school. Upon completing the original analysis, the school board found there was some dishonesty regarding the test scores. As a result, the analysis was conducted one more time. This time the test scores for 9th grade in Thomas High School were to be replaced with NaN (Not a Number).

### How is the district summary affected?

There were 461 students in 9th grade at Thomas High School. Once their scores had been removed our results changed very minimally due to there being over 39000 students in the whole district. The "Total Students" number did not change because the student names and ID remain in the dataset, only their scores were replaced with NaN. I have shown the % passing values with 1 decimal place so the minimal differences can be seen.


**Original analysis:**
<img width="750" alt="district_analysis" src="https://user-images.githubusercontent.com/104115586/170851126-324114bd-acba-4d36-940a-74199349ecb3.png">

**Updated analysis:**
<img width="750" alt="new_district_analysis" src="https://user-images.githubusercontent.com/104115586/170851135-f2d7a15f-bb3c-48bc-88aa-774a472f1868.png">

### How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate. It was the second highest performing school in the district. 

![Screen Shot 2022-05-28 at 9 22 52 PM](https://user-images.githubusercontent.com/104115586/170851673-5e9eac73-9a62-4468-bc1b-edf4e29b188d.png)

### How does using NaNs affect Thomas High School’s performance relative to the other schools?

Removing the 9th grade students from the data set and replacing them with NaNs had a huge impact on the overall passing rate, by dropping from 91% to 65%. This moved Thomas High School down to 8th in the school summary.

<img width="750" alt="Screen Shot 2022-05-28 at 8 52 45 PM" src="https://user-images.githubusercontent.com/104115586/170851677-54fbdf3e-b3aa-43cb-b8dc-9e93396b837b.png">

The DataFrame below was created once the 9th grade scores had been removed completely and displays the scores for 10th to 12th grade only. By making this change, we can see that Thomas High School is in 2nd position once again.

<img width="750" alt="Screen Shot 2022-05-28 at 10 13 07 PM" src="https://user-images.githubusercontent.com/104115586/170851883-84f65723-e1a4-436f-bb3e-d0cf98274a4c.png">

Evidence of the NaN values for 9th grade at Thomas High School.

<img width="380" alt="Screen Shot 2022-05-28 at 8 59 11 PM" src="https://user-images.githubusercontent.com/104115586/170899768-d8a4becf-7e87-4dc1-9e57-0d104dad7786.png">  <img width="380" alt="Screen Shot 2022-05-28 at 8 59 30 PM" src="https://user-images.githubusercontent.com/104115586/170899774-10522f32-4d38-4859-a2d5-aefbe48c014c.png">


### Scores by school spending

Thomas High School falls into the spending range of $631-$645 per student. After removing the 9th grade scores, we can see there is an extremely minor difference between the two values - 0.8% to be exact. The values have been left unformatted to show the nominal changes.

**Original analysis:**

![Screen Shot 2022-05-28 at 9 15 08 PM](https://user-images.githubusercontent.com/104115586/170851999-0310cd46-8380-4745-90bd-852088fdea8e.png)

**Updated:**

<img width="850" alt="Screen Shot 2022-05-28 at 9 15 21 PM" src="https://user-images.githubusercontent.com/104115586/170852009-2be0dab1-f8e3-48a1-a1da-fb0b1d39d26e.png">

### Scores by school size

Thomas High School has 1635 students, so it is classed as a "Medium" sized school. Removing the 9th grade scores caused the % scores to decrease very minimally. The values have been left unformatted to show the nominal changes.

**Original**:
![Screen Shot 2022-05-28 at 9 15 58 PM](https://user-images.githubusercontent.com/104115586/170852059-668f69ff-e631-4fdf-a069-b674414c8643.png) 

**Updated:**
<img width="756" alt="Screen Shot 2022-05-28 at 9 16 05 PM" src="https://user-images.githubusercontent.com/104115586/170852067-df401a7b-0d2f-4806-b17a-a5e86fe01b32.png">


### Scores by school type

Thomas High School is a Charter school. Removing the 9th grade scores caused the % Overall Passing to drop more than 3%.

**Original**:
![Screen Shot 2022-05-28 at 9 17 28 PM](https://user-images.githubusercontent.com/104115586/170852071-90e54a63-62b6-4af6-bb28-f593aa545770.png)

**Updated**:
<img width="718" alt="Screen Shot 2022-05-28 at 9 17 35 PM" src="https://user-images.githubusercontent.com/104115586/170852076-6bc846cc-23ff-4d62-9634-1734f06e6474.png">

## Summary

By conducting the comparative analysis, four major changes are evident after reading and math scores for 9th grade Thomas High School students were replaced with NaNs.

1. Utilizing NaN is an effective way to capture inconsistencies in a dataset, without manually having to enter zeros in place of the values in question.
2. School spending ranges per student do not impact math and reading scores.
3. School size has an impact on testing scores. The larger the school size, the lower the test scores and percentage of overall students passing.
4. Charter Schools perform better than District Schools, as they have higher testing scores and percentages of overall students passing.



