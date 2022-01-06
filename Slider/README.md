# Test

This provides the user with 2 independent maps side by side and a slider to compare both -- though the slider is somehow hidden for some reason.
For now if the user wants to plot on either map, they have to manually mess with the url. For example if I wanted to plot Ghana with an ADM2,
The way to do it would be the url followed by ?ADM=ADM#&ISO=Country_ISO ---> http://127.0.0.1:5500/Test2/index2.html?ADM=ADM1&ISO=GHA or 
url followed by ?ISO=Country_ISO&ADM=ADM#& ---> http://127.0.0.1:5500/Test2/index2.html?ISO=GHA&ADM=ADM1
This will plot two geojsons on two separate maps. This is much closer to what we want to achieve
