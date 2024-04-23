# slcapstone
In this data, we will try to navigate the world of gardening, by discovering the best solutions possible for new beginners.
 #You will want to import pandas, requests, BeautifulSoup, matplotlib, numpy, and re.

1) Pull in the data from , sharon/vegetables-herbs-and-edible-flowers | Workspace | data.world. Make sure to select the Raw file. *Before Pulling the csv file into python make sure to check the images column and verify the images are not duplicated in the cell. If cell is empty pull a jpg file of that plant and place it into the cell.
2) Shorten the Name column to only include first plant name and rename the column plants.
3) Drop any unneccesary columns
4) Narrow down information on both the spaceInstructions column and the harvestInstructions column to only include the number. Respectively, spaceInstructions in 'inches' and harvestInstructions in 'weeks'.
5) Make a seperate column to only include the names of compatible plants or if best left alone
6) Rename column 'Name' to 'plants'
7) Make a new csv file of the cleaned data and pull it into PowerBI

8) Having no original pest datasets you will need to create your own in Excel. Using this guide (15 Plants to Grow for a Pest-Proof Yard - Bob Vila). Make a column that includes the photo of said pest. Make Dataset into a csv and pull it into PowerBI

9) We will now be pulling Data For the hardness Zone to make a functional map in PowerBI. The data Will be found here (PRISM Climate Group at Oregon State University and https://simplemaps.com/data/us-zips).
10) Read in both datasets first
11) Rename zipcode columns on both so that match to make for an easy merge. Merge them on 'zipcode'
12) Drop any uneccessary columns
13) Create a new column that returns month time frame for each zone. Information for that can be found here (Vegetable Planting Guide by Zone: A Professional's Advice - Gardening Flow)
14) Make cleaned dataset into a csv and pull in into PowerBI

15) Once you have the required data in PowerBI, make a presentation ansering these questions. What time of year to start growing plants?  Which ones are considered easy to grow? Which plants also keep pests away for the best combination growth? Which plants grow best with other plants? What are the top five best plants to grow based on easy to grow, less pest issues, grows best with surrounding plants. What is the distribution levels of harvest time, and spacing.