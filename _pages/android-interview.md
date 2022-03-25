---
permalink: /android-interview/
title: VIZIO Android Take-Home project
author_profile: false
header:
  overlay_image: /assets/images/vizio-header.png
---
## Hello!
Thank you for interviewing with VIZIO. This document outlines the guideline you will need to complete the take-home project. You’ll have a week to complete the project. If you have any questions during the process please reach out to your recruiter and we’ll get back to you ASAP.

## Requirement
- Builds a TV show app that shows a list of TV shows from the provided endpoint.
- The app should display a list that shows all the TV shows returned from the JSON endpoint.
- Each item in the view should contain a summary of a TV show, including its image, title, and subtitle at a minimum.
- Make sure to handle the normal variety of errors when querying an endpoint.
- Unit tests should be provided for the app
- Please do not build any more screens than this list.

## JSON Endpoints (TODO to host JSON Data)

- URL 1
- URL 2
- URL 3

## JSON structure

| Key | Type | Note |
| --- | --- | --- |
| id | String | The unique identifier for the TV show |
| title | String | The title of the TV show |
| genres | String | The genres of the TV show |
| imagePath | String | The URL of the TV show’s image |

```json
{
      "tv_shows" : [
        {
          "id":"1",
          "title":"The Book of Boba Fett",
          "genres":"[Action, Adventure, Science Fiction]",
          "imagePath":"http://images.vizio.com/v4/vibes/1/getimage.aspx?vibeHandle=%7b%22Sid%22%3a3%2c%22Iid%22%3a3019340945%2c%22_tid%22%3a18%7d&vid=2000009&tid=32&width=480&height=720"
       },
        ...
      ]
    }
```

## What we are looking for

- Architectural consistency
- Cleanliness and concise of code
- Show us your best strength

# Submitting the project