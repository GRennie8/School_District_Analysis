# School District Analysis

## Project Overview

The purpose of this project was to analyze the data of an entire School Districts' grade scores for math and reading. The data was broken down to provide insights into the relevance of funding, school size and type of school. Upon completing the original analysis, the school board found there was some dishonesty regarding the test scores. As a result, the analysis was conducted one more time. This time the test scores for 9th grade in Thomas High School were to be replaced with NaN (Not a Number).

### How is the district summary affected?

There were 461 students in 9th grade at Thomas High School. Once their scores had been removed our results changed very minimally due to there being over 39000 students in the whole district. The "Total Students" number did not change because the student names and ID remain in the dataset, only their scores were replaced with NaN. I have shown the % passing values with 2 decimal places so the minimal differences can be seen.


Original analysis:
<img width="922" alt="district_analysis" src="https://user-images.githubusercontent.com/104115586/170851126-324114bd-acba-4d36-940a-74199349ecb3.png">

Updated analysis:
<img width="952" alt="new_district_analysis" src="https://user-images.githubusercontent.com/104115586/170851135-f2d7a15f-bb3c-48bc-88aa-774a472f1868.png">

### How is the school summary affected?


![Screen Shot 2022-05-28 at 9 22 52 PM](https://user-images.githubusercontent.com/104115586/170851673-5e9eac73-9a62-4468-bc1b-edf4e29b188d.png)

<img width="987" alt="Screen Shot 2022-05-28 at 8 52 45 PM" src="https://user-images.githubusercontent.com/104115586/170851677-54fbdf3e-b3aa-43cb-b8dc-9e93396b837b.png">

### How does using NaNs affect Thomas High School’s performance relative to the other schools?

<img width="989" alt="Screen Shot 2022-05-28 at 10 13 07 PM" src="https://user-images.githubusercontent.com/104115586/170851883-84f65723-e1a4-436f-bb3e-d0cf98274a4c.png">


After removing 9th grade completely from the DataFrame we find:

### Scores by school spending


  ![Screen Shot 2022-05-28 at 9 15 08 PM](https://user-images.githubusercontent.com/104115586/170851999-0310cd46-8380-4745-90bd-852088fdea8e.png)


<img width="824" alt="Screen Shot 2022-05-28 at 9 15 21 PM" src="https://user-images.githubusercontent.com/104115586/170852009-2be0dab1-f8e3-48a1-a1da-fb0b1d39d26e.png">

### Scores by school size

![Screen Shot 2022-05-28 at 9 15 58 PM](https://user-images.githubusercontent.com/104115586/170852059-668f69ff-e631-4fdf-a069-b674414c8643.png)

<img width="756" alt="Screen Shot 2022-05-28 at 9 16 05 PM" src="https://user-images.githubusercontent.com/104115586/170852067-df401a7b-0d2f-4806-b17a-a5e86fe01b32.png">


### Scores by school type

![Screen Shot 2022-05-28 at 9 17 28 PM](https://user-images.githubusercontent.com/104115586/170852071-90e54a63-62b6-4af6-bb28-f593aa545770.png)

<img width="718" alt="Screen Shot 2022-05-28 at 9 17 35 PM" src="https://user-images.githubusercontent.com/104115586/170852076-6bc846cc-23ff-4d62-9634-1734f06e6474.png">

## Summary
