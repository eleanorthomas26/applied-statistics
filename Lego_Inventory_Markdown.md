# Lego Inventory
***Assignment 2 - Group 5***

## Contents
1. Introduction and Purpose
2. Structure of the Inventory
    + 2.1. Sizes
    + 2.2. Colors
3. How to use the Inventory
    + 3.1. Stock Overview
    + 3.2. Incoming Pieces
    + 3.3. Outgoing Pieces

## 1. Introduction and Purpose
At first, we were given approximately one hundred Lego pieces and were supposed to create a structured inventory that included information and quantity of every single Lego piece. These pieces consist of different shapes, sizes, uses, and colors which we as a group had to categorize correctly. In general, the inventory is designed to provide an overview of the stock for a Lego Reselling company.

As for the purpose, after preparing a complete overview of the inventory, we can decide on further planning and also how to deal with various orders. The overview of the inventory in a Google Sheet serves as an assistance to monitor the whole supply and demand flows.

You can find the [inventory here](https://docs.google.com/spreadsheets/d/1e5OsPttHjQvtAFLUt-rMEAGYMcvyG97LAem_8MwMLfk/edit?gid=450027551#gid=450027551).

## 2. Structure of the Inventory

The columns of the inventory relate to the shape/size of a piece and the rows correspond to the color. It is worth mentioning that there is no difference whether you assign the colors to the rows or the columns!

Also, below each column, several sub-columns correspond to the different shapes and then their specific size. For instance, one of the shapes among Lego pieces is rectangle and there are also different sizes such as 2*1, 2*4, and so on. For the last sub-column, we used categorical variables such as small, big, and flat.
![image](https://github.com/user-attachments/assets/af98e5d5-1c97-47a9-90d1-8d1e12ceda1b)


### 2.1. Size/Shape

Pieces are first divided into general shape categories e.g. square, rectangle, circle, sword. 
The next subcategory divides shapes based on the number of holes/studs. 
The final subcategory considers the depth of the piece: 
+ Big refers to duplo pieces
+ Small refers to standard Lego pieces
+ Flat refers to pieces that are flat

### Notes on size/shape
We did not label the direction of the slope of a trapezoid.
We did not consider the inner hub of a wheel and the tyre as seperate pieces. 


### 2.2. Colors

Colors have a general description. Where there are more than two shades of one colour, we have included a second tab with reference photos and RBG to identify the different shades. 

## How to use the inventory

### Incoming Pieces 

#### Previously recieved piece

Locate the piece in the table and increase the number in the cell by 1.

#### New piece

First define if it is the shap, colour or both which are new. 

For a new shape:
+ Decide what level of cateogry needs to be added e.g. is it a new type of sqaure or is it a whole new shape alltogether
+ Add the appropriate columns

For a new colour:
+ Decide if it is a new shade or a whole new colour
+ If it is a new shade of an exisiting colour, create a entry in the colour tab to explain the difference in RGB, alter the names of the shades to make identification easier (e.g. 'light' or 'dark') and then add a row for the new colour

Once the correct rows and column exists, increase the correct cell by 1 to mark the incoming piece. 

### Outgoing Piceces

Locate the piece in the table and decrease the number in the cell by 1.
