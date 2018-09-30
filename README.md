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

![Screen 6](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_6.png)

When you drag and drop fields onto the visualisation area, Tableau makes default graphs for you, as we shall see soon, but you can change these by referring to the Show Me option.

**Note:** Not every graph can be made with any combination of Dimensions or Measures. Each graph has its own conditions for the number and types of fields that can be used, which we shall discuss next.

### 2.3 Various Graphs and Charts
So far we have pretty much covered the theoretical knowledge. Let's finally begin with some visualisations now.

Let’s begin with the simplest visualisation, and that is displaying the **Net Statistics** numbers. Tableau, being as smart as it is, automatically computes such values under **Measure Names** and **Measure Values**. Follow my steps to make what is called a **Text Table**:

1. Drag **Measure Names** from Dimensions onto the central empty area so that you see a Text Table.
1. **Measure Names** will be displayed automatically onto Rows, so drag it from Rows to Columns.
1. Since we don’t really need Measures like the Row ID, Discount etc, you can drag them off from below the Marks Pane, to get something like this :

![Screen 7](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_7.png)

**Note:** Don’t get confused by the different colours of the fields that you see. Just remember one small trick : Blue means **Discrete** and Green, **Continuous**.

So we have the net Sales and Profit values, let’s delve a little deeper by getting the **Sales and Profit Values over the years**. Let's make another, but a more detailed, Text Table :

1. Drag Order Date from Dimensions and Sales from Measures to Rows.
1. Right click on the green Sales Pill, and select Discrete, in place of Continuous, since we want the explicit values and not the bar graphs.
1. Finally drag Profit on the ‘abc’ column to get:
![Screen 8](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_8.png)
1. Do the same thing for Monthly Sales and Profit Values, but this time change the format of Order Date, from Year to Month, by right clicking on Order Date in the Rows, and choosing Month, to get something like this:
![Screen 9](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_9.png)

We have just covered the numeric part of the Dashboard, but that is not its selling point. It’s the Line Charts.Let's quickly learn how to make one:

1. To create the chart of Sales and Profit Growth, drag Order Date over the Columns, Sales over Rows and then Profit over the formed Sales axis – so that you see an equals sign – to get the following:

![Screen 10](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_10.png)

1. Repeat the same to find the Peak Sales and Profit Months, but again change the format of Order Date, from Year to Month, and get:

![Screen 11](https://raw.githubusercontent.com/AppliedResearchAndInnovation/dac_workshop/master/images/Screen_11.png)

If you were to click on Show Me, you will see the different types of Line Charts that you can make, and if you were to hover over each of them, you will get to see their Dimension and Measure requirements too. In case you ever feel lost, I recommend referring to Show Me.

With the previous visualisations, we had gotten a brief overview of the Superstore. Let’s dig a little deeper now. The next thing that I can think of exploring is the demographic of the Sales and Profit. What are the States that have the highest Sales Revenue, which ones are generating the maximum Profits:



















                                                                                                                                                                        
