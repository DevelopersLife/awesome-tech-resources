# Awesome Tech Resources

**A curated list of awesome resources for developers!**

## Awesome Tech Communities
The communities.json file contains **a list of communities** in alphabetical order.
The idea behind it is to map online and offline communities in order to allow all interested people to find them easily!  

Any suggestions, improvements or feedback are welcome! :)  
  
If you know any unlisted communities, please add them by doing a PR, below is the detail of how to add them:

```
{
    "name": "community name",
    "description": "community description",
    "logo_file": "community_logo.png",
    "homepage_url": "community url (can be a social network/meetup/youtube/etc url)",
    "place": "online or city, country",
    "primary_language": "community primary language",
    "topics": [
        "topic 1",
        "topic 2",
        "topic 3"
    ],
    "extra": {
        "twitter_url": "twitter url if it exists",
        "facebook_url": "facebook url if it exists",
        "blog_url": "blog url if it exists",
        "chat_url": "chat url if it exists",
        "youtube_url": "youtube url if it exists",
        "mailing_list_url": "mailing list url if it exists",
        "meetup_url": "meetup url if it exists",
        "eventbrite_url": "eventbrite url if it exists",
        "other": [{
            "name": "other link name",
            "description": "other link description",
            "url": "other link url"
        }]
    }
}
```
Field description:
* **name (mandatory)**: the community name
* **description (mandatory)**: the community description (you can write the description in the main language of the community)
* **logo_file (mandatory)**: the logo filename (you will have to upload the community logo in the logos folder with a size of at least 256x256, in square format)
* **homepage_url (mandatory)**: the main url of the community
* **place (mandatory)**: the place where your community congregates most often. It can be for example "online" or "Milan, Italy"
* **primary_language (mandatory)**: the primary language of your community
* **topics (mandatory)**: a list of keywords representing your community topics (maximum 3)
* **extra**: contains a list of other addresses you can add. If you don't find a suitable url for you you can use other which contains:
  * **name**: the extra channel name, for example "Telegram channel"
  * **description**: a description of the channel, for example "an additional channel where you can talk exclusively about HTML"
  * **url**: the url to reach your extra channel

**Some things to know:**
* excluding mandatory fields, you can omit any optional fields;
* each PR must contain one and only one community;
* you must necessarily upload a logo in the logos folder when you add a new community to the list;


**Generally all communities that talk about technology, programming and technical or technological sectors freely accessible to anyone are accepted** (paid, subscription or reserved communities are therefore excluded).
In any case, **violent communities and/or communities that do not respect the most basic rights of free coexistence between people are not allowed**.
