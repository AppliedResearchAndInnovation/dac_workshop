# dac_workshop

### 1. What is Tableau?

Tableau is a Data Visualisation tool that is widely used for Business Intelligence but is not limited to it. It helps create interactive graphs and charts in the form of dashboards and worksheets to gain business insights. And all of this is made possible with gestures as simple as drag and drop!
### 2. Getting Started
Now that you have the software installed and set up, I am pretty sure that your hands must be tingling with anticipation to finally begin! Well let’s not keep you waiting then, go ahead and launch the tool.
### 2.1 Connect to the Data
![Screen 1](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/screen_1.png)

You should see a screen similar to above. This is where you import your data. As is visible, there are multiple formats that your data can be in. It can be in a flat file such as Excel, CSV or you can directly load it from your company’s data servers too.

You can see that Tableau itself offers some Sample Workbooks, with pre-drawn charts and graphs. I would suggest going through these later for further exploration.

The best way to learn is to get your hands dirty. Let us start with our Data, which can be found [here](https://github.com/AppliedResearchAndInnovation/dac_workshop/blob/master/Sample-Superstore.xls). The data is that of a United States’ Superstore which is deliberating over its expansion. It wishes to know the prospective regions of the country where it could and hence requires your help.

The first thing that you will obviously need to do is import the data into Tableau. So quickly follow steps with me:
Since the data is in an Excel File, click on Excel and choose the Sample – Superstore.xls file to get :

![Screen 2](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_2.png)

You can see three sheets on the screen, but we are only going to be dealing with Orders here, so go ahead and drag the same on Drag sheets here :

![Screen 3](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_3.png)

Uh oh, the imported data looks a bit different for the first few rows. Don’t worry, the solution lies right ahead.
 
### Data Interpreter

You see the option of Use Data Interpreter?  Click on it to get the following clean view :

![Screen 4](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/screen_4.png)

All that messy data magically disappeared!

### 2.2 Data Visualisations

As soon as you had imported your dataset, next to the Data Source tab near the bottom of the screen, you immediately must have seen Go to Worksheet. A Worksheet is where you make all of your graphs, so click on that tab to reach the following screen :

![Screen 5](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_5.png)

Don’t get overwhelmed by the various elements that you see here, we will cover them all one by one.

Let’s start with Dimensions and Measures :

#### Dimensions: 
Dimensions are the fields that you cannot aggregate. They are generally string values, or Discrete values, and are mostly used as column or row headings. E.g: CountryName, ProductName, etc...

#### Measures: 
Measures as the name suggests are the fields that you can measure or aggregate. They are generally numerical values or continuous and are mostly used for plotting values. Eg: CountryPopulation, ProductSales, etc…

#### Moving onto Shelves:

(add image)

Visualisation in Tableau is possible through dragging and dropping Measures and Dimensions onto these different Shelves.
Rows and Columns : Represent the x and y – axis of your graphs / charts.

#### Filter: 
Filters help you view a strained version of your data. For example, instead of seeing the combined Sales of all the Categories, you can look at a specific one, such as just Furniture.

#### Pages: 
Pages work on the same principle as Filters, with the difference that you can actually see the changes as you shift between the Paged values. Remember that Rosling chart? You can easily make one of your own using Pages.

#### Marks: 
The Marks property is used to control the mark types of your data. You may choose to represent your data using different shapes, sizes or text.

And finally there is Show Me, the brain of Tableau!





                                                                                                                                                                        
