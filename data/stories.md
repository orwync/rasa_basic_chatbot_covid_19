## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## what is cororna
* corona_intro
  - utter_corona_intro

## how dose corona spread
* corona_spread
  - utter_corona_spread

## corona food spread
* corona_food_spread
  - utter_corona_food_spread

## warm weather spread
* warm_weather
  - utter_warm_weather

## who is at high risk
* high_risk
  - utter_high_risk
