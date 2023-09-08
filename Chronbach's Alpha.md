- Metric used to assess the internal coherence or consistency of a set of variables that measure the same characteristic.
- ![[Pasted image 20221030173226.png]]
- Results:
	- (<0): Catastrophic. Variables could be inversely correlated. This is bad if we are working with coherent variables.
	- (around 0): There is no correlation between the two variables. Also not good if we are treating them as coherent.
	- (>0.6): Acceptable coherence between variables.
	- (>0.8): Excellent coherence.
	- Nevertheless, you should be very careful when you have an alpha whose value is so high, for instance, 0.98. You would effectively be in a situation where your variables used to calculate your score are very coherent. However, you should always take a step back and ask yourself if you haven't deviated from your original objective. Let's remind ourselves that **the objective from the start was to measure many different aspects of one key characteristic**. If all these variables take exactly the same value, it is imperative to verify if your questions really measure different distinct aspects, or if you aren't **asking the same question over and over** using synonyms.

#DataScience 