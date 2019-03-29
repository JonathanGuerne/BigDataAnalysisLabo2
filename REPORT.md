# BigDataAnalysisLabo2


## Part 1 RankLangs

**How much does the code take? What is the list of ranked languages?**

## Part 2 rankLangsUsingIndex

**How much does the code take? What is the list of ranked languages?**

**Can you notice a performance improvement over attempt #1? Why?**

## Part 3

**How much does the code take? What is the list of ranked languages?**

**Can you notice an improvement in performance compared to measuring both the computation of the index and the computation of the ranking as we did in attempt #2? If so, can you think of a reason?**


**Performance :**
```bash
List((JavaScript,1733), (Java,737), (C#,735), (PHP,653), (CSS,468), (Python,449), (C++,385), (MATLAB,312), (Perl,203), (Ruby,165), (Haskell,83), (Objective-C,61), (Scala,56), (Groovy,34), (Clojure,29))
Processing Part 1: naive ranking took 130790 ms.
Processing Part 2: ranking using inverted index took 161992 ms.
Processing Part 3: ranking using reduceByKey took 61775 ms.
```
