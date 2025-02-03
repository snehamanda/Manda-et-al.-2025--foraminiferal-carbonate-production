# Manda-et-al.-2025--foraminiferal-carbonate-production
This GitHub report corresponds to the code I have written to evaluate calcium carbonate production potential for LBFs from the EaM

#I have written this on python

#loading all required packages
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from datetime import date

#loading the required dataframe (correspond to/ reffered to as X in the manuscript)
#This specific example uses the data on A. lobifera absolute abundances per unti area at NAhsholim station. THe rowas corresponf to different salpimg season and the columns correspond to the different size classes)

df = pd.read_csv('/content/shikmona_amphi.csv')

#dates (time intervals)
date1 = date(2021, 5, 31)
date2 = date(2021, 9, 13)
date3 = date(2021, 11, 23)
date4 = date(2022, 3, 8)
date5 = date(2022, 5, 31)
delta1 = date2 - date1
delta2 = date3 - date2
delta3 = date4 - date3
delta4 = date5 - date4
print(delta1.days)
print(delta2.days)
print(delta3.days)
print(delta4.days)

