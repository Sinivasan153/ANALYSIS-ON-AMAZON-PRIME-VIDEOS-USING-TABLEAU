# ANALYSIS-ON-AMAZON-PRIME-VIDEOS-USING-TABLEAU
ANALYSIS ON AMAZON PRIME VIDEOS USING TABLEAU
         
            
            
            
Amazon Prime Video is a popular streaming service offered by Amazon, providing
subscribers with a wide range of movies, TV shows, and original content. In this analysis
using Tableau, we aim to gain insights into Amazon Prime Video's content library, user
engagement, and viewer preferences. By examining factors such as content genres,
release years, viewer ratings, and user behavior, we can identify popular shows, analyze
viewer patterns, and provide recommendations for content selection and user experience
improvements. This analysis will help Amazon Prime Video understand its strengths and
areas for growth in the competitive streaming industry.

# This Python 3 environment comes with many helpful analytics libraries installed
# It is defined by the kaggle/python Docker image: https://github.com/kaggle/docker-python
# For example, here's several helpful packages to load

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

# Input data files are available in the read-only "../input/" directory
# For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
