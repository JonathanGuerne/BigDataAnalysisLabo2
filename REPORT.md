# BigDataAnalysisLabo2


## Part 1 RankLangs

**How much does the code take? What is the list of ranked languages?**

## Part 2 rankLangsUsingIndex

**How much does the code take? What is the list of ranked languages?**

**Can you notice a performance improvement over attempt #1? Why?**

There is indeed a significant performance improvement. One of the reasons might be the following :
for the first part to check if there was a mention of a specific language in an article we iterated trough 
each language and then used the function ```occurenceOflang```  over each article for a specific language. 
And it is important to note that to be effective the "check function" has to iterate trough each word of 
a given article's text. 

Knowing all of that it is then pretty straight forward to realize that if we iterate first trough the 
languages and then only trough the words in the article will be less cost efficient in term of list generation
then the opposite. 

## Part 3

**How much does the code take? What is the list of ranked languages?**

**Can you notice an improvement in performance compared to measuring both the computation of the index and the computation of the ranking as we did in attempt #2? If so, can you think of a reason?**


**Performance :**
```bash
List((JavaScript,1704), (C#,731), (Java,699), (CSS,429), (Python,409), (C++,384), (PHP,333), (MATLAB,296), (Perl,175), (Ruby,160), (Haskell,65), (Objective-C,61), (Scala,53), (Clojure,29), (Groovy,29))
Processing Part 1: naive ranking took 59018 ms.
Processing Part 2: ranking using inverted index took 11732 ms.
Processing Part 3: ranking using reduceByKey took 6381 ms.
```
