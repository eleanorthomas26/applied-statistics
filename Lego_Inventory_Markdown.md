# Lego Inventory
***Assignment 2 - Group 5***

![LEGO_logo svg](https://github.com/user-attachments/assets/5d485b23-c369-4161-9eb2-aadcf8fef3fe)


## Contents
1. Introduction and Purpose
2. Structure of the Inventory
    + 2.1. Sizes/Shapes
    + 2.2. Colors
3. How to use the Inventory
    + 3.1. Stock Overview
    + 3.2. Incoming Pieces
    + 3.3. Outgoing Pieces

## 1. Introduction and Purpose
At first, we were given approximately one hundred Lego pieces and were supposed to create a structured inventory that included information and quantity of every single Lego piece. These pieces consist of different shapes, sizes, uses, and colors, which we had to categorize correctly as a group. In general, the inventory is designed to provide an overview of the stock for a Lego Reselling company.

After preparing a complete overview of the inventory, we can decide on further planning and also how to deal with various orders. The overview of the inventory in a Google Sheet helps monitor the whole supply and demand flow.

You can find the [inventory here](https://docs.google.com/spreadsheets/d/1e5OsPttHjQvtAFLUt-rMEAGYMcvyG97LAem_8MwMLfk/edit?gid=450027551#gid=450027551).

## 2. Structure of the Inventory

The columns of the inventory relate to the shape/size of a piece and the rows correspond to the color. It is worth mentioning that it does not matter whether you assign the colors to the rows or the columns!

Also, below each column, several sub-columns correspond to the different shapes and then their specific size. For instance, one of the shapes among Lego pieces is rectangle and there are also different sizes such as 2x1, 2x4, and so on. For the last sub-column, we used categorical variables such as small, big, and flat.

![image](https://github.com/user-attachments/assets/dbba84c0-9577-43a0-bba0-a7498f29ffdd)

The picture above represents a simple overview of what the rows and columns of the inventory look like.

### 2.1. Sizes/Shapes

Pieces are first divided into general shape categories e.g. square, rectangle, trapezoid, circle, sword. 
The next subcategory divides shapes based on the number of holes/studs (length and width). 
The final subcategory considers the depth of the piece: 
+ Big refers to duplo pieces
+ Small refers to standard Lego pieces
+ Flat refers to pieces that are flat

### + Notes on size/shape
We did not label the direction of the slope of a trapezoid.
We did not consider the inner hub of a wheel and the tyre as separate pieces.
The above-mentioned notes are points that could help in improving the precision of the inventory. However, without considering them, we still managed to create a understandable and practical inventory.


### 2.2. Colors

Colors have a general description. Where there are more than two shades of one color, we have included a second tab with reference photos and RBG to identify the different shades.

Some colors such as green and blue had various spectrums which could not be overlooked. In order not to misclassify the colors, we took a picture of different colors and used them as our reference to classify other Lego pieces based on their colors.

![image](https://github.com/user-attachments/assets/96325326-31ec-4bff-a6d5-d30ac3b1e403)

The picture above shows how we tried to identify each single color related to each other.

## 3. How to use the inventory

### 3.1. Stock Overview
After counting all the Lego pieces, we found out that there are 103 pieces consisting of different shapes, sizes, and colors.
We also defined a simple sum operation to understand how many pieces per shape/color exist. For example, if you look at the last column of the Google sheet, you will notice there exist a total number of 13 red pieces. On the other hand, if you take a look at the last row of the sheet, you will be able to see how many rectangular pieces with the size of 2x4 (small) exist.

![image](https://github.com/user-attachments/assets/0a403a1f-3d8a-4500-91cc-a545911d3c7e)

The picture above shows a part of the inventory in the Google sheet. As can be seen, the quantity of each Lego piece is written, and the total quantity helps you determine what is going on inside the inventory of the company.

### 3.2. Incoming Pieces 

#### Previously received piece

Locate the piece in the table and increase the number in the cell by 1.

#### New piece

First define if it is the shape, color, or both which are new.

*For a new shape:*
+ Decide what level of category needs to be added e.g. is it a new type of square or is it a whole new shape altogether
+ Add the appropriate columns

*For a new color:*
+ Decide if it is a new shade or a whole new color
+ If it is a new shade of an existing color, create an entry in the color tab to explain the difference in RGB, alter the names of the shades to make identification easier (e.g. 'light' or 'dark'), and then add a row for the new color

Once the correct rows and columns exist, increase the correct cell by 1 to mark the incoming piece. 

### 3.3. Outgoing Pieces

Locate the piece in the table and decrease the number in the cell by 1.
