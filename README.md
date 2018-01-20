# Test Firebase Cloud Messaging

<img src="ScreenRecord.gif" alt="" align="center">

## Send notification from HTTP client

```
POST /fcm/send HTTP/1.1
Host: fcm.googleapis.com
Authorization: key=AAAAJyW0l_Q:APA91bHLP16NQNvy-57HrmeGrTnZGIUsXA_yjRSzsW7geQNvcE695ib_ewaOJlErDwrZnaq62kvQS8kxsiLLfKqoxn5B1eUWVsDCg7yuDiX-WP1xGOglTZoYgLkBR10uYNHcp7UNeBaL
Content-Type: application/json

{
  "notification": {
    "title": "Bubble Nebula",
    "body": "It's found today at 21:00",
    "icon": "https://diamondlord.github.io/ServiceWorkerPush/Bubble-Nebula.jpg",
    "click_action": "https://www.nasa.gov/feature/goddard/2016/hubble-sees-a-star-inflating-a-giant-bubble"
  },
  "to": "YOUR-TOKEN-ID"
}
```
