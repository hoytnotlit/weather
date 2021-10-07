Notes/issues/etc.

My Rasa model failed with the user utterance "what is the weather in London UK"
-> UK was not recognised as a country, though this works as expected with tdm

I got this warning when running the last test:
UserWarning: Semantic Warning: Incoming entity 'city_tallinn' has expected sort 'city' but got 'country'
and I dont know why, the test however passes and the request seems to be correct
