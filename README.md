# blockchain_ledger_web_Interface_system

# Blockchain-based ledger system with a user-friendly web interface 

Objective: To create a blockchain-based ledger system, complete with a user-friendly web interface using python and Streamlit library to create the web interface.
The file containing the python is in the github repository under file name: pychain.py
The code starts by importing all the libraries we will need to create the blockchain ledger and web interface.  The challenge had provided a basic code that then is updated to define a new pyhton data class named “Record” and create a “sender”, “receiver” and “amount” attributes with their specific datatypes.  The code then modifies the block data class to store the record data.
As a next step in the python coding, we input the areas and messages for the user interface for “sender”, “receiver” and “amount” attributes and to add a new block as records are created. The code then adds a sidebar for block difficulty and a block inspector showing a summary for each record.

Finally, the code was tested by running the streamlit application in a terminal, creating records and adding new blocks, (Each with its prev_hash value, time stamp and nonce numbers which were based in the Block difficulty set up for each entry.)
The following is the screenshot showing the web interface with the attributes, difficulty and inspector blocks, 3 new records and the validation button showing a “true” to validate the blockchain.

 <img src="/Images/BlockchainsSreenshot .png">
 

###Resources
1.	Fintech Bootcamp-UC Berkely Extension Class materials
2.	Bootcamp tutoring session 4/24/24.
