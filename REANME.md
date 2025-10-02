## Submission Format Note

This project is submitted as a `.ipynb` Jupyter Notebook file instead of a `.py` file.

Reason:
- The entire development and testing process was done in Google Colab.
- My local machine does not have a Python interpreter installed to run `.py` files directly.
- As confirmed by the TA, it is acceptable to submit the `.ipynb` file as long as clear instructions are provided on how to run it and reproduce the results.

Please refer to the "How to Run" section below for step-by-step instructions to execute the notebook in Google Colab and replicate the output.


## How to Run

1. Drag and drop the provided `.ipynb` notebook file into Google Colab.
2. Upload all the attachment files from the project folder into Colab’s file directory.  
   **Important:** First unzip the `filemayuse.zip` folder before uploading its contents, because the notebook code does not include an unzip step. Then, upload the extracted files one by one into Colab.
3. Run each code block in the notebook sequentially (from top to bottom).

## Required Package Installation

Before running the notebook, make sure to install the following packages in Colab’s terminal or in a code cell:

```bash
For example:
...
pip install facenet-pytorch
pip install opencv-python==4.9.0.80
pip install pandas==2.2.1
...
they are mentioned in the code

