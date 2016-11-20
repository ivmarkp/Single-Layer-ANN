# Single-Layer-ANN
An implementation of a single layer neural network in Python. This is a part of an article that I contributed to [GeekforGeeks](http://www.geeksforgeeks.org) technical blog. You can check it out [here](http://www.geeksforgeeks.org/implementing-ann-training-process-in-python/) to understand the implementation in detail and know about the training process.
## Dependencies
You need to install [NumPy](http://numpy.scipy.org/) library on your system to run the code. To know how to install NumPy, follow the instructions here according to your platform: https://docs.scipy.org/doc/numpy-1.10.1/user/install.html.  

If you're on Ubuntu/Debian platform like me, you can simply enter the following in the terminal:

    $ sudo apt-get install python-numpy

## Running the neural network
Clone this repository in your system and go to the root directory of the cloned copy i.e. `~/Single-Layer-ANN`
Now, just run `ann.py` in your terminal:

    $ python ann.py

To change the training example, you need to modify the training set for the network which is specified by numpy arrays named as `inputs` and `outputs` in the code; they basically represent input values and expected output for a given combination of inputs respectively.

**Note:** Since this is a single layer network, it can only work with linearly separable functions or patterns e.g. AND and OR. Trying to play with this network using XOR would be a waste of time. :)

### License
This code is distributed under the MIT license.
