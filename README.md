# Random

## Clean-up and export Skype chat history

### Description
Back in the day it was possible to save your Skype history by simply selecting everything in a conversation window and pasting it into an editor of choice. For a while that hasn't been possible. There used to be an awesome program that parsed the main.db file that contained local copies of history (skyperious). However Skype now stores everything in the cloud and their own parser doesn't parse a lot of Skype-specific tags so you end up with a mash of regular conversation text and long weird HTML tags that represent call / edit / quoting / file attachent, etc. history, which looks very bad.

Not set to develop anything complex I came up with my quick list of RegEx statements to help clean-up the chats into a readable format for saving using Skype's own JSON parser.
