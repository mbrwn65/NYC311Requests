# Interactive Map of NYC's 311 Requests for 2023
### [Tableau Visualization](https://public.tableau.com/views/NYC311Requests/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [Data Source](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data)
______________________________________________________
## Data Visualization:
<img width="1432" alt="Screenshot 2024-05-18 at 4 02 54 PM" src="https://github.com/mbrwn65/NYC311Requests/assets/117549863/dab4be28-9019-4165-ab68-8fc220143eea">

I created an interactive visualization of NYC's 311 Complaints using Python to organize and clean the data and Tableau to visualize it. At the top of this README is the Tableau link to the interactive visualization where you can filter by complaint type and hover over each district for exact complaint numbers & median response times.

The Jupyter Notebook contains the Python code used to filter and organize the complaints from the 2023 311 complaint dataset. It narrows down the complaints to only the 50 most frequent, creates hours as a column from start and closing dates, and changes the community board column so that it can be joined with the spatial data used for the map in Tableau.

*THIS PROJECT IS ONGOING AND WILL BE UPDATED AS MORE FEATURES ARE FINISHED*
