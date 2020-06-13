---
layout: page-no-title
title: Tutorials
---

<header class="post-header">
    <h1 class="post-title" style="text-align:center"><i class="far fa-lightbulb fa-fw fa-lg svv"></i>{{ page.title | escape }}</h1>
</header>

## <i class="fab fa-python fa-fw fa-lg fa-notbold svv"></i> [Python tutorial](/tutorials/python/)

## $\,\rightarrow\,$ [$\LaTeX$ tutorial](/tutorials/latex/)

<!-- ```ruby
class Person
  include ActiveModel::Conversion
  include ActiveModel::Validations

  validates_presence_of :name

  attr_accessor :name

  def initialize(attributes = {})
  	@name = attributes[:name]
  end
```


```python
%matplotlib notebook
fig, ax = plt.subplots(figsize=(10,6))
df = pd.read_csv("daily-data/BILBAO-parsed" + ".csv", sep=",")
df['full-date'] = pd.to_datetime(df['full-date'])
df = df.set_index('full-date')
ax.plot(df['rain (mm)'], '-o', label="daily rain (mm)")
ax.set_xlabel("date")
ax.set_ylabel("daily rainfall (mm)")
ax.set_title("Hyetograph -- Bilbao, Spain")
plt.gcf().autofmt_xdate()

import matplotlib.pyplot as plt
from numpy import random

color = "#f02254"

@requires_authorization
def somefunc(param1='', param2=0):
    r'''A docstring'''
    if param1 > param2: # interesting
        print 'Gre\'ater'
    return (param2 - param1 + 1) or None

class SomeClass:
	"""
	ahalja;
	;lkajdf
	"""
    pass

```


 -->