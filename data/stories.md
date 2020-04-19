## Intropath
* greet
  - utter_greet
  
## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## search story path 1
* greet
  - utter_greet
* bot_challenge
  - utter_iamabot
* corona_intro
  - utter_corona_intro
* corona_spread
  - utter_corona_spread
* corona_food_fact
  - utter_corona_food_fact
* corona_social_distancing
  - utter_corona_social_distancing
* corona_sick_and_isolation
  - utter_corona_sick_and_isolation
* corona_protect
  - utter_corona_protect
* corona_warm_weather
  - utter_corona_warm_weather
* corona_high_risk
  - utter_corona_high_risk
* search_provider{"facility_type":"hospital","location":"San Francisco"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye
  
## search story path 2:without location
* greet
  - utter_greet
* corona_intro
  - utter_corona_intro
* corona_spread
  - utter_corona_spread
* corona_food_fact
  - utter_corona_food_fact
* search_provider{"facility_type":"hospital"}
  - utter_ask_location
* inform_location{"location":"Austin"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye
  
## search story path 3: direct search & with location
* greet
  - utter_greet
* search_provider{"facility_type":"hospital","location":"California"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye
  
## search story path 4:direct search & without location
* greet
  - utter_greet
* search_provider{"facility_type":"hospital"}
  - utter_ask_location
* inform_location{"location":"Austin"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye
  
## search story path 5:Only questions
* greet
  - utter_greet
* bot_challenge
  - utter_iamabot
* corona_intro
  - utter_corona_intro
* corona_spread
  - utter_corona_spread
* corona_food_fact
  - utter_corona_food_fact
* corona_social_distancing
  - utter_corona_social_distancing
* corona_sick_and_isolation
  - utter_corona_sick_and_isolation
* corona_protect
  - utter_corona_protect
* corona_warm_weather
  - utter_corona_warm_weather
* corona_high_risk
  - utter_corona_high_risk
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye
  
## Search Provider with location
* search_provider{"facility_type":"hospital","location":"California"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye

## Search Provider without location
* greet
  - utter_greet
* corona_intro
  - utter_corona_intro
* search_provider{"facility_type":"hospital"}
  - utter_ask_location
* inform_location{"location":"Austin"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye
  
## Only search
* greet
  - utter_greet
* search_provider{"facility_type":"hospital"}
  - utter_ask_location
* inform_location{"location":"Austin"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
* goodbye
  - utter_goodbye
