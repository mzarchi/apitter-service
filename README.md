# Apitter Service

Base url: https://apitter.ir/<br>
Sample: `https://apitter.ir/api/v1/ACCESS-TOKEN/method/params/`
<br>
Free access token (v1-limit): `4e799b16face1a59c264d8de2e78a0e12b23a876`
<br><br>

# API Methods (v1.0)

## User:
* <b>/api/v1/ ```ACCESS-TOKEN``` /user/ ```USER-ID``` </b>(GET)
* <b>/api/v1/ ```ACCESS-TOKEN``` /user/ ```SCREEN-NAME``` </b>(GET)<br><br>
Each user in Twitter has a user id <i>(for example the user id of [jack](https://twitter.com/jack) in <b>12</b>)</i> that is not determined and chosen by the user, and this ID cannot be edited. And by using this method and sending this value, view the details of the user's account. You can also do the same with screen name, which is <b>@username</b>
<br><br>
API output: [/result/user.json](./result/user.json) <br><br><br>


## Tweet & Replies:
* <b>/api/v1/ ```ACCESS-TOKEN``` /user/ ```USER-ID``` /replies/ </b>(GET)
<br><br>
API output: [/result/replies.json](./result/replies.json)
<br><br><br>


# ToDo
## Apitter (v1)
* [x] Get twitter's user data
* [ ] Get user's tweets data
* [ ] Get twitter's user tweets
* [x] Get twitter's user tweets and replies
* [ ] Get twitter's user likes
* [ ] Get tweets with special keywords
* [ ] Get tweets with special date-time