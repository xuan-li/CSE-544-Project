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
- Xuan Li
- Xiaofei Sun
- Xuan Xu
- Yunqing Yang
- Hongyi Duanmu
- Keyi Chen
- Yicheng Lin

## Hypothesis
![plot.png](plot.png)

## Topics
### Events (Xuan Xu, Yunqing Yang):

After a big event happends:
- Visits of corresponding entries will increase.
- Update frequency of corresponding entries will increase.
- New entries will be created
- Visits frequency follows Poisson distributions (with `x` is time delay after the event happening and `y` is the 
 visit frequency)
 
### Times (Keyi):

- Visit frequency is a periodic function with period equal to 24 hours.
- Visit frequency of some entries in weekends is higher than that of weekdays.
- Distribution of ranges of access per hour per day.
  
### Languages (Hongyi Duanmu):

- Culture-related entries are in different level of hottness in different languages.
  
### Revision Records Digging (Xuan Li):

- Access frequency with Update frequency
- #Vandalism with access frequency
- Vandalism respond times with frequency
- #Recovery by ClueBot with access frequency

  
### Page Content (Yicheng):

- Hotter words have more embedded-in links towards other entry
- Hotter words have more images

### Categories (Xiaofei Sun):

- The popularity of different categories has different levels of attentions, e.g. entertainment-related entries are more popular than academic entries.
  
### Page Sizes (Xiaofei Sun):

- Popular entries have larger page sizes.
  
### Level of Difficulties (Xiaofei Sun):

- The most popular entry under each category is not a common used term.


