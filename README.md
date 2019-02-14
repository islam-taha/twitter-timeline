# Twitter home timeline API
Twitter home timline script for fetching urls within tweets in your home timeline with a tiny description for each.

## requirements
- ruby version >= 2.6.0
- bundler version >= 2.0 (inline gemfile)
- Internet connection :)

## Preparation
- `cp .env.sample .env`
- Add your twitter API credentials in the .env file

## usage
- ./tweets_executer start_date end_date
- start_date & end_date should be in this format %Y-%M-%D (2019-02-14)
- start_date & end_date are optional args
