## Software

### Have a *folder strategy*
Here is an example:
* Create a dedicated project folder.
* Create `/raw` within the project folder to save original datasets, and do not allow anybody's -- including your own -- code to access that folder in any way. Declare it as a *NO MACHINE* zone.
* Create `/input` within the project folder to save original datasets, which could be accessed by machines.
* Create `/util` within the project folder to save general purpose code.
* Create `/doc` within the project folder to save all documents related to the analysis.

### Code like a pro
One big mistake many data analysts do is to underestimate the *importance of proper coding*.

Please remember that even though nobody else will see your scripts used during the analysis, which in fact is a major issue by itself, **you** might want to refer the same scripts in the future. And unless you maintain a high standard in your coding style, large amounts of time will be lost during the *remembering your own code* process.

* Explicitly indicate what your counters are counting. ~~`n`~~, ~~`m`~~ & `customer_n`, `product_m`
* Add units to variable names. ~~`delay`~~, ~~`size`~~ & `delay_ms`, `size_mb`
* Explicitly state which variables are boolean with adding a proper prefix, such as `is_...` and `has_...` to your variable names .
* Comment on how a constant got its value and stop this madness: `THRESHOLD=10 `~~`# Threshold is set to 10`~~.
* Use information-dense words for comments, function and variable names.
* Start naming your functions with verbs.

[Return to README](https://github.com/srctaha/recipes-for-data-analysis/blob/master/README.md)
