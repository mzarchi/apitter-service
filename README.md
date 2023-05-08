# Apitter Service

Base url: https://apitter.ir <br>
Free token access (v1-limit): ‍‍‍```4e799b16face1a59c264d8de2e78a0e12b23a876```

## API Methods (v1.0)
### User:
- <b>/api/v1/ ```ACCESS-TOKEN``` /user/ ```USER-ID``` </b>(GET)<br>
- <b>/api/v1/ ```ACCESS-TOKEN``` /user/ ```SCREEN-NAME``` </b>(GET)<br>
Each user in Twitter has a ```user id``` <i>(for example the user id of [jack](https://twitter.com/jack) in <b>12</b>)</i> that is not determined and chosen by the user, and this ID cannot be edited. And by using this method and sending this value, view the details of the user's account. You can also do the same with ```screen name```, which is <b>@username</b>
<br><br>
API output: <br><sub>https://apitter.ir/api/v1/4e799b16face1a59c264d8de2e78a0e12b23a876/user/mhzarchi</sub><br>

    ```json
    {
        "code": 200,
        "data": {
            "user_id": 970599654097219584,
            "screen_name": "mhzarchi",
            "name": "Mohammad Zarchi",
            "bio": "Interested in python's programming \u2615\ufe0f",
            "url": "t.me/MohammadZarchi",
            "location": "Iran, Mashhad",
            "friends_count": 121,
            "followers_count": 389,
            "created_at": 1520243965.0,
            "can_media_tag": true,
            "can_direct_message": true,
            "listed_count": 0,
            "media_count": 33,
            "avatar_url": "https://pbs.twimg.com/profile_images/1637013976969015297/0vaARzsm.jpg",
            "tweet_count": 835,
            "fav_count": 3124,
            "blue_verified": false,
            "birthdate": {
                "year": 0,
                "month": 0,
                "day": 0
            }
        }
    }
    ```