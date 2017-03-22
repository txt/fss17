# fss17: foundations of software science

NCSU CSC 591-023 (10722)  
CSC 791-023 (11162)  
Tues/Thurs 4:30 to 5:45  
Mid-session exam week 10 (on terminology)    
No final exam.

<img align=right src="https://github.com/txt/fss16/raw/master/img/science.png">


## Why this subject?


"Science" is the process of communities sharing and reviewing and improving each other's ideas.

Sadly, most "data science" is not about "science". Rather its about vendors selling you stuff tjat does not work properly and does not
ring an alarm when it starts failing.

So lets fix that.

<br clear=all>

## Project

Apply SE principles to a data science problem. 

- Implement add any of the operators listed on slide 9 of [this tutorial](http://tiny.cc/timm) (and listed below) to any 
  data science problem 
- Ideally one from SE but i can be flexible on that. e.g. if you are doing X in your thesis, then we can apply all this to X.


  
Operator | Notes
------|--------
Comprehensible | Something we can read, argue with
Fast | Not a CPU hog
Light |Small memory footprint 
Goal-aware |Different goals means different models. ANd multiple goals = no problem!
Humble | Can publish succinct certification envelope (so we know when not to trust)
Context-aware | Knows that local parts of data ⇒ different models. Knows how to find different contexts
Privacy-aware | Can hide an individual's data
Anomaly-aware | Can detect when new inputs differ from old training data
Shareable | Knows how to transfer models, data, between contexts
Self-tuning | And can do it quickly
Incremental | Can update old models with new data


FYI: I have a basline tool for all of those. But most parts of it remain untested. And might want to use
         the tool for inspiration rather then execution.

## Why Take This Subject?

A million million people can run data miners. But how many  now when those data miners start going wrong? And how to fix faulty models?

Do this subject, learn answers to those questions, become the data scientist everyone needs to consult with  when things start going wrong.
