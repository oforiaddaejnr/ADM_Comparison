# Test3

This provides the user with 2 different tile layers and a slider to compare both.
The user can choose what country to plot on the map, but the problem is, the plotted map
covers both tilelayers at the same time instead of one. The reason being, both tile layers are 
overlapped on one map, and both tile layers have the same z index. I was able to mess around with the z index to
get it to plot on one tilelayer at a time, but it seems it's impossible to plot two diff layers on separate tiles
