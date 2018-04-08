CSE-544-Project
----

## Data

Data can be downloaded from [here](http://www.wikibench.eu/?page_id=60).

Each entry of data has the following information:
- A monotonically increasing counter (useful for sorting the trace in chronological order)
- The timestamp of the request in Unix notation with milli-second precision
- The requested URL
- A flag to indicate if the request resulted in a database update or not

Store all data into `./data` folder. Feel free to put big files in this fold because they will be ignored.



## TODO

- [x] Pick a raw dataset, process it, clean it (correct any errors or omit any outliers), and read it into a program.
- [ ] Form multiple different hypotheses about the dataset and provide references for supporting the hypotheses, if applicable.
- [ ] Analyze the processed data using multiple techniques to accept or reject each hypothesis.
- [ ] Provide a measure of confidence for each case, as applicable.
- [ ] Conclude with findings based on the data analysis.

## Group Member
- Xuan Li 111676019
- Xiaofei Sun 111753600
- Xuan Xu 111675940
- Yunqing Yang 111485471
- Hongyi Duanmu 111464575
- Keyi Chen 110947716
- Yicheng Lin 111583117

## Hypothesis
![plot.png](https://github.com/xuan-li/CSE-544-Project/blob/master/plot.png)

## Topics
### Events:

After a big event happends:
- Visits of corresponding entries will increase.
- Update frequency of corresponding entries will increase.
- New entries will be created
- Visits frequency follows Poisson distributions (with `x` is time delay after the event happening and `y` is the). 
 visit frequency)
 
### Times:

- Visit frequency is a periodic function with period equal to 24 hours.
- ~~Visit frequency of some entries in weekends is higher than that of weekdays. ()~~
  
### Languages:

- ~~Culture-related entries are in different level of hottness in different languages.~~
  
### Search Ranks:

- Popular entries have higher rank in google search results.
  
### Redirections:

- ~~Redirections contribute to visits.~~
- ~~Visits have correlations with the order of redirections.~~
  
### Categories:

- The popularity of different categories has different levels of attentions, e.g. entertainment-related entries are more popular than academic entries.
  
### Page Sizes:

- Popular entries have larger page sizes.
  
### Level of Difficulties:

- The most popular entry under each category is not a common used term.


