Video Game Sales analysis

The purpose of this analysis is to investigate what makes a successful video game. The industry is an immensely popular and lucrative one that earns billions of pounds each year. It is imperative for game developers to produce video games that sell well in order to keep producing the games. This is due to the high production cost, the video game Destiny cost over half a billion to produce whereas the video game GTA V was the fastest media product to achieve 1 billion dollars in revenue.

The analysis uses two datasets and combines them, one for nintendo game sales and one for video game review scores. Only nintendo games were used as that is the data that was available and useable... after some fixing. The combined data contains games released up to 2021. 

Sales data was acquired from the url: https://www.kaggle.com/datasets/codefantasy/list-of-best-selling-nintendo-games

Review score data was acquired from the url: https://www.kaggle.com/datasets/deepcontractor/top-video-games-19952021-metacritic

As a result, the code presented in this analysis titled "Assessment.ipynb" runs through using a regression and KNN analysis to elucidate the links between sales, review scores, video game genres and platforms. The full details will be presented in the 2 page report.

To execute the code you will need to have python installed. It is recommended to use anaconda and jupyter lab or jupyter notebook to run the notebook script. The script ws written with python 3 in a jupyter notebook. Launch jupyter lab and open the notebook file "Assessment". The data should be included in the file presented and the file should therefore be set as your working directory. All packages used were, as far as I know, included with the installation of anaconda. However, in the event a package was not included, please follow these steps.

1. Open a terminal in jupyter lab.
2. Type into the terminal everything that follows the colon: pip install package_name

Example: pip install pandas

That should install the packages. Nothing else will be required to run this code once the data and packages are installed.

To run the code:

1. Download the full folder including the two data files, the report and the notebook "Assessment.ipynb"
2. Ensure you have read through this read me properly
3. Open the notebook and run the code in sequence by pressing shift enter, the annotations should help you understand what the code is doing and explain the output. Refer to the report for additional comments/info.
4. Should any of the code fail, ensure that the libraries are installed using the above instructions, here is a list of the libraries used:

pandas
numpy
seaborn
matplotlib
warnings
sklearn
statsmodels
math

This is all the info you require to successfully run through the code, hopefully you enjoy the analysis looking at a snapshot of the video game sales and review data for Nintendo consoles from the Nintendo 64 onwards.

