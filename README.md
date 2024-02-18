# mathy_neural_net
My artificial neural network pet project. The network utilizes the definition of the derivative to compute gradients and does not make use of Python ML libraries like PyTorch or Scikit-Learn. Enjoy!

Why did I create this project?
* Building a neural network without the aid of ML libraries was a very interesting exercise for me. Previously, I had learned about ML through PyTorch and Scikit-Learn, and I felt as if I wanted to gain a deeper understanding of the mathematics behind ML models.

Are there any issues with the project? 
* As of Feb. 17, 2024, the neural network is terribly inefficient in terms of the time it takes to run. This is the result of me designing the network while prioritizing the use of mathematics over the network's actual functionality. 
* Computing gradients in the way that I do -- using the definition of the derivative with lim(h) -> 0 -- is very slow. 

What are my future plans for this project? 
* The changes I hope to implement deal with making the network more time-efficient.
* I have recently explored automatic differentiation (relies on recursing through mathematical operations, which take the form of Python functions) as an alternative method of computing gradients that will likely be faster.
* General optimizations and removals of redundant code will invariably improve the network's time efficiency as well. 

