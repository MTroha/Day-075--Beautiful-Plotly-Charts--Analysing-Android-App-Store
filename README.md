# Day-075--Beautiful-Plotly-Charts-and-Analysing-Android-App-Store
Pandas + Make charts with Plotly

Pandas:
- .sample() --> pull a random sample (row) from DataFrame
- .duplicated() --> find duplicate entries in a DataFrame
- .drop_duplicates() --> remove duplicates from a DataFrame
- .to_numeric() --> convert string and object data types into numbers
- .stack()

Plotly (plotly.express as px):
- px.pie() --> generate pie and donut (hole=0.6) charts
- px.bar() --> generate bar charts (orientation='h' --> horizontal, orientation='v' --> vertical)
- px.scatter() --> generate scatter charts
- px.box() --> generate box charts (it shows min, max, mean, ... values)

- .update_traces() --> assign additional properties of labels
- .update_layout() --> assign additional properties of chart
- .show() --> show the chart
