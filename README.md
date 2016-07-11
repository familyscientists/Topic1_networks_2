# Topic1_networks_2
Visualizing a network in Gephi

I am including a word document with the basic info of Gephi and also an excellent 20 min video, from my social dynamic network professor, with an overview of the software. 

https://www.youtube.com/watch?v=TtAGBbYno7w

Steps on Gephi:
1. Import Spreadsheets using Data Laboratory icon: nodes and links (be aware with "As table:" option)
2. In Overview, use layout options. I chose: Force Atlas, Radia Axis and Random layout.
3. On Statistics window run the basic metric (centrality options): Average degree, network diameter find more info about layouts and metrics here (https://gephi.org/tutorials/gephi-tutorial-quick_start.pdf) 
4. On Appearance window, color and size the nodes. I colored by region and sized by degree.
5. Go to preview and set your prefered options. 
*Be aware with Edges thickness, because of the variance of the weigths I had to use Thickness = 5.0E-9
6. Export pdf or png 

*Extra steps for geocoded nodes.
1. I already uploaded the same nodes database including two new columns: latitude and longitude for each country.
On Gephi:
2. Import new spreadsheet. In the Import spreadsheet window (import seetings, where you have to specify the type for each variable) you HAVE to select "Double" for latitude and longitude variables.
3. You have to download two layout plugins: "Geo Layout" and "Map of countries". To do that, go to Tools -- Plugins and then install them. This step will add two new layouts.
4. Go to Layout window, select Geo Layout and then match each variable: latitude and longitude and Run it. Then, voilà.
5. Go to Layout window, select Map of countries if you want a worldmap as background.
