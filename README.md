# Cache Size Identification Project

### Technologies used
* Python
* Bash scripting
* Intel-MLC
* lmbench
* tinymembench

### Code example
Please review the Python script I have placed in this folder, which shows how I used Python with the Pandas package to structure and analyze data from the selected tools. 

If you are interested in our project results, please review the PDF also placed in this folder.  

### Background
I worked on this project as part of a graduate-level class in the Department Electrical and Computer Engineering (ECE) at Duke University.  The course was ECE 590: Conventional and Emerging Memory Systems and was taught by Dr. Helen Li.  I was enrolled for the Spring 2020 semester, and my partner for the project was Leon Riesbos, a PhD student in the ECE Department.

### Project structure
The goal of this project was to use tools available to collect data on cache access latencies and analyze the data to determine experimentally machine cache size.  

Both my partner and I researched available tools, and we selected intel-mlc, tinymembench, and lmbench, which we were able to download for free from their respective distributors.  We also both researched likely cache sizes for our machines.

As Leon had more experience working with operating systems, he tested the tools on his machine and created the scripts to help run the tools.  We tested each tool on our personal laptops, and Leon tested the tools on a virtual machine provided by the Duke Computing Cluster.

Once the data was collected, I created a Python program to clean the data and detect edges.  These edges could be used to determine experimentally cache size thresholds.  Together we plotted the data and compared apparent jumps in the scatterplots to the edges detected with the program.  We worked together to create a short paper in IEEE format which was submitted for our class.
