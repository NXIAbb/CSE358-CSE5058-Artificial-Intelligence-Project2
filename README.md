Download Link :https://programming.engineering/product/cse358-cse5058-artificial-intelligenceproject2/


# CSE358-CSE5058-Artificial-Intelligence-Project2
CSE358/CSE5058 Artificial Intelligence Project2
Project Definition

In this project, you are required to color the map of the South America continent using a backtracking search algorithm. When coloring the map, two neighboring countries should not have the same color. Furthermore, you can use at most 4 different colors (blue, green, red, and yellow).

Table 1 presents the border neighborhoods of the countries in South America. You need to embed this information into your application in a way of your own choice (e.g., reading a CSV file, setting as program variables etc.).

Table 1. Countries on the continent of South America and their border neighbors


Country

Argentina

Bolivia, Brazil, Chile, Paraguay, Uruguay

Bolivia

Argentina, Brazil, Chile, Paraguay, Peru

Brazil

Argentina, Bolivia, Colombia, Guyana, Paraguay, Peru,

Suriname, Uruguay, Venezuela

Chile

Argentina, Bolivia, Peru

Colombia

Brazil, Ecuador, Peru, Venezuela

Ecuador

Colombia, Peru

Falkland Islands

NONE

Guyana

Brazil, Suriname, Venezuela

Paraguay

Argentina, Bolivia, Brazil

Peru

Bolivia, Brazil, Chile, Colombia, Ecuador

Suriname

Brazil, Guyana

Uruguay

Argentina, Brazil

Venezuela

Brazil, Colombia, Guyana

Figure 1 presents a sample map coloring for the continent of South America. The figure is created with plotly, a Python graphing library. You are already provided with the code to create such a graph in “submission.py” script. However, you have to make this code working by installing necessary dependencies. Please look at the dependencies section for more details.


Figure 1. Sample coloring of the map of the South American continent

To-Do

You are going to develop a Python application, which employs backtracking to color the countries in South America. Once the algorithm finds a possible solution, you should plot a choropleth map by calling “plot_choropleth“, which takes a dictionary as an argument. This dictionary should contain country names as keys and colors as values. Figure 2 shows the actual dictionary and function call plotting the valid map in Figure 1.


Figure 2. Sample dictionary and function call producing the colors in Figure 1.

Modify the script file (base.py) provided for you to develop a solution for the map coloring problem defined above. Create a PDF report describing your effort in this assignment. Define variables, domains, and constraints as shown in the lecture. Furthermore, include sample outputs in your report.

Dependencies

In order to run the map plotting function, you need to install the following modules into your virtual environment:

pandas (current latest version: 1.1.4)

plotly (current latest version: 4.13.0)

To-Submit

Submit the source code (rename your source file as name–surname–ID.py), your report in PDF format, and any additional files to run your application. Submitted file should be an archive (tar, zip, rar, etc.) named as name–surname–ID.xxx (e.g., alper-bilge-12345678.zip)

Submit your own work.

“Honesty is the best policy; I will stick to that.” – Miguel de Cervantes.

Notes

Please read this document very carefully.

Submissions not complying with the To-Do list will be disqualified.
