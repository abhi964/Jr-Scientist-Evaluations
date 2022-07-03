# Jr-Scientist-Evaluations
PART 1

PART 1 Q1:

Write a regex to extract all the numbers with orange color background 
from the below text in italics.

data = {"orders":[{"id":1},{"id":2},{"id":3},{"id":4},{"id":5},{"id":6},
       {"id":7},{"id":8},{"id":9},{"id":10},{"id":11},{"id":648},{"id":649},
       {"id":650},{"id":651},{"id":652},{"id":653}],"errors":[{"code":3,
       "message":"[PHP Warning #2] count():Parameter must be an array or 
        an object that implements Countable (153)"}]}

I have noticed all the orange colour backgrounded numbers were beside ":" so used a
regex function to identify numbers that are present beside ":".

PART 1 Q2:

Problem statement - There are times when a user writes Good, Nice App or any other positive text, in the review and gives 1-star rating. 
Your goal is to identify the reviews where the semantics of review text does not match rating. 
Your goal is to identify such ratings where review text is good, but rating is negative- so that the support team can point this to users. 
Deploy it using - Flask/Streamlit etc and share the live link. 

Build a model and a web application for Review-Ratings. User will upload a csv file and result will be in the table
with coloumns. It will give row values with positive review and 1 start ratings.

Used python, Flask-API, HTML etc for the web application.

deployed link: http://127.0.0.1:5000/
screen cast link: 

PART 1 Q3:

Ranking Data - Understanding the co-relation between keyword rankings with description or any other attribute.

First I have done some preprocessing steps and made data ready for use after visualized using heatmap and correlations
to understand how data is behaving.

1.Is there any co-relation between short description, long description and ranking? 
Does the placement of keyword (for example - using a keyword in the first 10 words -
 have any co-relation with the ranking)

Ans. *Short Description and ranking are negatively corelated but not of much significance.
     *Similarly, Even long description is positively corelated with rank but not of much significannce
     *Even descriptions have no good corelation between keyword and also keyword, rank are also weakly corelated,
      So inclusion of keyword in description maynot have effect in ranking.

2. Does App ID (Also known as package name) play any role in ranking?

Ans. Rank is mostly corelated is AppID among the features present, So, we can say that APPID has significance role 
     in ranking than any other feature.

3. Any other pattern or good questions that you can think of and answer?

Ans. Features does not exhibit multicollinearty expect descriptions, Short and Long descriptions have much corelation 
     we can say that they are somewhat similar

PART 2 Q1:

1. Check if the sentence is Grammatically correct: Please use any pre-trained model or use text from
   open datasets. Once done, please evaluate the English Grammar in the text column of the below dataset.

Ans. For this task I have used Calibre library which is an open source. I checks the errors and spelling mistakes in
     text and returns the corrected one. Here I have checked corrected, given texts and predicted whether its 
     gramatically correct or not.


QUESTION:

1. Write about any difficult problem that you solved. (According to us difficult - is something which 90% 
   of people would have only 10% probability in getting a similarly good solution).  
Ans: *I have seen many people leaving or trying alternate ways when the error is not in program but
      in the installations or the path ways etc. 
     *In the grammer check problem altough libraries are good enough to directly solve the question
      but there are many errors and adujstments required.
     *And also many people doesnot understand the business scenario and removes many imporatant features 
      that produces wrong results.
     * In a linear regression problem because of muulticollinearity all of my team removed important features
       that are important for the powerplant. I figured they are important features and we concluded 
       dataset is not good.

2. Formally, a vector space V' is a subspace of a vector space V if
V' is a vector space every element of V′ is also an element of V.
Note that ordered pairs of real numbers (a,b) a,b∈R form a vector space V. 
Which of the following is a subspace of V?
The set of pairs (a, a + 1) for all real a
The set of pairs (a, b) for all real a ≥ b
The set of pairs (a, 2a) for all real a
The set of pairs (a, b) for all non-negative real a,b

Ans. 
The set of pairs (a, b) for all non-negative real a,b is right answer.
