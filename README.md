# COVID19 Visualizations
As the economy is still struggling with the impact of the covid19 pandemic, all developers around the globe are striving towards helping the general population as much as they possibly can. 
Many have created covid19 apps and websites to show stats on the pandemic whereas others are creating applications that help track people who were in contact with the newly infected person. 
As a developer, I have created a COVID19 statistic visualization which not only helps my colleagues and family but also myself. 

This project showcases many eye-catching visualizations. I have majorly focused on confirmed cases, deaths, recovered, and percentage data of growth globally and county wise in the United States. 

## Pre-requisites
- For the visualization, I am using Kaggle’s virtual machines instead of the local Jupyter lab or Jupiter notebook. It is much easier to import-export datasets as well as avoid some issues which I faced during visualization.

<b>Note:</b> There are some issues in the Jupiter lab/notebook while showing Plotly graphs. This occurs due to multiple versions of Python. You could resolve it using these troubleshooting methods.
- For more information on Kaggle, refer to this article from GeeksforGeeks.
- We are using two county datasets. One from covid19-county and another from usa-county-info Kaggle datasets. You have to either download the files separately (in case you are using local Jupiter) or import these datasets using the ‘Add Data’ option on the right side of Kaggle VM.

covid19-county dataset URL: https://www.kaggle.com/devavratkalam/covid19county

usa-county-info dataset URL: https://www.kaggle.com/kkbk58901/usa-county-info


## Implementation Instructions
- Clone the repository
- Open the file 'covid19_visualization.ipynb' in jupyter notebook or jupyter lab or kaggle's VM(recommended).
- Run the file

<b>Note:</b> If the plotly graphs are not visible on jupyter notebook/ jupyterlab, follow this troubleshoot guide link for more information. 

Link: https://plotly.com/python/troubleshooting/

## Global Stats
### Line Tree Map

![](./images/Line_TreeMap.png)

### Pie Chart

![](./images/Bar-Chart.png)

### Area Chart

![](./images/Area-Chart.png)

### Bar Chart

![](./images/Bar-Chart.png)

### Bar Chart Logarithmic

![](./images/Bar-Chart-Log.png)

### Confirmed cases Map

![](./map/Confirmed_Map.png)

### Deceased cases Map

![](./map/Deceased_Map.png)

## US based Stats
### County wise Confirmed cases Choropleth

![](./choropleth/Confirmed_Choropleth.png)

### County wise Deceased cases Choropleth

![](./choropleth/Deceased_Choropleth.png)

### County wise Confirmed cases TreeMap

![](./map/Confirmed_TreeMap.png)

### State-County wise Deceased TreeMap

![](./map/Deceased_TreeMap.png)
