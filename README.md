# Cricket Data Analytics ![Cricket_Logo](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/c76b0a7f-c330-4ec6-84b7-c641c9a9b3a9)

# Intro and Objective:-
The Cricket Data Analytics🏏 project is made on T-20 Cricket World Cup Data(2022). I have used Power BI for making the Dashboards. We can easily analyse the data of the matches played in the world cup. We can also pick the best playing 11
as per the choice of subject matter expert.
>Note:-To interact with the dashboard you can download the complete .pbix file from the repository and download it locally to your desktop.

# Steps involved in the project:
>>📝 Requirement Gathering:-

>>🌐Data Collection using the web scraping using the ESPN cricinfo website plz click the below url to get redirected to the website for more information:-

 URL:- https://www.espncricinfo.com/
 ![csv_logo](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/735ad1f6-46d6-44bb-8367-f468d00aac56)

>>Brief description of the datasets used:-
    1>dim_match_summary:-It contains information about the names of the teams between whom the matches was played,
                         the winner of the team and margin of runs the team won, ground on which the match was played
                         and id of the match in which the match was played.

    2>dim_players:-It contains the information about each player his name his team name batting style,bowling style
                   description about the player.

    3>fact_batting_summary:-This contains the information about each match,batsman 
                            name,balls,boundaries,sixes,strike/rate,
                            match_id.
    4>fact_bowling_summary:-This contains the information about the bowlers name,no of overs bowled,no of maidens bowled,no of runs scored,no of wickets taken,economy rate of the bowler,no of boundaries,no of sixes,no of wides,no of noballs,match_id(the unique id of each match)

   >JSON_files_used:-
   >t20_wc_player_info

   >t20_wc_match_results

   >t20_wc_bowling_summary

   >t20_wc_batting_summary

>>🧹 Data Cleaning and Preprocessing in pandas library using the jupyter notebook.

>>🪄  Data transformation using power query(self service etl tool of power bi) inside the power bi desktop.

>>⚒️Data Modelling and building parameters,calculated columns and measures in power bi using the DAX formuales for
     effective visualisation.

>>📊Building the interactive dashboard in power bi to take analytical decisions.

# Screenshots of the dashboard:-
![image](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/bcfdf0e0-95a0-4883-829f-8afd8455d081)

![image](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/5bda263c-6da4-4446-b86d-27f34350ae83)

![image](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/4056641c-5501-4c1b-9850-dda171f516de)

![image](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/5f86225b-412d-4c3c-84d3-f9a402936778)

![image](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/7dc57872-a6cf-45cf-8549-128ccd95a26e)

![image](https://github.com/Vkumar-sys/Industrial_Project_2-IPL_SPORTS_ANALYTICS-/assets/66684700/0e3f0f6e-dc77-470e-a493-82c3286876ae)

















