# NDS
# Network Decentralized Storage
(Or should be DNS - Decentralized Network Storage?)

# What is NAS?
Network Attached Storage (NAS) is, basically, a local server made only for store files. The server has multiples storage units (HDD or SSD) and RAID capacity.

# What is NDS?
Network Decentralized Storage (NDS) has the same purpose of NAS, but instead of using one server for store your files, your server will be a part of a network where your files will be.

# How does it works?
On NDS, your files will be avaiable on multiple Nodes, so you can download them anytime you want, anywhere.

## Splitting up de files
Storaging raw data on other's people server isn't a great idea. That's why each Node will only have a small part of the data.
When you upload a file, we'll separate into multiple parts (small binary files), each part will be sent to a different Node on the NDS Network.

### Availability
When we trust our data to someone, we need to make sure you can access it whenever you want. If your file is in only one place and it gets shutdown or without internet connetion, you lose your data. And since we split our files into multiples pieces, all these pieces must be always available.
To make sure of this availability, we send every piece to multiple Nodes, so, if one Node goes down, you can still access from another node. Plus, you gain redundancy for sending the same file to multiple locations.

#### How can we make sure a Node is reliable?
The internet is scary, we can't trust everyone. TODO: Finish this sentence.
