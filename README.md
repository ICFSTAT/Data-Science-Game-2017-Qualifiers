# Data-Science-Game-2017-Qualifiers

This is one my best submissions - my best single model- in private and public leaderboard which gets an score of 0.67061 in private leaderboard and 0.67749 in public leaderboard which is enough to qualify for the finals. My best submission in the leaderboard is an ensemble of models similiar to this one but this model is the best single model in the leaderboard.

My approach was to work mainly with likelihood features and most of them had to depend strongly on the time the song was listened but I think the catch is that to calculate the likelihood if my sample is less than 20 in size, I set the value as missing. Also, to train the model I just considered the rows from flow mode because the test required predictions for flow mode which are music recomendations and the rows with values of not flow mode were not really recommendations of songs, the other rows were to generate more features about the behaviour of the user in not flow mode.


