<hr style="border:2px solid gray"> </hr>

<font size="6" face = "Times New Roman"><b>Classification of Animals into Mammals or Non-Mammals</b></font>
<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr><br>

<font size="5" face="Times New Roman"><b>Name:</b></font><font size="4" face="Times New Roman">Chandrashekar Akkenapally</font><br><br>
<font size="5" face="Times New Roman"><b>Email:</b></font><font size="4" face="Times New Roman">chandrashekar.akkenapally@mst.edu</font><br><br>
<font size="5" face="Times New Roman"><b>Course:</b></font><font size="4" face="Times New Roman"> CS 5402</font><br><br>
<font size="5" face="Times New Roman"><b>Assignment:</b></font><font size="4" face="Times New Roman"> Programming Assignment 3</font><br><br>
<font size="5" face="Times New Roman"><b>Date:</b></font><font size="4" face="Times New Roman">07/18/2022</font><br><br>
    
<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Concept Description</b></font><br><br>
<font size ="4" face="Times New Roman"> Classification of animals into Mammals or Non-Mammals using the 1R classification and Discretization. Building a model Considering the attributes like Legs of the animals, if they lay eggs, presence of tail if they nurse their young with milk, and gestation period to classify animals into Mammals or Non-Mammals. Using the scatter plots, bar charts and various other visualization will understand the attributes clearly. </font>
<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr>

<font size="5" face="Times New Roman"><b>Data Collection</b></font><br><br>

<font size ="4" face="Times New Roman">The client has provided the data set on animal-taxonamy which they had collected in the form of a comma separated file. The provided data set  consists of known animals to train and test the classification system 
with.
</font>
<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr>

<font size="5" face="Times New Roman"><b>Example Description</b></font><br><br>

<font size ="4" face="Times New Roman">  Animal-taxonamy data set has 19 attributes which will help us to predict the animals into Mammal or Non-Mammal and explore different techniques using the various attributes. </font>
>* <font size ="3" face="Times New Roman"> <b>animal name:</b> Displays the animal name .</font><br>
   <font size ="3" face="Times New Roman"> <b>Example:</b> aardvark </font>     
>* <font size ="3" face="Times New Roman"> <b>hair</b> The presence of hair on animals.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> True</font>
>* <font size ="3" face="Times New Roman"> <b>feathers:</b> Presence of feathers.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> False</font>
>* <font size ="3" face="Times New Roman"> <b>eggs:</b> If they lay eggs or not .<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> False</font><br>
>* <font size ="3" face="Times New Roman"> <b>milk:</b> If the animals nurse their young with milk.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> True</font>
>* <font size ="3" face="Times New Roman"> <b>airborne:</b> If they are airborne.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> False</font>
>* <font size ="3" face="Times New Roman"> <b>aquatic:</b> If they are aquatic.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> False</font>
>* <font size ="3" face="Times New Roman"> <b>predator:</b> If they are predatory.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> True</font>
>* <font size ="3" face="Times New Roman"> <b>toothed:</b>If the animals have teeth.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b>True</font>
>* <font size ="3" face="Times New Roman"> <b>backbone:</b> If they have a backbone.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b>True</font>
>* <font size ="3" face="Times New Roman"> <b>breathes:</b>If the animals breath air.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> True</font>
>* <font size ="3" face="Times New Roman"> <b>venomous:</b>If they are venomous.<br></font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> False</font>
>* <font size ="3" face="Times New Roman"> <b>fins:</b> If they have fins.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> False</font>
>* <font size ="3" face="Times New Roman"> <b>legs:</b>The number is legs the animal have.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b>4</font>
>* <font size ="3" face="Times New Roman"> <b>tail:</b> If the tail present or not.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b>False</font>
>* <font size ="3" face="Times New Roman"> <b>domestic:</b> If they are domesticated.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> False</font>
>* <font size ="3" face="Times New Roman"> <b>catsize:</b>If they are cat sized.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> True</font>
>* <font size ="3" face="Times New Roman"> <b>gestation:</b> Gestation period.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> 213.0</font>
>* <font size ="3" face="Times New Roman"> <b>type:</b>Type of the animal.<br> </font>
   <font size ="3" face="Times New Roman"> <b>Example:</b> Mammal <br></font>



<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr>

<font size="5" face="Times New Roman"><b>Level of measurement </b></font><br><br>
<font size="4" face="Times New Roman"><b>Nominal </b></font><br><br>
<font size="3" face="Times New Roman"><b>Nominal data are those items which are distinguished by  a simple naming system. Animal name and type are name-only, All the other attributes have True or False as the values so, we have to only two outcoms which come under nominal level of measurement. </b></font><br><br>

<ul>
  <li><font size="3" face="Times New Roman">animal name</font></li>
  <li><font size="3" face="Times New Roman">hair</font></li>
  <li><font size="3" face="Times New Roman">feathers</font></li>
  <li><font size="3" face="Times New Roman">eggs</font></li>
  <li><font size="3" face="Times New Roman">milk</font></li>
  <li><font size="3" face="Times New Roman">airborne</font></li>
  <li><font size="3" face="Times New Roman">aquatic</font></li>
  <li><font size="3" face="Times New Roman">predator</font></li>
  <li><font size="3" face="Times New Roman">toothed</font></li>
  <li><font size="3" face="Times New Roman">backbone</font></li>
  <li><font size="3" face="Times New Roman">breathes</font></li>
  <li><font size="3" face="Times New Roman">venomous</font></li>
  <li><font size="3" face="Times New Roman">fins</font></li>
  <li><font size="3" face="Times New Roman">tail</font></li>
  <li><font size="3" face="Times New Roman">domestic</font></li>
  <li><font size="3" face="Times New Roman">catsize</font></li>
  <li><font size="3" face="Times New Roman">type</font></li>
</ul><br><br>
 
<font size="4" face="Times New Roman"><b>Ratio </b></font><br><br>
<font size="3" face="Times New Roman"><b>Mainly the ratio attributes has true zero point. The attributes legs and gestation have zero values. </b></font><br>

<ul>
  <li><font size="3" face="Times New Roman">Legs</font></li>
  <li><font size="3" face="Times New Roman">gestation</font></li>
</ul>
 

<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Data Import and Wrangling</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">Animal-taxonomy csv files are read using pandas.</font></li>
  <li><font size="3" face="Times New Roman">Importing all the required functions for data mining and analysis.</font></li>
   <li><font size="3" face="Times New Roman">Displaying the top 5 rows from the animal-taxonomy csv files.</font></li>
</ul>


```python
import numpy as np
import pandas as pd 
import collections
import matplotlib.cm as cm
import matplotlib as mpl
from matplotlib import rcParams
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
from pandas.plotting import scatter_matrix
from sklearn.model_selection import train_test_split
from sklearn.datasets import load_iris
from sklearn.metrics import confusion_matrix

 
animal_data = pd.read_csv(r"C:\Users\MYPC\Documents\Introduction to Data Mining\Assignment\animal-taxonomy.csv"
                   ,skip_blank_lines=True,na_filter=True,encoding='latin-1')
animal_data.head() # displays top 5 rows
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>animal name</th>
      <th>hair</th>
      <th>feathers</th>
      <th>eggs</th>
      <th>milk</th>
      <th>airborne</th>
      <th>aquatic</th>
      <th>predator</th>
      <th>toothed</th>
      <th>backbone</th>
      <th>breathes</th>
      <th>venomous</th>
      <th>fins</th>
      <th>legs</th>
      <th>tail</th>
      <th>domestic</th>
      <th>catsize</th>
      <th>gestation</th>
      <th>type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>aardvark</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>213.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>1</th>
      <td>anole</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>42.0</td>
      <td>reptile</td>
    </tr>
    <tr>
      <th>2</th>
      <td>antelope</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>274.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>3</th>
      <td>axolotl</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>17.0</td>
      <td>amphibian</td>
    </tr>
    <tr>
      <th>4</th>
      <td>bass</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>0</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>5.0</td>
      <td>fish</td>
    </tr>
  </tbody>
</table>
</div>




```python
animal_data.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 132 entries, 0 to 131
    Data columns (total 19 columns):
     #   Column       Non-Null Count  Dtype  
    ---  ------       --------------  -----  
     0   animal name  132 non-null    object 
     1   hair         132 non-null    bool   
     2   feathers     132 non-null    bool   
     3   eggs         132 non-null    bool   
     4   milk         132 non-null    bool   
     5   airborne     132 non-null    bool   
     6   aquatic      132 non-null    bool   
     7   predator     132 non-null    bool   
     8   toothed      132 non-null    bool   
     9   backbone     132 non-null    bool   
     10  breathes     132 non-null    bool   
     11  venomous     132 non-null    bool   
     12  fins         132 non-null    bool   
     13  legs         132 non-null    int64  
     14  tail         132 non-null    bool   
     15  domestic     132 non-null    bool   
     16  catsize      132 non-null    bool   
     17  gestation    126 non-null    float64
     18  type         132 non-null    object 
    dtypes: bool(15), float64(1), int64(1), object(2)
    memory usage: 6.2+ KB
    


```python
animals = animal_data.copy()
animals["type"] = np.where(animals["type"] == "mammal", "mammal", "non mammal") #creating a class type with mammal or non-mammal
animals.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>animal name</th>
      <th>hair</th>
      <th>feathers</th>
      <th>eggs</th>
      <th>milk</th>
      <th>airborne</th>
      <th>aquatic</th>
      <th>predator</th>
      <th>toothed</th>
      <th>backbone</th>
      <th>breathes</th>
      <th>venomous</th>
      <th>fins</th>
      <th>legs</th>
      <th>tail</th>
      <th>domestic</th>
      <th>catsize</th>
      <th>gestation</th>
      <th>type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>aardvark</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>213.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>1</th>
      <td>anole</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>42.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>2</th>
      <td>antelope</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>274.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>3</th>
      <td>axolotl</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>17.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>4</th>
      <td>bass</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>0</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>5.0</td>
      <td>non mammal</td>
    </tr>
  </tbody>
</table>
</div>



<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Discretization</b></font><br><br>
<font size ="3" face="Times New Roman"> The attribute gestation is consider for discretization.</font> <br>  


```python
temp = pd.crosstab(index=animals["gestation"],columns=animals["type"],margins_name="all",margins=True)
temp
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>type</th>
      <th>mammal</th>
      <th>non mammal</th>
      <th>all</th>
    </tr>
    <tr>
      <th>gestation</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2.0</th>
      <td>0</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>3.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>5.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>450.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>540.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>645.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>720.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>all</th>
      <td>50</td>
      <td>76</td>
      <td>126</td>
    </tr>
  </tbody>
</table>
<p>81 rows × 3 columns</p>
</div>




```python
from IPython.display import display
display(temp.head(34))
display(temp.tail(46))

```


<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>type</th>
      <th>mammal</th>
      <th>non mammal</th>
      <th>all</th>
    </tr>
    <tr>
      <th>gestation</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2.0</th>
      <td>0</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>3.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>5.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>8.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>10.0</th>
      <td>0</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>12.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>14.0</th>
      <td>2</td>
      <td>2</td>
      <td>4</td>
    </tr>
    <tr>
      <th>15.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>16.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>17.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>18.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>20.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>21.0</th>
      <td>1</td>
      <td>3</td>
      <td>4</td>
    </tr>
    <tr>
      <th>23.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>25.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>26.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>28.0</th>
      <td>1</td>
      <td>3</td>
      <td>4</td>
    </tr>
    <tr>
      <th>29.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>30.0</th>
      <td>1</td>
      <td>4</td>
      <td>5</td>
    </tr>
    <tr>
      <th>31.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>34.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>35.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>40.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>42.0</th>
      <td>1</td>
      <td>6</td>
      <td>7</td>
    </tr>
    <tr>
      <th>43.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>45.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>49.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>53.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>55.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>56.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>59.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>60.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
  </tbody>
</table>
</div>



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>type</th>
      <th>mammal</th>
      <th>non mammal</th>
      <th>all</th>
    </tr>
    <tr>
      <th>gestation</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>64.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>66.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>67.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>68.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>72.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>75.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>77.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>80.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>88.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>90.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>91.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>95.0</th>
      <td>2</td>
      <td>0</td>
      <td>2</td>
    </tr>
    <tr>
      <th>98.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>100.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>108.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>115.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>120.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>132.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>139.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>140.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>150.0</th>
      <td>1</td>
      <td>2</td>
      <td>3</td>
    </tr>
    <tr>
      <th>155.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>160.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>163.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>180.0</th>
      <td>0</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>201.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>209.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>210.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>213.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>220.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>222.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>240.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>260.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>266.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>274.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>279.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>330.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>334.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>350.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>360.0</th>
      <td>3</td>
      <td>1</td>
      <td>4</td>
    </tr>
    <tr>
      <th>390.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>450.0</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>540.0</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>645.0</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>720.0</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>all</th>
      <td>50</td>
      <td>76</td>
      <td>126</td>
    </tr>
  </tbody>
</table>
</div>


Head= Non mammal=52, Mammal=11
Tail= Non Mammal= 24,Mammal=39


```python
animals.plot(kind="scatter", x="gestation", y="type",alpha=0.8, figsize=(12,6))
plt.show()
```


    
![png](output_14_0.png)
    



<ul>
  <li><font size="3" face="Times New Roman">If the gestation period is greater than 60, then they are mammals.</font></li>
  <li><font size="3" face="Times New Roman">If the gestation period is less than or equal to 60 they are Non-mammals.</font></li>
   <li><font size="3" face="Times New Roman">Error rate of 35 of 126.</font></li>
</ul>

<hr style="border:2px solid gray"> </hr>

<font size="5" face="Times New Roman"><b>Exploratory Data Analysis:</b></font><br><br>

<ul>
  <li><font size="3" face="Times New Roman">Splitting the animal data set into training data and test data.</font></li>
  <li><font size="3" face="Times New Roman">Handling the missing values.</font></li>
</ul>


```python
animals.describe()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>legs</th>
      <th>gestation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>132.000000</td>
      <td>126.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>2.916667</td>
      <td>119.460317</td>
    </tr>
    <tr>
      <th>std</th>
      <td>2.261668</td>
      <td>141.358588</td>
    </tr>
    <tr>
      <th>min</th>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>1.500000</td>
      <td>26.500000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>4.000000</td>
      <td>61.500000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>4.000000</td>
      <td>162.250000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>12.000000</td>
      <td>720.000000</td>
    </tr>
  </tbody>
</table>
</div>



<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Handling Missing Values:</b></font><br><br>



```python
animals["gestation"].fillna(value=animals["gestation"].mean(), inplace=True) # replacing the NaN values with mean for gestation
animals.describe()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>legs</th>
      <th>gestation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>132.000000</td>
      <td>132.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>2.916667</td>
      <td>119.460317</td>
    </tr>
    <tr>
      <th>std</th>
      <td>2.261668</td>
      <td>138.083427</td>
    </tr>
    <tr>
      <th>min</th>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>1.500000</td>
      <td>28.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>4.000000</td>
      <td>66.500000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>4.000000</td>
      <td>156.250000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>12.000000</td>
      <td>720.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
# dividing the data into test and training sets
training_data, test_data = train_test_split(animals, test_size=0.2, random_state=42)
work_set = training_data.copy() # assigning a copy of train set to work_set
```


```python
work_set.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>animal name</th>
      <th>hair</th>
      <th>feathers</th>
      <th>eggs</th>
      <th>milk</th>
      <th>airborne</th>
      <th>aquatic</th>
      <th>predator</th>
      <th>toothed</th>
      <th>backbone</th>
      <th>breathes</th>
      <th>venomous</th>
      <th>fins</th>
      <th>legs</th>
      <th>tail</th>
      <th>domestic</th>
      <th>catsize</th>
      <th>gestation</th>
      <th>type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>95</th>
      <td>rhea</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>43.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>96</th>
      <td>scorpion</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>8</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>540.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>0</th>
      <td>aardvark</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>213.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>12</th>
      <td>catfish</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>0</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>10.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>126</th>
      <td>wallaby</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>30.0</td>
      <td>mammal</td>
    </tr>
  </tbody>
</table>
</div>




```python
work_set.groupby('legs')['type'].value_counts(ascending=True)
```




    legs  type      
    0     mammal         3
          non mammal    24
    2     mammal         5
          non mammal    17
    4     non mammal    12
          mammal        31
    5     non mammal     1
    6     non mammal     8
    8     non mammal     2
    10    non mammal     1
    12    non mammal     1
    Name: type, dtype: int64




```python
work_set.plot(kind="scatter", x="legs", y="type",alpha=0.8, figsize=(12,6))
plt.show()
```


    
![png](output_23_0.png)
    



```python
sns.catplot(x="milk", y="type", data=work_set)
plt.show()
```


    
![png](output_24_0.png)
    



```python
sns.catplot(x="venomous", y="type", data=work_set)
plt.show()
```


    
![png](output_25_0.png)
    



```python
sns.catplot(x="eggs", y="type", data=work_set)
plt.show()
```


    
![png](output_26_0.png)
    


<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Mining or Analytics:</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">Let's find out the attribute which is best fit for from 1R classifier.</font></li>
  <li><font size="3" face="Times New Roman">Here we consider four attributes that are legs, milk, aquatic, eggs.</font></li>
   <li><font size="3" face="Times New Roman">The error rate for each attribute is calculated.</font></li>
</ul>


```python
atr1= pd.crosstab(index=work_set["legs"],columns=work_set["type"],margins_name='Total',margins=True)
atr2= pd.crosstab(index=work_set["milk"],columns=work_set["type"],margins_name='Total',margins=True)
atr3=pd.crosstab(index=work_set["aquatic"],columns=work_set["type"],margins_name='Total',margins=True)
atr4=pd.crosstab(index=work_set["eggs"],columns=work_set["type"],margins_name='Total',margins=True)
```


```python
display(atr1,atr2,atr3,atr4)
```


<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>type</th>
      <th>mammal</th>
      <th>non mammal</th>
      <th>Total</th>
    </tr>
    <tr>
      <th>legs</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>3</td>
      <td>24</td>
      <td>27</td>
    </tr>
    <tr>
      <th>2</th>
      <td>5</td>
      <td>17</td>
      <td>22</td>
    </tr>
    <tr>
      <th>4</th>
      <td>31</td>
      <td>12</td>
      <td>43</td>
    </tr>
    <tr>
      <th>5</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>6</th>
      <td>0</td>
      <td>8</td>
      <td>8</td>
    </tr>
    <tr>
      <th>8</th>
      <td>0</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>10</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>12</th>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>Total</th>
      <td>39</td>
      <td>66</td>
      <td>105</td>
    </tr>
  </tbody>
</table>
</div>



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>type</th>
      <th>mammal</th>
      <th>non mammal</th>
      <th>Total</th>
    </tr>
    <tr>
      <th>milk</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>False</th>
      <td>0</td>
      <td>65</td>
      <td>65</td>
    </tr>
    <tr>
      <th>True</th>
      <td>39</td>
      <td>1</td>
      <td>40</td>
    </tr>
    <tr>
      <th>Total</th>
      <td>39</td>
      <td>66</td>
      <td>105</td>
    </tr>
  </tbody>
</table>
</div>



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>type</th>
      <th>mammal</th>
      <th>non mammal</th>
      <th>Total</th>
    </tr>
    <tr>
      <th>aquatic</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>False</th>
      <td>34</td>
      <td>31</td>
      <td>65</td>
    </tr>
    <tr>
      <th>True</th>
      <td>5</td>
      <td>35</td>
      <td>40</td>
    </tr>
    <tr>
      <th>Total</th>
      <td>39</td>
      <td>66</td>
      <td>105</td>
    </tr>
  </tbody>
</table>
</div>



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>type</th>
      <th>mammal</th>
      <th>non mammal</th>
      <th>Total</th>
    </tr>
    <tr>
      <th>eggs</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>False</th>
      <td>38</td>
      <td>5</td>
      <td>43</td>
    </tr>
    <tr>
      <th>True</th>
      <td>1</td>
      <td>61</td>
      <td>62</td>
    </tr>
    <tr>
      <th>Total</th>
      <td>39</td>
      <td>66</td>
      <td>105</td>
    </tr>
  </tbody>
</table>
</div>


<font size="4" face="Times New Roman"><b>Legs</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">If,Legs =0 then Non-Mammal(Error=3)</font></li>
  <li><font size="3" face="Times New Roman">Legs =2 then Non-Mammal(Error=5) </font></li>
   <li><font size="3" face="Times New Roman">Legs =4 then Mammal (Error=12)</font></li>
   <li><font size="3" face="Times New Roman">Legs =5 then Non-Mammal (Error=0)</font></li>
   <li><font size="3" face="Times New Roman">Legs =6 then Non-Mammal (Error=0)</font></li>
   <li><font size="3" face="Times New Roman">Legs =8 then Non-Mammal (Error=0)</font></li>
   <li><font size="3" face="Times New Roman"> Legs =10 then Non-Mammal (Error=0)</font></li>
    <li><font size="3" face="Times New Roman"> Legs =12 then Non-Mammal (Error=0)</font></li>
</ul>
<font size="4" face="Times New Roman"><b>Milk</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">If the Animal nurse their young with milk i.e., represented by True then it is a Mammal(Error=1)</font></li>
  <li><font size="3" face="Times New Roman">If the Animal doesn't nurse their young with milk i.e., represented by False then it is a Non Mammal(Error=0)</font></li>
</ul>
<font size="4" face="Times New Roman"><b>Aquatic</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">If the animal is aquatic i.e., represented by True then it is a Non Mammal(Error=5)</font></li>
  <li><font size="3" face="Times New Roman">If the animal isn't aquatic i.e., represented by False then it is a Mammal(Error=31)</font></li>
</ul>
<font size="4" face="Times New Roman"><b>Eggs</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">If the animal lay eggs ie. True then, it is a Non Mammal (Error=1) </font></li>
  <li><font size="3" face="Times New Roman">If the animal doesn't lay eggs i.e., Represented with False then, it is a Mammal(Error=5)</font></li>
</ul>



```python
Total_value = 105
Legs_error=20
Milk_error=1
Aquatic_error=36
Eggs_error=6

Legs_errorrate= Legs_error/Total_value
print('legs error rate is '+str(Legs_errorrate))
Milk_errorrate=Milk_error/Total_value
print('Milk error rate is '+str(Milk_errorrate))
Aquatic_errorrate=Aquatic_error/Total_value
print('Aquatic error rate is '+str(Aquatic_errorrate))
Eggs_errorrate=Eggs_error/Total_value
print('Eggs error rate is '+str(Eggs_errorrate))
```

    legs error rate is 0.19047619047619047
    Milk error rate is 0.009523809523809525
    Aquatic error rate is 0.34285714285714286
    Eggs error rate is 0.05714285714285714
    

<font size="4" face="Times New Roman"><b>Considering all the error rates from the above attributes, we can see that the Milk attribute has the lowest error rate.</b></font><br><br>
<font size="4" face="Times New Roman"><b>1R classifier rule set is:</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">If the Animal nurse their young with milk i.e., represented by True then it is a Mammal(True->Mammal)</font></li>
  <li><font size="3" face="Times New Roman">If the Animal doesn't nurse their young with milk i.e., represented by False then it is a Non Mammal(False->Non Mammal)</font></li>
</ul>


```python
pd.crosstab(index=work_set["legs"],columns=work_set["type"]).plot.bar(stacked=True)
display(plt.show())
pd.crosstab(index=work_set["milk"],columns=work_set["type"]).plot.bar(stacked=True)
display(plt.show())
pd.crosstab(index=work_set["aquatic"],columns=work_set["type"]).plot.bar(stacked=True)
display(plt.show())
pd.crosstab(index=work_set["eggs"],columns=work_set["type"]).plot.bar(stacked=True)
display(plt.show())
```


    
![png](output_33_0.png)
    



    None



    
![png](output_33_2.png)
    



    None



    
![png](output_33_4.png)
    



    None



    
![png](output_33_6.png)
    



    None


<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Evaluation:</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">Here we use the test data set to create a confusion matrix for the manually created 1R classifier.</font></li>
  <li><font size="3" face="Times New Roman">Accuracy and F1-Score for the model is determined.</font></li>
</ul>


```python
M_true = test_data.copy()
M_pred = test_data.copy()
```


```python
M_true.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>animal name</th>
      <th>hair</th>
      <th>feathers</th>
      <th>eggs</th>
      <th>milk</th>
      <th>airborne</th>
      <th>aquatic</th>
      <th>predator</th>
      <th>toothed</th>
      <th>backbone</th>
      <th>breathes</th>
      <th>venomous</th>
      <th>fins</th>
      <th>legs</th>
      <th>tail</th>
      <th>domestic</th>
      <th>catsize</th>
      <th>gestation</th>
      <th>type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>56</th>
      <td>human</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>266.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>83</th>
      <td>pheasant</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>23.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>19</th>
      <td>chupacabra</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>90.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>31</th>
      <td>duck</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>28.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>76</th>
      <td>opossum</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>14.0</td>
      <td>mammal</td>
    </tr>
  </tbody>
</table>
</div>




```python
M_pred.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>animal name</th>
      <th>hair</th>
      <th>feathers</th>
      <th>eggs</th>
      <th>milk</th>
      <th>airborne</th>
      <th>aquatic</th>
      <th>predator</th>
      <th>toothed</th>
      <th>backbone</th>
      <th>breathes</th>
      <th>venomous</th>
      <th>fins</th>
      <th>legs</th>
      <th>tail</th>
      <th>domestic</th>
      <th>catsize</th>
      <th>gestation</th>
      <th>type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>56</th>
      <td>human</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>266.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>83</th>
      <td>pheasant</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>23.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>19</th>
      <td>chupacabra</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>90.0</td>
      <td>mammal</td>
    </tr>
    <tr>
      <th>31</th>
      <td>duck</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>2</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>28.0</td>
      <td>non mammal</td>
    </tr>
    <tr>
      <th>76</th>
      <td>opossum</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>4</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>14.0</td>
      <td>mammal</td>
    </tr>
  </tbody>
</table>
</div>




```python
M_true.loc[M_true["milk"]=="True","type"]= "mammal"
M_true.loc[M_true["milk"]=="False","type"]= "non mammal"
```


```python

from sklearn.metrics import confusion_matrix
binary_confusion_matrix = confusion_matrix(M_true["type"], M_pred["type"])
print("Binary confusion matrix:\n%s" % binary_confusion_matrix)
```

    Binary confusion matrix:
    [[11  0]
     [ 0 16]]
    


```python
ax = sns.heatmap(binary_confusion_matrix, annot=True, cmap='Blues')

ax.set_title('Seaborn Confusion Matrix with labels\n\n');
ax.set_xlabel('\nPredicted Values')
ax.set_ylabel('Actual Values ');

ax.xaxis.set_ticklabels(['True','False'])
ax.yaxis.set_ticklabels(['True','False'])

## Display the visualization of the Confusion Matrix.
plt.show()
```


    
![png](output_40_0.png)
    



```python
TP=11 # True positive
FP=0 # False positive
FN=0 # False Negative
TN=16 # True Negative
Total=27 # Total number of values
Accuracy = (TP+TN)/27
print(Accuracy)
```

    1.0
    


```python
Precision = TP/(TP+FP)
Recall = TP/(TP+FN)
print("Precision = " +str(Precision))
print("Recall = "+ str(Recall))
```

    Precision = 1.0
    Recall = 1.0
    


```python
F_measure= (2*Recall*Precision)/(Recall+Precision)
print("F_measure = "+str(F_measure))
```

    F_measure = 1.0
    

<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Results:</b></font><br><br>
<ul>
  <li><font size="3" face="Times New Roman">After choosing the different attributes for classification of Mammal or Non Mammal, we can see that MIlk attribute showed best result when compared to other attributes..</font></li>
  <li><font size="3" face="Times New Roman">In 1R classifier, the error rate of milk attribute is 0.00952,legs error rate is 0.19047, Aquatic error rate is 0.34285,Eggs error rate is 0.05714.</font></li>
   <li><font size="3" face="Times New Roman">The error rate for the milk attribute was very low in 1R classifier.</font></li>
   <li><font size="3" face="Times New Roman">After testing the test data with the 1R classifier data, the milk attribute Accuracy is 1 which is 100%.</font></li>
   <li><font size="3" face="Times New Roman">The classification of animals as Mammals or Non mammals can be done based on the attribute Milk.</font></li>
   <li><font size="3" face="Times New Roman">If the animals nurse their young with milk then it's mammal and if not it's a Non mammal based on our classifier model.</font></li>
</ul>
<hr style="border:2px solid gray"> </hr>

<hr style="border:2px solid gray"> </hr>
<font size="5" face="Times New Roman"><b>Reference: </b></font><br><br>

>* <font size ="3" face="Times New Roman"> https://pandas.pydata.org/docs .<b></font> <br><br>  
>* <font size ="3" face="Times New Roman"> https://realpython.com/.<b></font> <br><br>  
>* <font size ="3" face="Times New Roman"> https://towardsdatascience.com/.<b></font> <br><br>  
>* <font size ="3" face="Times New Roman"> https://pythongeeks.org/python-scatter-plot/.<b></font> <br><br>
>* <font size ="3" face="Times New Roman">https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html.<b></font> <br><br>

<hr style="border:2px solid gray"> </hr>
