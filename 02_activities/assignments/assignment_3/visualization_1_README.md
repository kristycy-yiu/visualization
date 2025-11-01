Dataset: Career College Key Performance Indicators
Data source: https://data.ontario.ca/dataset/private-career-colleges-pcc-key-performance-indicators/resource/799f29b1-1031-4e14-b3bf-01ee811e9129
Application: Power BI
Chart Type: Clustered Column Bar Graph
Chart Title: Graduate Outcomes by Program (Arial, size 18)
X-axis Values: Program Type Abbrev (Arial, size 11)
X-axis Title: Program Type (Arial, size 14)
Y-axis: Graduation Rate, Graduate Employment, Graduate Employment in Field of Study, Graduate Satisfaction (Arial, size 11)
Y-axis Title: Average Rate (%) (Arial, size 14)

New Measures:
Graduation Rate: Average of Graduation Rate column
Graduate Employment: Average of Graduate Employment column
Graduate Employment in Field of Study: Average of Graduate Employment in Field of Study column
Graduate Satisfaction: Average of Graduate Satisfaction column

Filters:
Unselect all "blanks" from Program Type Abbrev in bar graph and slicer

Data Transformation:
Create Program Type Abbrev Column: Copied Program Type Column and abbreviate longer names

Slicer: Program Type

Additional Text: Abbreviations at bottom right of graph