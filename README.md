# President Trump's Tweets and TV

*An analysis of President Trump's tweets and television news chyrons.*


## Description

This is an analysis of the President's tweets and how they are linked to the news of the day.  We'll utilize some natural language processing (NLP) in Python to determine if there is a  relationship between the news of the day and the President's twitter activity.

## Data

The chyron data is provided by the [Third Eye Project](https://archive.org/details/third-eye).  We'll access the tweets on [Twitter](https://www.twitter.com/) via the [Tweepy](https://www.tweepy.org/) library.


## Instructions

#### Environment

To get started initialize the python environment with the required libraries you can run:

```bash
$ make requirements
```

#### Setup

You'll need to set some environment variables for Twitter API access (we're using [python-dotenv](https://github.com/theskumar/python-dotenv) library for that), you'll also need a Twitter account and API key.  You can setup a new app on Twitter via the [Apps Management](https://apps.twitter.com/) when you're logged into your Twitter account.  You can set the keys interactively using this command:

```bash
$ make setup
```


## License

This project's code is Copyright (C) 2018 Douglas Daly and licensed under the MIT license - details can be found in the `LICENSE` file.  All other trademarks and copyrights are the property of their respective owners.

