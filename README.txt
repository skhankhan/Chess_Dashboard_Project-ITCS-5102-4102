The purpose of this project is to provide visual tools for data analysis to those seeking to understand more about who is involved in the “Chess” social media scene. Chess is a game played around the world. For marketing purposes, community organization, and pure data science, it is important to understand where the hotspots for chess activity are.

For this code to work correctly with kibana/ElasticSearch follow these instructions:s

1. Make sure Kibana and ElasticSearch are installed and running
2. Open Kibana and copy paste the code from json_mapping_kibana .txt file into the Developer's Console
3. Execute the line with "PUT /chess_geocoord"
4. Run the chess_data-collect-script to collect data for kibana
5. Specify the location of index patterns "chess_geocoord" and "chess_non_geocoord" under management, 
	**make sure "Index contains time-based events" is unchecked
6. Import all json files for searches, dashboard, and visuals into Kibana under Management