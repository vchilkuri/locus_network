# locus_network
The directed graph network for various kinds of companies that comprise Seattle's aerospace industry.

## Methodology:

1) I decided to do this on d3.js as it would be helpful in creating highly interacitve graphs and can be optimized furthur without disturbing the earlier features.

2) The first task I did was to convert the xslx files into two different csv files and then after creating two CSV files, I studied the data. the feasible way to view this network would be creating a node link system. I planned on differentiating the nodes based on the Object category.

3) This graph could also be created using ccNetViz.js which I worked on during my summer but ccnetviz involved more customization rather than coding and it was not yet developed for parsing data efficiently from CSV files.

4) I then created a node link graph with good amount of variance in different colors so that the categories can be viewed without any visual hinderance.

5) With the number of nodes available, I was able to provide the user a flexibility to hover over the nodes to see the id and edges to see the label respectively. The node radius also increases when we hover over any point.

## Works planned but unable to complete:

1) I also planned to create a tooltip to display the Activity and Object when hovered over a node so that user can also understadn which nodes of same color belonged to same object.

2) Another feature could have been added, which I planned intitially, where we would be able to view the network by clicking on a particular node and the rest of the network would be faded out.
