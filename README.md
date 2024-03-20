Requirements

•
App asks user for: 

first name

last name

age

Minimum interested age

Maximum interested age

Gender

Gender interested in dating

Location (rural, city)

•
Above input is checked for valid input and question is repeated if invalid:

Makes sure names have letters and not empty strings

Age, min_age_interested, max_age_interest is 18+

max_age_interest is higher than min_age_interest

All number values are stored as numbers

gender and gender_interest = M, F, X. 

location = rural/city

•
App iterates on imported data (mockData) and checks who matches the criteria:

User age matches min/max interested age of a match

Matched age matches min/max interested age of the user

User gender interest is the same as the gender of a match

Match gender interest is the same as the gender of the user

Location is the same

•
App displays the number of matches and prints it in an understandable format where it is clear who the match is, their age and their location.
