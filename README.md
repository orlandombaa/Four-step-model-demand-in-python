# Four step model demand in python

The code presented here is a open sourse code which generates the classic four step model demand for tranport modelling using [Quetzal](https://github.com/systragroup/quetzal) a library under develpment of Python. 
The general structure of the fourt step model is represnted in the following figure: 


![4](https://user-images.githubusercontent.com/48104481/134217296-24ea73a7-c393-48fb-9e1d-bbfa38641594.png)


The sub-models are:  
- Trip generation: this estimates the total number of trips generate and attracts by every zone 
- Distribution:  it estimates the spatial distribution of the total number of trips per zone to the rest of the zones 
- Modal split: this estimates the percentage distribution of evey mode available  
- Network assignment: this sub-model assigns trips to the road network or public transport network. 


Much more detail information can be found in my PhD thesis in the section of modelling. 

The data contains in the folder input data is the neccesary to generate all the outputs and SM (Step Model). The code contains information about the tasks in the code, and a more detail explanation is in the followin file: 

