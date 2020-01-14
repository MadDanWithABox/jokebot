## corny_joke
* joke: tell me a joke
  - utter_ask_joke_type
* joke: [corny](joke_type)
  - slot{"joke_type":"corny"}
  - action_corny

## inspiring_quote
* quote: can i have a quote
  - utter_ask_quote_type
* quote: [trump](quote_type) quote
  - slot{"quote_type":"trump"}
  - action_trump

## inspiring_quote filled
* quote: give me an [inspiring](quote_type) quote
  - slot{"quote_type":"inspiring"}
  - action_inspiring
