# Data-visualization
Its all about creating visualizations from big data using extensive library that is D3.js

Without using D3.js buildin functions I have done created different layouts using d3.js. 
The details about the work I have done is below :

My objective is to create a dashboard for graph layout from scratch using d3.js. The purpose of this is to train myself to be able to create custom layouts as per my own choice.
The dashboard should enable users to upload a file containing an adjacency matrix. After loading file I have to  identify cycles, determining connectivity, classifying the graph as a General Graph, Directed Acyclic Graph (DAG) or a Tree, and laying
out (visualizing it) appropriately it on the screen. The user will be provided with layout options according
to the determined type of the graph. FOR EASE  dividing the code in different html files(each layout having different html file). 

Note: For laying out graphs, you CANNOT use any pre-built layout algorithm in d3 or any other
source. You must lay out the graph from scratch using d3.js. 

1. UI Design & Development (.html )
Creating a user-friendly design of my Intelligent Graph Layout webpage. The UI must contain the following features i.e., Develop a user-friendly file upload feature, allowing users to upload a file that contains an adjacency matrix. Analyze the
uploaded graph data to identify cycles. As a first step, determine the graph’s connectivity. If the
graph has disconnected components, ask the user to upload a connected graph. For a connected
graph, determine if the graph is one of these special types i.e., a Directed Acyclic Graph (DAG) or
a Tree or is it a general graph. Based on the type of the graph, the UI should intelligently offer the
users appropriate layout options on the screen to select how they want to visualize the graph.
The following options layout options should be shown as per the graph are as follows:

• General Graph:
1. Grid Layout
2. Chord Diagram
• Directed Acyclic Graph:
1. Sugiyama Layout
2. Radial Sugiyama Layout
• Tree:
1. Rheingold Tilford Layout
2. Icicle Tree Layout

NOTE: making html file for each layout for ease. 
Then the user can select any layout it want to be displayed. for instance in i want chord layout then I will select chord option and and chord page will be displayed oh that page i will have to upload a file and chord layout will be made from that respective input uploaded csv file. 
