This project is a new interface for the BirdNET-Pi Project based on Streamlit

You should ad the following into your secrets.toml:

``` Console
flickr_api = "[optional]"
language = "de"

[connections.birds_db]
url = "sqlite:///../BirdNet-Pi/scripts/birds.db"
```
First you need to pull the repository
``` Console
git pull https://github.com/mazze84/BirdnetPI-Analyzer.git
```
You can run install.sh to create the environment.
After that you can start it with start.sh
