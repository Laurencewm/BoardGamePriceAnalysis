# BoardGamePriceAnalysis
Using the data on the Boardgamegeek.com rankings, as well as data scraped from the web, multilayer perceptron and random forest models were applied to predict the prices of the boardgames. Unfortunately, both models concluded with mean absolute errors around ~£9. This is not what I had been hoping for. However, it became clear that whilst the data contained many features, it lacked some of the key information that would indicate the price of the boardgame. Specifically, the quality of game components, location and scale of manufacture. Many boardgames vary wildly in price simply due to production costs. If a game contains many high quality components, it is going to cost more, regardless of its rating or weight on Boardgame geek, or the mechanics employed. Thus, whilst this project would not be suitable for querying whether or not you are getting value for your money - it does a reasonable job at predicting the rough pricing of a game. 





The boardgame geek reviews data was collated by Jesse van Elteren (https://www.kaggle.com/jvanelteren/boardgamegeek-reviews). I do not own this data, it is owned by BoardGameGeek.

