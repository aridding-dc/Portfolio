
---
title: Projects Title
---

# Course Projects

##  Data Aggregation Projects
This python code runs data aggregations on an input file. 

### Introduction
In order use this code, you must have Python installed, as well as the package, pandas. 

### Samples

```python

############################
####  Create New Columns ###
############################

# SETTING A DEFAULT COLUMN VALUE
raw_df_1["Benchmarks"] = 150

# CALCULATE A COLUMN
raw_df_1["Productivity_score"] = round(raw_df_1["SUB"] / raw_df_1["Benchmarks"], 2)

```
