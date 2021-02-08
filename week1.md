Link: https://www.ytb-network.com/
Reddit Post: https://www.reddit.com/r/dataisbeautiful/comments/leva2m/oc_small_part_of_youtube_channel_recommendations/
Source: r/dataisbeautiful

This visualization acquired is a network of nodes representing the connections between channels as seen through YouTube’s recommended algorithm. For those of you who are not familiar, lets walk through an example: Say you are on Pewdiepie’s YouTube channel (The biggest orange dot in the middle) and you find yourself watching many of his videos. YouTube assumes you are enjoying that content and “recommends” you watch other channels based on Pewdiepie’s content. So, from that we can this quickly creates a vast network of all the interconnections from the just starting from one channel. This particular data vis claims to have started with 54 french YT channels, and from there it created this vast network of around 5000 nodes (each one representing a unique channel).  

Cool features: 
1.	The size of the bubble for each YouTube channel corresponds to the number of subscribers for that person. (like our homework). 
2.	The search panel on the left side was unique because it allowed you to see just a specific cluster and it made the visualization a lot clearer       when trying to see how network was spread out. 
3.	The cluster feature was built using “Force Atlas” which puts channels that are similar in real life close together. This explains why the french      channel starting point is far away from the English Channel.
4.	I thought that the tab that pulls out to the side that gives more information on the channel was useful for figuring out further connection. 

Other Comments: 
1.	This is hard to really fix due to the scale of the work but, sometimes the connections between the lines are skinny making it hard to see the connection between certain nodes. 
2.	Improvement: Maybe provide a link to the channel on the pullout tab using string concat to see how the content between channels compares. 
