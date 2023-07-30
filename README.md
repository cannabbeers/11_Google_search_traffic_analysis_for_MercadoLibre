# 11_Google_search_traffic_analysis_for_MercadoLibre
Module 11 Challenge

## User Story
Step 1: Find unusual patterns in hourly Google search traffic

Step 2: Mine the search traffic data for seasonality

Step 3: Relate the search traffic to stock price patterns

Step 4: Create a time series model with Prophet




If you're using Windows, you may install `google-colab` or simply run the code in your jupyter notebook.

macOS users: find and open `forecasting_net_prophet.ipynb` and click the button at the top of the page.

          *** be sure to unhash the first section of code if attempting to run in Colab ***
            
        <! # Our instructor said we can skip the google colab piece if on windows
        # however, before he told us it was ok to skip, I found some stuff like the 'open in colab' button while trying to figure out colab
        # see code reference in readme for the fancy colab button and this may even work in colab if you unhash all colab dependencies
        # have not tested and disabled since causing problems with my matplolib inline, (i think) 

        # Install the required libraries
        # !pip install pystan
        # !pip install prophet
        # !pip install hvplot
        # !pip install holoviews -->

Windows users: 

    If missing any of the libraries listed below, they must be installed in your `dev` environment prior to launching jupyter lab: 
        
  review whole list:
  
        $ conda list 
        
  check for each individually:
        
        $ conda list <name_of_library> 
        
  you can also try `pip install` for these, but recommend full installation:
  
        $ conda install -c conda-forge pandas
        $ conda install -c conda-forge hvplot
        $ conda install -c conda-forge pystan
        $ conda install -c conda-forge holoviews
        $ conda install -c conda-forge prophet
        $ conda install -c conda-forge watermark
        


      
      
## Usage

1) Navigate to my repo "11_Google_search_traffic_analysis_for_MercadoLibre"
2) Press the button `<> Code` to get the URL for HTTPS or SSH, proceed to clone the repo locally
3) Open the folder your cloned repo is located, activate your dev environment in Python=3.7
4) Launch Jupyter Lab from GitBash or Terminal

If you want to try running in `Google Colab` *Click on the button at the top of the notebook to launch `google-colab` and proceed to run the code*

### Code source references: 

+ ([Open In Colab Badge Icon](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

+ https://matplotlib.org/3.1.1/gallery/ticks_and_spines/tick-formatters.html


      
