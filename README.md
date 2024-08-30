# Capstone-3

`Syarah` is one of the biggest online based platform marketplace from Saudi Arabia that are specialized in the sale and purchase of new and used cars. The website offers a variety of vehicles, including sedans, SUVs, trucks, and more. It also provides users with detailed information on the cars available, including specifications, prices, year release, and sometimes you can negotiate the price. Syarah itself acts as a third party business company for promoting in selling new and used cars, providing business or individual to buy their cars.

In this case, we are going to:
1. **Make an analysis of dataset distribution and dataset features to target (price).**
1. **Make an appropriate machine learning model to determine the right selling price of a car.**

The dataset contains 5624 records of used cars collected from [syarah.com](https://syarah.com/). Each row represents a used car. Other information regarding each car is the brand name, model, manufacturing year, origin, options, engine capacity, transmission type, mileage that the car covered, region price, and negotiable.

|No.|Column Name|Data Type|Description|
|-|-|-|-|
|1.|Type|object|Type of used car|	
|2.|Region|object|The region in which the used car was offered for sale|
|3.|Make|object|The company name|
|4.|Gear_Type|object|Gear type size of used car|
|5.|Origin|object|Origin of used car
|6.|Options|object|Options of used car
|7.|Year|int|Manufacturing year
|8.|Engine_Size|float|The engine size of used car
|9.|Mileage|int|Mileage of used car (In kilometer)
|10.|Negotiable|bool|True if the price is 0, that means it is negotiable
|11.|Price|int|Used car price (In Saudi Arabia Riyal)
