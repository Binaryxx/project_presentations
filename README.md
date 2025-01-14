# project_presentations  
A repository to store copies of presentations for the personal projects completed. Centralized location to refer recruiters and employers to provide an overview in coding experience. The README file will reference the projects' repository names as well as a high level description of the project.  
<br>
  
**Project List:**  
<br>
  
<ins>SF6 Rank Distribution Explorer: Rank Web Scraper and Visualizer  

*The Jupyter Notebook can be found in Binaryxx/sf6-rank_distribution-explorer (https://github.com/Binaryxx/sf6-rank-distribution-explorer)*  
- Web scrapes the official Street Fighter 6 website for data on the player count for each rank; Visualizes the trends and patterns recorded  
  * Provide up-to-date summaries of the competittive scene in Street Fighter 6  
<br>
    
<ins>Valorant Meta Analysis Series  

WORK IN PROGRESS: Needs code revisions for professional presentation and readability; A draft of the basic information of the project provided; The project is fully functional    
*The Jupyter Notebook can be found in Binaryxx/valorant-project (https://github.com/Binaryxx/valorant-project)*  
- Use the unofficial Valorant API created by Henrik-3 to collect the data about agent pick rate, agent win rate, player rank, and player performance (win rate, headshot rate, utility usage, Kill/Death/Assist Ratio)   
  * Collect the necessary data to complete project ideas  
- Create a Python script to collect and store match information from specified players  
  * The API only provides the 5 most recent match information; for visualization, a larger sample size is required.  
  * Running this script modifies a file with the cumulated ranked matches collected in the past, updating the file with new matches when executed  
- Create an interactive dashboard which allows users to specify parameters such as the Rank Range, Map, and Playable Agent Pool to present the Pick Rate and Win Rate of each agent  
  * Identify the "best" agents to pick given a certain map and rank range  
- Identify correlation between player performance and rank using machine learning algorithms for correlation    
  * Which factors, if any, are significantly correlated to a higher rank, thus a higher level of skill
  
- Web scrape a Valorant tournament tracker website to collect data from professional players  
  * Provides a different population to identify the prevailing strategy with skill level being a non factor  
- Create a script which provides the most prevalent team composition in each map  
  * Presents the most common combination of agents selected per map by professional players, thus hinting the most effective strategy in playing the map (each agent has a set of skills which serves a certain purpose)  
- Create a script which identifies the most prevalent "controller" agent in each map  
  * Learn the "controller" agent to pick for each map

<ins>Winning the Space Race through Data Science  
  
DISCLAIMER: This project was completed as part of the Coursera Certification Course: IBM Data Science Professional
*The Jupyter Notebook can be found in Binaryxx/coursera-capstone-project (https://github.com/Binaryxx/coursera-capstone-project)*  
- Determines whether SpaceX will be able to successfully land and reuse the engine used for a rocket launch; A successful reuse allows the company to enjoy savings from not having to rebuild a rocket and pass on the savings as competitively low contract pricings
  * Used Logistic Regression, SVM, KNN, and Decision Trees to classify whether a launch will have a successful rocket landing for retrieval based on characteristics such as rocket mass, launch location, rocket orbit trajectory
  * Collected data from SpaceX's API and through webscraping, wrangled data, performed EDA, created interactive visualizations
