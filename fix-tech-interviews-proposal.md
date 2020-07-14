# How to Fix Tech Interviews
Calling all SWEs, SREs, Software Architects, Engineering Managers, and anyone writing code for a living! It's about time we as a community come together to define a **better** tech interview standard. 

## 1. Create an universal algorithm and data structure industry exam.
Accountants have the [CPA Exam](https://www.aicpa.org/becomeacpa/cpaexam.html). Lawyers have the [Bar Exam](https://www.calbar.ca.gov/Admissions/Examinations/California-Bar-Examination). Nurses have the [NCLEX](https://www.ncsbn.org/nclex.htm). Financial advisors have the [CFA](https://www.cfainstitute.org/en/programs/cfa/exam). Architects have the [ARE](https://www.ncarb.org/pass-the-are). The list is too exhaustive to list here. 

If we are to dole out the same exact algorithm and data structure questions during interviews, let's establish an industry-recognized algorithm and data structure exam to use in place of repetitive white-board sessions. This exam can use scaling and points used similarly by the [GRE](https://www.ets.org/gre/revised_general/scores/how/) to measure where the test-taker falls. 

This allows engineers to study once and never again have to prepare for interviews weeks in advance. This also frees up engineer time to spend time learning new technologies instead of regurgitating the same information over and over again.


## 2. Use real world examples.
Technical portions for interviews should be thoughtful and **relevant**. Don't ask a candidate to implement an LRU cache that at best tests a candidate's knowledge to memorize a formula. How about this approach instead?

**Q:** _Location cookie sizes exceed the maximum allowed size. This happens when users look up too many locations. Each location search results in zip to city cookie mapping for speed. How can this be improved?_

**A:** A potential approach could utilize an LRU cache to keep up to 5 or 10 most recently accessed location mappings and serialize the linked list of top most accessed locations. The serialized linked list (JSON) would then be stored in a singular zip to city cookie. 

## 3. Do not haze the interviewees.
An interview process often feels like a battle for survival for the interviewee, while interviewers are there to dole out punishment. Treat interviewees as potential colleagues and allow coding, system design, and architectural sessions to feel like a preview of day-to-day operations. 


---

### Resources

Behroozi, Mahnaz & Parnin, Chris & Barik, Titus. (2019). [Hiring is Broken: What Do Developers Say About Technical Interviews?](https://www.researchgate.net/publication/334448588_Hiring_is_Broken_What_Do_Developers_Say_About_Technical_Interviews). 
