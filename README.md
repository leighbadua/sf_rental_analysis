# sf_rental_analysis
An analysis  of the housing rental market data for San Francisco, complete with professionally styled and formatted interactive visualizations using hvPlot and GeoViews. Data is used from `"sfo_neighborhood_census_data.csv"` located in the Resource folder of this repository. This project will focus on the following tasks:
  + Calculate and plot the housing units per year. 
  + Calculate and plot the avergae prices per square foot.
  + Compare the average prices by neighborhood.
  + Build an interactive neighborhood map.
  + Compose a Data Story
    + How does the trend in rental income growth compare to the trend in sale prices? Does this same trend hold true for all the neighborhoods across San Francisco?
    + What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? Do neighborhoods exist that you would suggest for investment, and why?

---

## Technologies

Click on the links below for documentation on each of the technologies used. This project uses the following libraries and dependencies:
+ [**Anaconda**](https://docs.anaconda.com/): an open source package and environment management system.
+ [**JupyterLab**](https://jupyterlab.readthedocs.io/en/stable/): an extensive environment using web-based user interface designed for data analysis. 
+ [**Pandas**](https://pandas.pydata.org/docs/getting_started/index.html): (included in Anaconda) a Python package data analysis toolkit.
+ [**PyViz**](https://pyviz.org/index.html): a Python visualization package that provides a single platform for accessing multiple visualization libraries. PyViz ecosystem includes both [**hvPlot**](https://hvplot.holoviz.org/) and [**GeoViews**](https://pypi.org/project/geoviews/) incorporated into this project. 

---

## Installation Guide
Check to ensure that Jupyterlab is installed on your machine by entering the following into your environment:
```
conda list jupyterlab
conda list pandas
```
If any of these packages are not installed into your environment, use the corresponding codes in your terminal:

```
pip install jupyterlab
pip install pandas
```

Finally, to install PyViz package, use the following:
```
conda install -c pyviz hyplot geoviews
```

### Instructions to Use JupyterLab

To launch JupyterLab:
  1. Open terminal window, and type `conda activate dev`.
  2. Type `jupyter lab`. JupyterLab user interface should open in your browser. 
      a. Or copy and paste one of the URLs: "http://localhost:8888/lab?token=..." into web browser. 

To exit JupyterLab:
  1. On your web browser, use the Run button to shut down any running kernel sessions.
  2. On the menu bar, on the File menu, select Shut Down. 
  3. Okay to close tabs once a dialog box with "Server stopped" message indicates the server has stopped. 
  4. Navigate to terminal window, where you launched JupyterLab and type `conda deactivate`. This will return you to your `base` environment. 

---

## Usage 

### Import the required libraries and dependencies:

![image](https://user-images.githubusercontent.com/96001018/153379052-2cfccb4b-3065-42b7-b87e-8ab091af7a16.png)


### Calculate and plot the housing units per year.

![image](https://user-images.githubusercontent.com/96001018/153389254-0c0f739a-bcef-4795-a270-1556e5ea3dc8.png)

![image](https://user-images.githubusercontent.com/96001018/153389415-d58b31fb-7a60-427f-8023-396ba7f1e304.png)


### Calculate and plot the avergae prices per square foot.

![image](https://user-images.githubusercontent.com/96001018/153389777-da94e7ca-6d58-4537-af00-3411c83025e0.png)

![image](https://user-images.githubusercontent.com/96001018/153395963-c0c7dc6b-7baa-4c9a-abe7-5d71cf1069d5.png)


### Compare the Average Sale Prices by Neighborhood

![image](https://user-images.githubusercontent.com/96001018/153391279-ab1ffa4f-4290-47fd-807d-6cc8ba705e7b.png)

Line Plot (using hvPlot) of Average Sales Prices per Square Foot by Neighborhood. Includes an interactive widget to sort through the different neighborhoods.
![image](https://user-images.githubusercontent.com/96001018/153391424-7903e795-8324-47a4-b437-58310b67b496.png)


### Build an interactive neighborhood map

![image](https://user-images.githubusercontent.com/96001018/153392264-44c60ca1-7fbb-419f-898f-16e67e8410e1.png)

![image](https://user-images.githubusercontent.com/96001018/153392352-e3d45fec-ad51-4be2-864e-8464504da4d2.png)


### Compose a Data Story

Using the interactive visualizations with hvPlot and GeoViews, we can note the trend in rental income growth compared to the trend in sales prices during years 2010 to 2016. This trend holds true for most neighborhood across San Francisco. However, there are investment opportunities that exist for neighborhoods with high gross rent and a relatively low sales price per square foot. See `'san_francisco_housing_analysis.ipynb'` for the full analysis.   

---

## Contributors

Leigh Anne Badua leighbadua@gmail.com 

---

## License

+ [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)
