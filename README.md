# mathy_neural_net
My artificial neural network project. The network utilizes mathematics to compute gradients and do backpropogation, without making use of Python ML libraries like PyTorch or Scikit-Learn. Enjoy!

Why did I create this project?
* Building a neural network without the aid of ML libraries was a very interesting exercise for me. Previously, I had learned about ML through PyTorch and Scikit-Learn, and I felt as if I wanted to gain a deeper understanding of the mathematics behind ML models.

Are there any issues with the project? 
* As of Feb. 17, 2024, the neural network is terribly inefficient in terms of the time it takes to run. A large part of the inefficiency is the result of my use of Python lists (O(N) access) for just about all internal node and weight storage. 
* Computing gradients in the way that I do -- using the definition of the derivative with lim(h) -> 0 -- is also very slow.
