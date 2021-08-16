# lol-team-analyzer

A command line tool ran during champion select that provides information regarding teammates, displaying their preferred role and recent ranked match win percentages.

This program utilizes an external ML library (https://github.com/Canisback/roleML) to determine the preferred role of each teammate based on the roles they have assumed in recent ranked matches. Player data is retreived through the Riot Games Client API and Riot Games LoL API. As a result of these dependencies, any changes to the above may affect this program.

The intention of this project was to practice working with APIs.  
