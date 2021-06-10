---
title: Add post
subtitle: 
# author: sara
tags: [api]
videos: 
    - title: Generate API-Key
      url: https://youtu.be/_OhSTyVSCSM
    - title: Using Postman for API testing
      url: https://youtu.be/-RYkapHBVs8
---

# Description
Add Post API allows to create new post on specific channel

#### Example payload

```json
{
    "title":"Hello world",
    "content": "This is my message",
    "toChannelId": "123"
}

```

#### Properties

| Property    | Required | Type   | Example                | Description                             |
| ----------- | -------- | ------ | ---------------------- | --------------------------------------- |
| title       | false    | String | `"Hello world"`        | post title                              |
| content     | true     | String | `"This is my message"` | post content                            |
| toChannelId | true     | String | `"456"`                | channel id (can be copied from zira UI) |