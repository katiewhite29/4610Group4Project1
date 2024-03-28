# 4610Group4Project1
This is a collaborative group project with a database for a Soccer club

## Team Name:
47114 Group 4

## Team Members:
1. Morgan Busbee [@morgan-busbee](https://github.com/Morgan-Busbee)
2. Corbin Gay [@corbinGay](https://github.com/CorbinGay)
3. Carson Harris [@clh15315](https://github.com/clh15315)
4. Ashley Seelochan [@as88578](https://github.com/as88578)
5. Hank Stocke [@hstocke1](https://github.com/hstocke1)
6. Katie White [@katieawhite29](https://github.com/katiewhite29)

## Problem Description:
The task for this project is to model and build a relational database as the owner of a soccer club. In the data model, the central entity is represented as Team which contains the attributes of all of the information for each of the teams that will be playing in matches at the soccer club. The Teams table will be connected with the information about the members on the team, the facilities, the individual matches, etc. We are interested in accurately modeling this data and their relationships, as well as generating sample data and understanding these entities and their attributes within the data. We will also be creating queries to help us understand the business insights and the operations throughout the soccer club. 

## Data Model:
Explanation of Data Model:

Our data model is based on a hypothetical soccer club composed of many complex relationships among the different entities of the club.

At the heart of AUSC are the teams, each embodying spirit, strategy, and sportsmanship. These teams engage in numerous matches throughout a season, illustrating a many-to-many relationship encapsulated within the entity known as matchSchedule. This associative entity is necessary for organizing the calendar of games, ensuring that each team has the opportunity to compete in multiple matches while facilitating the scheduling of matches between two teams. 

Each match is uniquely positioned within the boundary of a season, ensuring that the narrative of the league unfolds in a structured manner, culminating in climactic season finales that determine champions. Spatially, matches are anchored to specific facilities, which provide the stage for the game. This one-to-many relationship between venues and matches underscores the importance of place in the sport. 

The integrity and fairness of matches are upheld by referees, who navigate the complexities of the game with expertise. Recognizing the demanding nature of this role, AUSC employs a many-to-many relationship through the refSchedule entity, allowing referees to officiate multiple matches while enabling a single match to be overseen by multiple referees. This system ensures that matches are conducted fairly, with referees bringing varied perspectives and expertise to the game, enhancing the quality and fairness of the competition.

At the individual level, teams consist of players, each bringing unique skills and roles to their team. Players are supported by coaches, who provide strategic insight, training, and mentorship. This relationship is further enriched by the involvement of parents, who may have multiple children playing across different teams, creating a web of personal investment in the club's success. Training sessions are vital for team preparation, where strategies are honed, skills are developed, and bonds are strengthened. These sessions utilize various pieces of equipment, highlighting the material needs of teams and the importance of resources in their development.

AUSC's structure is rounded off by the leagues, which are composed of the myriad teams in competition. These leagues represent the broader organizational framework within which the drama of the soccer season unfolds. Members, through their financial contributions and fervent support, breathe life into the games. By paying a fee, they not only gain access to witnessing the matches but also contribute to the financial sustenance of the league, enabling it to thrive and grow.



<img width="576" alt="Screenshot 2024-03-27 at 8 33 54 PM" src="https://github.com/clh15315/group4project1/assets/150160152/da3db633-1876-4ab5-a25b-c73ab5eb8981">



## Data Dictionary:
### Table: player
<img width="507" alt="Screenshot 2024-03-27 at 9 47 10 PM" src="https://github.com/clh15315/group4project1/assets/40582321/ae1f8fba-f4d9-44e7-af73-4916838fe0c6">

### Table: team
<img width="508" alt="Screenshot 2024-03-27 at 9 49 26 PM" src="https://github.com/clh15315/group4project1/assets/40582321/65efa00b-f673-4e46-8894-01a75620381a">

### Table: coach
<img width="505" alt="Screenshot 2024-03-27 at 9 49 47 PM" src="https://github.com/clh15315/group4project1/assets/40582321/71bcfe8c-e33a-4764-8c74-a89b15bdba17">

### Table: league
<img width="555" alt="Screenshot 2024-03-27 at 3 41 12 PM" src="https://github.com/clh15315/group4project1/assets/40582321/6a783ab9-5474-4464-8cef-3209739fa9b6">

### Table: matches
<img width="533" alt="Screenshot 2024-03-27 at 9 47 59 PM" src="https://github.com/clh15315/group4project1/assets/40582321/acb22993-7634-4611-9ac5-cefce050983d">

### Table: matchSchedule
<img width="536" alt="Screenshot 2024-03-27 at 9 50 15 PM" src="https://github.com/clh15315/group4project1/assets/40582321/6dd66aae-6b55-4908-8d58-1722fbf38abd">

### Table: trainingSessions
<img width="535" alt="Screenshot 2024-03-27 at 9 50 36 PM" src="https://github.com/clh15315/group4project1/assets/40582321/6fab8c62-8537-406b-bc11-d73284fc2015">

### Table: season
<img width="508" alt="Screenshot 2024-03-27 at 9 48 42 PM" src="https://github.com/clh15315/group4project1/assets/40582321/6717d10b-9b3a-43e6-a541-ed326050dea5">

### Table: facilities
<img width="509" alt="Screenshot 2024-03-27 at 9 51 13 PM" src="https://github.com/clh15315/group4project1/assets/40582321/9d46bd35-10ac-461d-a79e-a7114e24b08f">

### Table: equipment
<img width="536" alt="Screenshot 2024-03-27 at 9 51 37 PM" src="https://github.com/clh15315/group4project1/assets/40582321/38e2e3fe-5363-4e5f-a240-d3b3b0a4b56a">

### Table: parent
<img width="570" alt="Screenshot 2024-03-27 at 3 43 39 PM" src="https://github.com/clh15315/group4project1/assets/40582321/fde4bf88-080c-4d8c-801e-762e27f9c7af">

### Table: membership
<img width="534" alt="Screenshot 2024-03-27 at 9 52 03 PM" src="https://github.com/clh15315/group4project1/assets/40582321/85dcc2b9-6aa7-4ebd-8c7f-5792e2697a93">

### Table: refs
<img width="538" alt="Screenshot 2024-03-27 at 9 52 22 PM" src="https://github.com/clh15315/group4project1/assets/40582321/85b75e0b-389b-4169-a0c3-22463fe16419">

### Table: refSchedule
<img width="536" alt="Screenshot 2024-03-27 at 9 52 39 PM" src="https://github.com/clh15315/group4project1/assets/40582321/58c33cc1-2a14-4c32-9cc0-c545f53c5fb6">



## Queries:
<img width="675" alt="Screenshot 2024-03-27 at 10 24 49 PM" src="https://github.com/clh15315/group4project1/assets/150160152/e9080e58-0f4d-4a28-8721-93663ce1bd7b">

### Query 1:
Write a query to list the name, contact information, and address of all parents whose children are on the mighty falcons team.

<img width="631" alt="Screenshot 2024-03-27 at 8 46 44 PM" src="https://github.com/clh15315/group4project1/assets/40582321/2c567a1a-ba09-40c8-bda9-808f4f08698d">

Query 1 gives a list of the names of the parents, their contact information and their address for the team "Mighty Falcons." This helps the soccer club to manage who each of the parents are for this specific team. They are able to easily access this information in case of an emergency or just to be able to contact the parents when certain information needs to be presented out.

### Query 2: 
Write a query to count how many matches each ref has refereed

<img width="628" alt="Screenshot 2024-03-27 at 8 47 14 PM" src="https://github.com/clh15315/group4project1/assets/40582321/842e6d08-c45d-4046-80f2-c9079a97c318">

Query 2 gives a list of all of the referees and how many matches they have refereed at. This information is useful to the soccer club so that they know how many matches the referees have been at and which referees have been the biggest help to their organization.

### Query 3: 
Write a query to list out all players, and the name of their team, and their coaches names whose coaches have a bachelor's degree

<img width="533" alt="Screenshot 2024-03-27 at 9 40 13 PM" src="https://github.com/clh15315/group4project1/assets/40582321/e2806cf1-8b9a-4382-b6e6-5adc30c2ee7e">

Query 3 lists out the names of the players, their team name, and the name of their coaches who have a bachelors degree. This is extremely useful to the soccer club in order to organize their clubs better and have a better understanding of which team the player is on and which coach is in charge of them. The bachelors degree part of the query gives an easy access to the coaches who have been through college to help the parents and the soccer club staff know who is in charge of what player.

### Query 4: 
Write a query to find the total number of players in each age group

<img width="626" alt="Screenshot 2024-03-27 at 8 50 12 PM" src="https://github.com/clh15315/group4project1/assets/40582321/c73fb0e8-9833-477b-93fd-dce1b7e546bc">

Query 4 gives out a list of all of the different age groups within the club and how many players are in each of those age groups. This can be helpful for 2 different parts of the club. For one part, it will be very helpful to be able to keep track of that many players if you are doing certain events organized by age group and you will know exactly how many people are in each of the age groups. The second part of the club that this information will be useful for is the marketing team. If they are trying to increase the amount of players for a certain age group, or the age group that has the least amount of players, they will easily be able to see which age groups they need to bring more players into the club for.

### Query 5: 
Write a query to list the names of the teams who have never won a championship

<img width="532" alt="Screenshot 2024-03-27 at 9 27 49 PM" src="https://github.com/clh15315/group4project1/assets/40582321/cda3f36e-16da-4ad0-af92-5269e825341d">


Query 5 gives a list of the team names who have never won a championship. This gives the club an overview of the top teams and all of the teams who have not been winning championships. This can give them the information of where they need to put more time or effort into making that team more successful in the future.

### Query 6: 
Write a query to list out the team names with less than 15 players

<img width="534" alt="Screenshot 2024-03-27 at 9 56 20 PM" src="https://github.com/clh15315/group4project1/assets/40582321/1ab8be90-58b2-438b-87b6-d9920bca0dd6">

Query 6 shows a list of all of the teams who have less than 15 players on that team. The soccer club can use this information in order to figure out if some teams need to have more players or some have a lot more than others. This will give them the information in order to distribute the teams in an even and fair way throughout the club so that no team has too much advantage compared to another.

### Query 7: 
Write a query to count the number of poor goalkeeper gloves

<img width="530" alt="Screenshot 2024-03-27 at 9 19 06 PM" src="https://github.com/clh15315/group4project1/assets/40582321/d5a9c1a8-ce6b-4880-b692-edf38c3dba99">

Query 7 gives a count for the number of goalkeeper gloves that are in poor condition. This shows the soccer club the amount of equipment that could use an improvement in for the goalies. If there are a lot of poor goalkeeper gloves, the goalkeepers will be needing new gloves and the soccer club will be able to know this and help them quickly.

### Query 8: 
Write a query to list the names of parents who have two male players
<img width="532" alt="Screenshot 2024-03-27 at 10 21 06 PM" src="https://github.com/clh15315/group4project1/assets/40582321/dca3179c-6d20-4206-8be6-31f0ce997e28">

Query 8 lists out the names of parents who have 2 male players listed under their names. This gives the soccer club information about which parents are in charge of 2 players within the club and can be easier for the leaders of the club to give out information to one individual parent.

### Query 9:
Write a query to list the names of refs and the percentage of matches they have refereed at "Mauv" facility

<img width="534" alt="Screenshot 2024-03-27 at 9 45 41 PM" src="https://github.com/clh15315/group4project1/assets/40582321/9808559d-3b9b-4284-9911-80c83a4353b8">

Query 9 shows a list of the referee names and the percentage of matches they have refereed at the "Mauv" facility. This gives the soccer club a way to figure out how often a single referee has spent at the "Mauv" facility in comparison to the other facilities. This can give the soccer club information about if some referees are spending too much time there or too little time and can help them to distribute them to different facilities throughout the club.

### Query 10:
Write a query to find the total fee cost of membership 9-11 and 12-14 age group

<img width="502" alt="Screenshot 2024-03-27 at 8 53 16 PM" src="https://github.com/clh15315/group4project1/assets/40582321/14b64f6d-f75b-46d9-9385-208a07f6eca8">

Query 10 gives a total fee cost for the membership of the 9-11 age group and the 12-14 age group. This helps to give the soccer club an easier way to figure out how much money is coming in from each of the age groups so that they are able to distribute that money throughout the age group evenly. This also helps to give the parents an easier way to estimate how much they will be paying for their child to play soccer.


## Database Information: 
Name of the database: ns_Sp24_47114_Group4

Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: CALL TP_Q1(); - CALL TP_Q10();
