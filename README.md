# Social Listener

Python project used to collect tweets and social-network data from Social's API

## Requirements

First of all create a Virtualenv

    virtualenv -p /usr/bin/python2.7 envSocial
    source envSocial/bin/activate

Install requirements:

    pip install -r requirements.txt

You need also:

    MongoDB up and running
    Twitter Developer Account 

Install front-end requirements:

    npm install

## How to Run

Create your own config file:

    cp config.ini.sample config.ini
    
Remember to edit the file with your settings.

In Development Mode:

    npm start (compile and run python server)
     
and in a second terminal window 

    npm run watch (watch on files)
    
In Production Mode use WSGI with Apache/NGINX (documentation will be provided soon..).

## API 

We support API! Go to:

    /api/v1
    
For now, we only support Twitter APIs:

    /api/v1/twitter
    
## Credits

Developed with <3 from TOP-IX Hackademy