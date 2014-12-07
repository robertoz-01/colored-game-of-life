Implementation of Game of life ( http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life ) with some extensions:
* State for a cell can be one of [RED, GREEN, BLUE, DEAD] instead of only [ALIVE, DEAD]
* Any cell can change its state not according with GoL rules with a given (very low) probability
* A cell, born according with GoF rules, must have the color state that is the most present in the neighbourhood
Requirements:
* Ruby
* Chingu gem and its requirements (gem install chingu)
