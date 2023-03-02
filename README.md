# blockchain-ledger

The purpose of this project is to build a locally hosted block chain which is able to accept new blocks and validate them as well. <br>
The steps to complete the ledger were: <br>
-Create a Record Data Class <br>
-Modify the Existing Block Data Class to Store Record Data <br>
-Add Relevant User Inputs to the Streamlit Interface <br>
-Test the PyChain Ledger by Storing Records <br>

## Usage

To use this program, download github repository clone and open the "pychain.py" file, run the file and type "streamlit run pychain.py" into the command line.  This will open up the host on your browser.  From there you can add info to new block to add to a new block chain.  Here it is in action: <br>
![streamlit](/images/giphy.gif)
You can see it records the sender, receiver, and amount for each block in the ledger.  It also shows the difficult of each block, and can validate the chain.
![Validation](/images/validation.png)

## Technologies
This project was created with on with python v3.7.13.  It also uses streamlit for the user interface

[pandas](https://pandas.pydata.org/) is an open source data analysis and manipulation tool.

[Streamlit](https://streamlit.io/) turns data scripts into shareable web apps.



---


## Licesne
GNU public lisence.