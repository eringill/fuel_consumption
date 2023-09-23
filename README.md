## Project title: fuel_consumption

## Project statement
[google doc](https://docs.google.com/document/d/145bdINznB5TpugOunzHF2LDdQuCvEcXMLCGlhdBBLb4/edit)

## Project team members

Team lead:

Mentor:

Documentation:

Scripting:

Modelling: 

Sanity checking: 

### Tasks
- [ ] Merge .csv files in /data/consumption_clean/
- [ ] Find out how many missing values are in each column of merged .csv file
- [ ] Merge fuel consumption file with prices file '/data/car_prices/prices_clean.csv' (hint: pd.merge())
- [ ] Find out how many car models have price data. If models don't have price data, is it because of hypens or spaces in model names in one of the files?
- [ ] What is the relationship between car price and CO2 rating? (hint: we can use plot, then use linear regression to determine this)
- [ ] What is the relationship between CO2 rating and smog rating?
- [ ] If somebody is going to purchase a battery-powered vehichle, what are the top options in terms of price? In terms of charging time? In terms of range? Is there a relationship between these?
