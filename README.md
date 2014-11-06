Network report
=====
In this report I will be discussing and demonstrating how I used the software Gephi to create a multimodal network graph of my Facebook friends. 
First of all to begin I searched for netvizz on Facebook which gathered my network data and relationship of Facebook friends. Netvizz is a Facebook app that lets you to make a .gdf file out of your friends on Facebook. I downloaded this and saved the file to my laptop. From there I loaded this .gdf file onto Gephi. At first what appeared was a grey square with circles. I then picked the layout which was force atlas. From there what was visible was lines and circles.  Here’s a simple key guide to understanding these graphs:
•	Circle or round ball = Node = Facebook friend or group member
•	Line / curve = Edge = Facebook connection (friendship)
•	Node size = Betweeness centrality (measure of how much a node connects and disconnects)
•	Node colour = randomly picked colours used to symbolise the communities/clusters, shown on the graph and based on their modularity class.
Choosing force atlas makes the connected nodes attract to each other and the unconnected nodes to separate and create clusters of connections. I then zoomed in to see the nodes clearer and made the text larger to see who each node was. On the right hand side I clicked statistics and ran the modularity setting. From there it was time to partition the gdf. File, I clicked the dropdown for nodes and chose modularity class. This grouped each node into a colour coordinated communities/clusters. I then ran the average degree statistic which removed any single nodes not connected to other nodes. These statistics measured the betweeness of each node. I then returned to the ranking tab on the left hand side of Gephi. From the drop down I choose in-degree. Clicking on the diamond shape which measures the size I selected the minimum size of 15 and maximum of 35. To keep the larger nodes from overlapping smaller ones, I went to layout in left side and clicked the ‘adjust by sizes’ box. After this was completed I clicked the filters on the right side and selected the topography box. At this moment I selected this degree range filter and dragged to the box below. Following this I changed it accordingly to my prefrencens. This filter basically removes the ‘leaves’ in the network that are not connected to many other nodes. Click filter to apply changes. I had then gathered my information and narrowed down my Facebook friends to a smaller group which had 3 different edges and 3 types of nodes. From there I clicked the preview tab and in the node section I clicked the show labels button and refreshed the page. I had completed the graph and had an eye catching, visualising result of my Facebook network community clusters. To export the file I saved it as a PDF file. 

Finally I will demonstrate my understanding of all of the networking terms we’ve been using including: nodes, edges, influence, bridging, bonding, degree, betweenness, closeness and eigen-vector centrality. 

•	Node - a stage in a network or graph at which lines or paths intersect or join together.
•	Edge – the lines and connections of each node.
•	Bridging – ‘A bridge is a line whose removal increases the number of components in the network (Nooy, Mrvar and Batagelj, 2011).’
•	Betweenness centrality - is the shortest paths in the middle of any two nodes that pass through a certain node. A high betweenness suggests that that node is connected to many other nodes bonding the network of friends together. Nodes closers to the edges would have lower connections to other nodes in the network. 
•	Closeness centrality - shows how close one node is to all the other nodes in the network. 

To conclude ‘Gephi is an interactive visualization and exploration platform for all kinds of networks and complex systems, dynamic and hierarchical graphs.’ (Gephi.github.io, 2014). I found the site extremely interesting to use. Especially to see how my Facebook friends where portrayed on such a dynamic graph. It was a fun way of learning about the trends in social computing. 

