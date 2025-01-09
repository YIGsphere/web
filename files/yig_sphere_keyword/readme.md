# use spyder: 
runfile('./academic-keyword-occurrence/extract_occurrences.py', args='"YIG sphere" 2018 2021', wdir='J:/academic-keyword-occurrence/academic-keyword-occurrence-master')
# you should get a "out.csv" contains the data you required

# command in MATLAB to make the plot: 
bar3(x,y,'m');ylabel('Year of Publication'); zlabel('Paper Counts'); title('Paper statistic of "YIG sphere"')