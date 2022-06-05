# PyChain_Ledger

![blockchain](https://user-images.githubusercontent.com/95719899/172059049-c6574eb0-e120-4b78-bc9c-fe237c63bde3.jpeg)

---

The purpose of this application is to build a blockchain-based ledger system that allows partner banks to conduct financial transactions and to verify the integrity of the data in the ledger. This user-friendly web interface allows users to add a block to the chain that includes sender, receiver, and amount information. Users can validate the chain, inspect any of the blocks, and adjust the block difficulty.

---

## Technologies
A Python 3 (ipykernal) in JupyterLab was used to write this application. Additional Python libraries are imported into the start of the app: 

![Screenshot 2022-06-05 095351](https://user-images.githubusercontent.com/95719899/172059136-f33c3abe-2ecf-4cf8-ab5d-91ef2fb3cc6e.jpg)

---

## Installation Guide

To run it from local computer, clone repo. From the Terminal, activate conda envirnoment; change directory to repo folder,
and type `streamlit run pychain.py`. This will launch a web browser with a local URL such as http://localhost:8501. *Note that you will need to install some libraries/dependencies if you do not already have them. You can do so by typing `pip install requirements.txt` into the terminal.* 

---

## Usage 
1. Enter values for the sender, receiver, and amount. Then click the "Add Block" button. Do this several times to store several blocks in the ledger. (You can also adjust the block difficulty if you would like. This indicates how many zeros must be at the beginning of the block hash.)

2. Verify the block contents and hashes in the streamlit drop-down menu.

![Screenshot 2022-06-05 094509](https://user-images.githubusercontent.com/95719899/172059296-80e92c37-f6bf-4519-81ec-6303badc5904.jpg)


3. Test the blockchain validation process by clicking on the "Validate Chain" button.

![Screenshot 2022-06-05 094544](https://user-images.githubusercontent.com/95719899/172059302-7519d6b4-9ce9-4dc6-8362-a0642e6f8ff5.jpg)


---

## Contributors

Thank you to UC Berekely for the data and reference code
For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero
