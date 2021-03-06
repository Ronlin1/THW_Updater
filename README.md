# THW Info Tabs (Updater)
The Hashnode Writeathon Python Module &amp; API CONNECTOR

This is a simple THW updater that I created for learning purposes during the challenge;

## Usage

Use one of the following APIs to test the different Hashtags

Web 3: https://hashnode.com/api/feed/tag/thw-web3

Web Apps: https://hashnode.com/api/feed/tag/thw-web-apps

Mobile Apps: https://hashnode.com/api/feed/tag/thw-mobile-apps 

Cloud Computing: https://hashnode.com/api/feed/tag/thw-cloud-computing

```
API_URLs = ['https://hashnode.com/api/feed/tag/thw-cloud-computing',
            'https://hashnode.com/api/feed/tag/thw-mobile-apps',
            'https://hashnode.com/api/feed/tag/thw-web3',
            'https://hashnode.com/api/feed/tag/thw-web-apps'
            
            ]
```

## ```code```

``` pip install thwAPI```

```
import thwAPI

URL = 'https://hashnode.com/api/feed/tag/thw-web3'
web_three = thwAPI(URL).count()

print(web_three)
```

Expected output;

```
......
There are currently 95 posts written!
....

```

The output depends at a time of running this;

Refer to Tests File for more examples;

Read Blog-Series here; https://blog.octachart.com/series/tabs-with-thw

Star this repo if you learnt something from my mini-series
