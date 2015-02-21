# TopicsClient
A Web Client for the Topics service

Web client
======
The webclient uses jQuery for the dynamic elements. The graphing uses d3.js and creates a scatter plot from the data obtained from the node server included in this repository. The web client also has a feature to show how people in different States in the USA feel towards the topic. This feature uses DataMaps and a JSON file called states included in this repository. All positive scores are shown in green, negative scores are red, a score of zero is gray, and no data is black.

The Web Client graphically displays the results from the sentiment analysis in a plot graph and a map of the US. The data only updates when the topic changes. If new data is requested when on the plot section, all the data gathered is from all over the world, however, when looking at the US map the only data shown is the data from the US. 

To run the Web Client locally bower is necessary for DataMaps

    -$ bower install datamaps
