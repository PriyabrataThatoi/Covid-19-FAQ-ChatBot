## Intropath
* greet
  - utter_greet
  
## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## what is corona path
* corona_intro
  - utter_corona_intro

## how does corona spread path
* corona_spread
  - utter_corona_spread

## corona food path
* corona_food_fact
  - utter_corona_food_fact
  
## corona social distancing path
* corona_social_distancing
  - utter_corona_social_distancing
  
## corona sick and isolation path
* corona_sick_and_isolation
  - utter_corona_sick_and_isolation
  
## corona protection path
* corona_protect
  - utter_corona_protect
  
## corona warm weather path
* corona_warm_weather
  - utter_corona_warm_weather

## corona high risk path
* corona_high_risk
  - utter_corona_high_risk
  
## search testing center with location path
* greet
  - utter_greet
* search_provider{"facility_type":"hospital","location":"San Francisco"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
  
## search testing center without location path
* greet
  - utter_greet
* search_provider{"facility_type":"hospital"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* thanks
  - utter_noworries
  
   