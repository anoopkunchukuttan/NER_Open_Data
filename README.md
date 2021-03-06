# a-mma_NER_Open_Data
> This repo contains timely updated NER tagged data collected through a-mma NER data collection programme. The online web interface is located [here](http://amma-ner-frontend.herokuapp.com/).

## Update [3 July 2018]
* added NER data collected during last month in news category.

---



Hey curious explorer 👋, welcome.

We are happy to present to you this **NER Open Data repository** on the behalf of 🎈🎆 each unknown generous contributor 🍾🎉.  Feel free to use this in your pet projects, geeky experiments, futuristic products or anywhere your creative mind tells you to. We feel very proud of making our first baby step 👶 to push language barriers together with the public. Let's make sure that no one gets discriminated in the connected world because of their language, at least in India 🇮🇳🇮🇳. And let everyone build tools for anyone else across boundaries.

## how to use this data? (data format)

All the information collected within a span of time is formatted as a single JSON object. All tagged information belongs to `data` field, which is a list. Each element of that list corresponds to each article in some language. A single article is another object having fields `text` and `entities` where `text` field contains the original raw article text and `entities` field contains a list of tagged entities in that article. This `entities` field is also another object having fields `start`, `value`, `end`, `entity`. Below snippet will give you a snapshot of the entire JSON object.
```
{
  "n_docs": "- total number of documentss tagged so far",
  "n_entities": "- total number of entities tagged so far",
  "data":[
            {
              "text":"- article original raw text",
              "entities":[
                            {
                              "start":"- entity word starting position within text",
                              "end":"- entity word ending position within text",
                              "value":"- actual entity value",
                              "entity":"- entity type specified"
                            },
                           {...},
                           {...}
                        ]
            },
            {...},
            {...}
        ]
}
```

## Are you are a developer, researcher or hobbyist? 💻🔬🏏
We encourage you to make use of this data and let's see what we could give in return.

## Are you an Entrepreneur? 🏢
We have got a great idea and awesome tools, but no data? Don't let data unavailability limit your imagination. Let's pave infrastructure for the future today.

## Are you a student? 💯🎓
You have got a lot of time to learn new stuff and experiment with it. Give this a try and let's see where this leads you. Ask questions on that journey, and we're here to help you smash any roadblocks 🥊🥊.

## Are you a content creator?
Contribute for the greater good and make sense of your content data (generate structured data).

## And finally.., We need your help as well. 🆘
To keep above-mentioned things alive, we need to fuel it. Here's how to do it:
- the first and foremost thing to do is giving contributions to **Open Data Collection**. Just [go here☝️](http://amma-ner-frontend.herokuapp.com/) and input some data whenever you get some time.
- please clarify what a-mma's mission and activities are by reading [this documentation🔖](https://github.com/a-mma/a-mma-documentation).  This will give you a broad view of what is going on and might encourage you to keep contributing to a-mma. 
- send your valuable suggestions and ideas to 📧 humans@a-mma.in

#### Disclaimer
> a-mma doesn't own any rights to the data being uploaded by the public. If you are a content creator and you see your content here which violates any rights, please let us know at humans@a-mma.in to take that content down.


thanks for your valuable time. Good day! 👏👏👏
