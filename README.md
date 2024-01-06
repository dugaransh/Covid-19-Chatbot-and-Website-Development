# Covid Chatbot and Dynamic Website

<h2>About the Project</h2>
The chatbot was developed using Python and Flask, leveraging a .yml dataset for training. 
When a user inputs a query in the chatbot GUI, the system first checks if the question exists in the SQLite database. If found, an automated response is generated from the database. If not, the chatbot searches the user's query in both the .yml dataset and a predefined dataset. The response is then displayed on the GUI. <br> <br>
On the website, users can explore the world-map API page to view global COVID-19 statistics, including current and recovered cases. The data, obtained from the graph_file Python library, is presented on a world map, with detailed information available by hovering over specific regions. The website also provides real time data of all the countries related to covid using APIs. The website also offers state/province-specific information, accessed through a search bar and displayed in graph format. Additional pages provide COVID advice, global research on the pandemic, vaccination details, and access to the chatbot. The site aims to provide comprehensive COVID-19 information and resources in an accessible manner.

<h2>Tech Stack Used</h2>
<h3>Front End</h3>
• Html <br>
• Css <br>
• Javascript <br>
• BootStrap <br>
<h3>Back End</h3>
• Python <br>
• Flask <br>
• Important Libraries – Graph_files, Chatterbot, Chatbot_corpus, numpy, request <br>
• Json <br>
