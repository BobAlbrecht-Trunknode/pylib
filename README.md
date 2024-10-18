# Python Libraries for Accessing Trunknode
These are libraries for using data data from Trunknode in AI Traning. The purpose is to make accessing data in Trunknode as simple as possible. Libraries are configured for all major AI frameworks including PyTorch and Tensorflow. 

# Use
## PyTorch
### Installation Of TrunkNode
#### pip installation
pip install trunknode_torch<br>
or<br>
#### conda installation
conda install trunknode_torch
### Accessing Data
import trunknode<br>
my_dataset = trunknode.dataset(trunknode_id)

\# my_dataset can now be used in model training for PyTorch. It implements the required \_\_init\_\_, \_\_len\_\_, and \_\_getitem\_\_ interfaces that allow it to be used directly in traning of PyTorch models. 




