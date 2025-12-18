# ehalsey-webcrawler-isc220-README

--------------------------------------------------------------------------------------------------------------



I wrote my web crawler in Google Colab, using a Python Notebook. The code is broken down into "cells", making it easier to distinguish the different sections of code. Each cell has detailed annotations that can be seen by opening the code in the original link: https://colab.research.google.com/drive/12gE1pEs4V3nv85PEc9TWA0Ckd0dFHhRJ?usp=sharing 



--------------------------------------------------------------------------------------------------------------



### COMPILING AND RUNNING THE PROGRAM



#### OPTION A. GOOGLE COLAB



Since this program was written in Colab, it is easier to run it as a notebook. Here are the steps to compile this program:



1) Click the link above or copy and paste it into your preferred browser.



2) Click the "Run All" button on the top left of the toolbar. This will run all the cells in the program and automatically start the main code block.



3) Follow the prompts in output box of the last cell. They should read:



      `Enter what you're searching for:`

      `Enter the starting URL for the web crawl:`



4) Watch the magic happen!



I prefer Colab for projects like this since it is more accessible and requires less overhead or setup. However, you can also run it in your favorite Python IDE.





#### OPTION B. PYTHON IDE

#### 

1) You will need to download the following libraries:

- bs4 | BeautifulSoup

- collections | dequeue

- requests

- urllib | robortparser

- urllib.parse | urlparse, urljoin



  a) This can be done in your terminal using the `pip install` command.

  b) If you use Anaconda, DO NOT use `pip`. This is unsafe and can cause dependency issues. Instead, open the Anaconda Shell and use `conda forge`.



2) Open the program in your IDE of choice. Move all the import statements to the top of the program.



  a) Having imports dispersed throughout the program may cause issues when running in an IDE.



3) Run the program and follow the prompts. They should read:



      `Enter what you're searching for:`

      `Enter the starting URL for the web crawl:`



4) Watch the magic happen!



--------------------------------------------------------------------------------------------------------------



### APPROACH



I initially wrote this program by following along with a video from my professor. I liked how it began, but since we were already in Colab, I decided to use the notebook feature for easier organization and clear annotation.



My next step was to create a running list of URLs visited. This step took a while to figure out the logic, since I'm not familiar with search algorithms in Python. I ended up using GeeksForGeeks as a reference and starting point: https://www.geeksforgeeks.org/dsa/breadth-first-search-or-bfs-for-a-graph/



After the BFS was finally successful, I included more error checking and error messages for each step to ensure everything would be caught, and that the end user would get a proper explanation of the problem.



Finally, I went back and implemented the extra credit URL frontier. I liked this part because even though it was difficult, it made the program much more efficient and useful.


