# WGU C964 Computer Science Capstone

## User Guide  
### Download Source Code  
1. To download the source code, select the button "Code" on github.
2. Download the ZIP file for the project.
3. Unzip the file to your computer.
4. Open the folder and extract the dataset.7z file.  
*This was the only way I could get past github's push file size limit, sorry.*
5. Make sure the resulting filename is "dataset.csv"

### Setup Project  

>
> Requires Python 3.12.2 or later  
>
*Project was built with VSCode in mind*  
1. Open the project inside of your IDE (preferrably VSCode)
2. Open your terminal and run ```python -m venv venv```  
3. Start the venv with one of the following commands depending on your system  
Windows using bash or powershell  
```source venv/Scripts/activate```  
Windows using cmd  
```venv\Scripts\activate```  
Mac using bash  
```source venv/bin/activate```  
4. Install the project requirements by running the command  
```pip install -r requirements.txt```

5. Please wait while the project dependencies finish downloading.  
6. Once complete, the project start point is ```exploration.ipynb```. You can click "Run all" to run the complete jupyter notebook.  
> This will result in a new output file being generated:
> ```cleaned_dataset.csv```  
7. You can now move to ```prediction.ipynb``` and click "Run all"  

### Add User Input  
1. The last 2 cells in ```prediction.ipynb``` contain the functionality to add a custom day.  
2. Enter a date and Weather condition in the fields provided.  
3. Run that current cell to create the test dataframe.
4. Run the next cell to get the prediction output.  
