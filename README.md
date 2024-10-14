# This project was written using the React framework 
中文版说明在README_CN.md中

You can access this [demonstration link](http://101.132.112.146：3000 )To view the effect, click on the gray part to return 
I really like GROWLANSER, so I tried to replicate the UI menu animation of this game on the web. 
This is my second time publishing this project because I misspelled the warehouse name the first time.

Although I used React, I am not very good at using React, so the vast majority of functions here are implemented using native syntax. 

# The composition of the entire project 
In the src folder: 
- The "style" folder defines the styles of various parts of a webpage; 
- The "ts_tool" folder contains numerous functions; 
    - The interaction between the front-end and back-end is defined in "data_jax"; 
    - "Public_mod" defines some common classes and methods; 
    - "Ui_views" defines all interface animations; 
# Some Problems -20240628 
1. I lack something to showcase, so I can only make a rough framework; 
2. It seems difficult for me to add third level menu items in the leftform, even if I have left enough space; 
3. Currently, the support for the number of menu items is relatively fixed, making it difficult to modify; 
4. I only support asynchronous animation for 8 animations. If I want to achieve more asynchrony, I need to completely rewrite my namespace "GL1Box";