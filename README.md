# guide-for-simplescalar-cache-study
This directory gives a document for you to get started with simple-scalar tool and use it as a method to take cache performance and optimazation study. I make the document when I was studying computer architecture class in SJTU, and I still remember that such materials online are few. Therefore, I hope you can appreciate my work.

The file introduces 'sim-cheetah' and 'sim-outorder' with SPEC95 benchmark 'go'.
First, use 'sim-cheetah' as a cache simulator to investigate the set and associativity effects on miss rate.
Second, further use 'sim-cheetah' to discuss the cache upon replacement policies (here focus on LRU and MIN algorithm).
Third, use 'sim-outorder' to investigate the effects of branch predictors on the execution for the SPEC95 benchmark 'go'.
