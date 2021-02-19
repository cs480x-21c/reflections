# Machine Learning for Visualization

![image](images/1_vMbB5fRW7LhS9RcStzbUCQ.gif)


## Link: https://medium.com/@enjalot/machine-learning-for-visualization-927a9dff1cab

## Description

For this weekly reflection, I want to dive into how Machine Learning can help us make better visualizations. This article is about a presentation made at OpenVisConf 2018 by Ian Johnson. Ian uses machine learning to help bridge the gap between computers and humans. One of his first interesting projects was visualizating how a neural networks learns the differences between a cat, dog, and a horse. The neural network was fed hundreds of different images of cats, dogs, and horses made with different amount of lines. These drawings are doodles, and the goal was for the neural network to recognize what type of animal is being drawn based on an imperfect sketch. A graph is then created base on the amount of strokes drawn per doodle, and categorized as either a cat, dog, or horse.

![image](images/graphml.gif)

The other interesting machine learning vis was "How do you Draw a Circle?" by Nikhil Sonnad. This visualization is a neural network that can determine if a circle is hand-drawn clockwise, or counter-clockwise. Nikhil then used this neural network to try to see cultural differences by region of how people draw circles. Interestingly enouigh, a graph can then be made about how likely a person is going to draw a circle in a clockwise or counter-clockwise rotiation based on region. What's cool here is people from Japan are 80% likely going to draw a circle in the clockwise direction. The United States sits at around 20%, which can be explained by the larger diversity of culture in the United States. It also turns out, that culture AND language have an affect on which way we draw circles.

Finally, Ian Johnson visualized his neural network:


![image](images/neuralnet.gif)

This is a visual representation of all the weights, nodes, and p-values of the neural network that work together to guess what kind of animal a doodle is. Each cluster contains doodles of similar stroke, shape, and design.
