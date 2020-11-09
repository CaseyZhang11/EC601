# Phrase 1

## 1(a) Twitter API

### Description:

Exploring Twitter API. Using Stream API to stream live tweet with keyword ”Donald Trump” and “Walter reed”

### Test result: 

(partial)

{"created_at":"Mon Oct 05 02:41:46 +0000 2020","id":1312946048696950786,"id_str":"1312946048696950786","text":"RT @charliekirk11: Donald Trump, diagnosed with the China Virus, STILL had more public appearances today than Joe Biden.","source":"\u003ca href=\"http:\/\/twitter.com\/download\/iphone\" rel=\"nofollow\"\u003eTwitter for iPhone\u003c\/a\u003e","truncated":false,"in_reply_to_status_id":null,"in_reply_to_status_id_str":null,"in_reply_to_user_id":null,"in_reply_to_user_id_str":null,"in_reply_to_screen_name":null,"user":{"id":1202273618975047682,"id_str":"1202273618975047682","name":"Lawrence Dawson","screen_name":"Lawrenc32250953","location":null,"url":"http:\/\/awake1-africa.org","description":null,"translator_type":"none","protected":false,"verified":false,"followers_count":66,"friends_count":664,"listed_count":0,"favourites_count":466,"statuses_count":553,"created_at":"Wed Dec 04 17:09:50 +0000 

### Extracted Tweets:


"RT @charliekirk11: Donald Trump, diagnosed with the China Virus, STILL had more public appearances today than Joe Biden."

"RT @C_3C_3: Want some truth?\n\nDonald Trump sacrificed himself and his family for America.\n\nJoe Biden sacrificed America for himself and his\u2026"
"#UnidosContraTrump"

"RT @KelemenCari: I have relatives in the hospitality\/hotel industry. President Trump is the Ultimate Host. He enjoys making sure people are\u2026"

"RT @AnnaKrukCorbin: When my 19 month old son spent 10 days in the PICU at Johns Hopkins in 2009, he shared a room with three other children\u2026"

"RT @BreitbartNews: President Donald Trump now leads Democratic presidential candidate Joe Biden in the national popular vote by one point,\u2026”

RT @BWJones: The more I think about it, the more this makes me sad.\n\nIt is absolutely pathetic that the *image* of strength of competence i\u2026"

## 1(b) GoogleNLP

### Description:

Building Sentiment analysis model using GoogleNLP library.

### Text result:

`Text1 : “I am sad today because I had a lot of homework”`

The text entered should be predicted as a negative emotion since keywork “sad”, “a lot of homework”

Result: the test shows a negative score of -0.8.  It is a large negative socre which shows it is a negative emotion. 

`Text2: “I want to go to the beach.”`

The text entered should be neutral since it contains no emotional words. 

Result: the test shows a score of 0.2 which shows no indication for positive or negative emotion. 

`Text3: “The moon is beautiful.”`

The text contains positive emotion word” beautiful.”

Result. Test score 0.89 which is high positive emotion. 

`Text4: “When do you want to eat”`

The text shows no indication of emotion. 

Result: test score -0.1. Negative score. Kind of makes no sense since it is a question. 

`Text5: “I have a job offer”`

The text shows no indication of emotion. 

Result: test score 0. 

`Text6: “I want to cook steak for dinner”`

The text shows no indication of emotion. 

Result: test score 0.2. 

# Phrase 2

`MVP`: 

extracting  emotion trend of tweets of a given time.

`User Story`: 

Company or researcher can extract the emotion trend of a certain event. For example, user can extract positive emotion from live tweets on a national holiday. User could extract negative emotion from live tweets on a disaster.

# Unit Test

## Project 4: 

### Test for Twitter API.

I put wrong Twitter Credentials. The error code I receive is ‘401’. 

`401 Unauthorized`

A 401 status code means that there was a problem authenticating your request, such as an invalid consumer key or secret.
I put the wrong Twitter API name. The error is name “” is not defined. 

### Test for Google NLP. 

Test 1: 

Temoraliy stop the service of google NLP account.

The error code is 403. 

403	PERMISSION_DENIED	Client does not have sufficient permission. This can happen because the OAuth token does not have the right scopes, the client doesn't have permission, or the API has not been enabled for the client project.


