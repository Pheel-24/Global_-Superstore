# Global Superstore

![](superstore1.jpg)

## Introduction

This is a Power BI project on Global Superstore which is a global online retailer based in New York, boasting a broad product catalog and aiming to be a one-stop-shop for its customers. The superstore’s clientele, hailing from 147 different countries, can browse through an endless offering with more than 10,000 products. This large selection comprises three main categories: office supplies (e.g., staples), furniture (e.g., chairs), and technology (e.g., smartphones).

## Problem Statement

The project is to help Global Superstore analyze and draw out meaningful insight from the Superstore dataset which would aid management in making informed decisions to improve performance and profitability.

## Skills/concepts demonstrated:

The following Power BI features were incorporated;
DAX, quick measures, filtering, data modeling, tooltips.

## Data Sourcing

Click [here](https://docs.google.com/spreadsheets/d/1nxESpFzWjlGDMGDVLH69xmDzIl9l6OEq/edit#gid=633280281)

## Data Transformation

A new table called _Calendar_  was created using DAX to derived day, month and year from the date column given.

## Modeling

Automatically derived relationships were adjusted to remove and replace unwanted relationships from the desired relationships.

![](modeling.png)

## Analysis/Visualization

1a. What are the three countries that generated the highest total profit for Global Superstore in 2014?

In 2014, the top three countries with the highest total profit are United States ($93,508), India ($48,808) and China ($46,794).

![](top_3.png)

1b.	For each of these three countries, find the three products with the highest total profit. Specifically, what are the products’ names and the total profit for each product?

•	United States

Canon imageCLASS 2200 Advance Copier - $15,680

Hewlett Packard Laserjet 3310 Copier - $3,624

GBC DocuBind TL300 Electric Binding System - $1,911

•	India

Sauder Classic Bookcase, Traditional - $2,420

CISCO Smart Phone, with Caller ID - $1,609

Hamilton Beach Refrigerator, Red - $1,440

•	China

Sauder Classic Bookcase, Metal - $2,420

Bush Classic Bookcase, Mobile	- $1,221

HP Copy Machine, Color - $1,196

United States          |    India      |   China
-----------------------|---------------|------------------
![](united_states.png) |![](india.png) |![](china.png)

2. Identify the 3 subcategories with the highest average shipping cost in the United States.
	
 The subcategories with the highest average shipping cost in United States are
• Copiers – 165.29
• Machines – 132.25
• Tables – 69.95

![]()

3a. Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African countries?

In 2014, Nigeria’s profitability compared to other African countries is the lowest with a total profit of -$23,285. This means that in 2014, Nigeria was at a huge loss.

![]()

b. What factors might be responsible for Nigeria’s poor performance? 

Nigeria’s poor performance was due to their relatively high shipping cost and discount rate. The shipping cost averaged at about $5.50 which is the second highest shipping cost in Africa and the discount rate average at about 0.70 which is amongst the highest in the world.

![]()
