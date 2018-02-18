
### Base URL

- https://gd2.line.naver.jp/mh/api
- https://gd2.line.naver.jp/mh/
- https://{$country-server}.line.naver.jp/mh/api
  
  
  
### headersTemplate

↓ You must need ↓
![headersTemplate](https://i.imgur.com/dtiKuyU.png "headersTemplate")
  
  
"X-Line-Carrier" → I don't know. ex)__51089, 1-0__  
"X-Timeline-WebVersion" → ex)__1.4.2__  
"X-Line-AcceptLanguage" → ex)__en__  



# Cheat sheets

* * *
### POST /api/v39/post/create.json
  
#### GET PARAMS
homeId = {$your_mid}  
sourceType = 'TIMELINE'

#### POST PARAMS
    {'postInfo': {'readPermission': {'type': 'ALL'}}, 'sourceType': 'TIMELINE', 'contents': {'text': text}}
    
readPermission->type = __ALL__ or __FRIEND__

