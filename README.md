# SomethingAwesome

## Run with reduced dataset

The code can be run with a reduced dataset, by downloading the UrbanSound8k dataset in this github repository and pointing the start of root_dir and csv_file directory strings to wherever this file is stored in the computer.

## Run with full dataset

To run this code successfully with the full dataset, you must upload the .ipynb file to google colab, and add a compressed file of the UrbanSound8k dataset to your google drive, available here:
https://urbansounddataset.weebly.com/urbansound8k.html
You will need to add '/content' at the start of the root_dir and csv_file strings and uncomment out the lines in the first cell related to extraction and mounting google drive. The code once run on colab will prompt for login for drive to access the dataset and extract it.

## Google colab link

The google colab file I used to train and test is at the link below:
https://colab.research.google.com/drive/10JhmD1Z7x187ud5UOOkOsbyr7gnNiaAR?usp=sharing
