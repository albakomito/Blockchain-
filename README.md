# Unit_18_Assignment-

## In pychain.py, we:  

* Import all libraries and dependencies (ln 25-33). 

### Step 1 (ln 34-58)  
* Create a Record Data Class, consisting of 'sender' and 'receiver' (both strings) and 'amount' (float).  

### Step 2 (ln 59-155)  
*  Rename the given `data` attribute to `record`, and set the data type to `Record`(per the class in Step 1). 
*  Create the hash_block(self) function (ln 81-101). 
*  Create the PyChain class and define the proof_of_work(self, block),  add_block(self, candidate_block) and is_valid(self) functions (ln 102-139).
*  Set up our Streamlit user interface or UI (ln 140-155). 

### Step 3 (ln 156-223)  
* Add Relevant User Inputs to the Streamlit Interface, and delete the input_data variable from the UI (having previously renamed the data attribute to record in Step 2).
* Add input text areas for the  'sender', 'receiver' and 'amount' attributes by creating one variable per attribute and using the function st.text_input('attribute name') (ln 174-185). 
* Use the st.button functions to create a button that adds previous blocks to the chain (ln 186-189). 
* Update `new_block` so that `Block` consists of an attribute named `record` which is set equal to a `Record` that contains the `sender`, `receiver`, and `amount` values (ln 190-203). 
* Continue with our streamlit code to include a header, a pychain dataframe, different difficulty levels in the sidebar, and a dropdown block inspector with prompt (ln 204-224). 

### Step 4
* Run our file in our terminal (see  gitbash1.jpg). 
* Enter several values for sender receiver and amount to create a blockchain.
* Verify the block contents in the sidebar's dropdown menu (see blockchain1.jpg), and
* Confirm that the blockchain is valid (see bottom of blockchain2.jpg and bottom of gitbash2.jpg). 
