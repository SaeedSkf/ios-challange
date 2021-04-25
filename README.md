# Mobile Interview Assignment

## Overview

Thanks for your interest in joining Us! For the next step of the interview process, we'd like for you to participate in a small project. Your task is to implement the following design and replicate it as close as possible.

## Design mockup:
![design](https://i.imgur.com/WN2ZRKw.png)

## Mocked Users API:
```curl
curl --request GET 'https://60859fb1d14a8700175780be.mockapi.io/api/users'
```
This endpoint returns a dummy list of articles with the following structure:
```json
[{
    "id": "1",
    "createdAt": "2021-04-25T04:14:34.567Z",
    "name": "Lelah",
    "avatar": "https://s3.amazonaws.com/uifaces/faces/twitter/kaelifa/128.jpg",
    "family": "Gutmann",
    "phoneNumber": "407.604.3782 x76001"
}]
```

## Acceptance criteria

* The first 5 users should be in the first section. (Quick Add)
* Each section should be have its corners rounded to 12.0px.  
* Each section should have a shadow with 5% opacity, (0, 4) offset, 10.0 radius, and #000000.  
* The separator should be half of a pixel in height (based on device scale).   
* The left & right padding of the section title should be 8px.  
* Your implementation should handle certain edge cases including (variable number of users per section, and empty sections).  

## Minimum technical Expectation
* Minimum **85%** test coverage. (Optional)
* MVVM architecture and clean coding style.
* Use **SwiftUI** to declare user interface.
* App should support `iOS 13.0` and above.
* As a mobile engineer, you should be able to detect/prevent errors and possible edge cases.

## Next Step
Our mobile development team will review your task carefully and contact you as soon as possible.
