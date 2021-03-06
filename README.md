# Back End Development and APIs Projects
## Timestamp Microservice

A microservice made in Express.js, first Back End and API project from the freeCodeCamp curriculum.

When requested with a valid date (date time string format), or with a unix timestamp, it returns a json made of:

- a `unix` key with the Unix timestamp of the input in milliseconds as the value, and
- a `utc` key with the UTC of the input as the value.

If the request has no date field, the Unix and UTC of the current time is returned.

Usage example:

Input: https://timestamp-microservice-fcc.vercel.app **/api/2022-1-28**

Output: `{ unix: 1643328000000, utc: "Fri, 28 Jan 2022 00:00:00 GMT" }`


This API is hosted on [Vercel](https://timestamp-microservice-fcc.vercel.app/).

![EXPRESS](https://img.shields.io/badge/Express.js-fff.svg?&logo=Express&logoColor=000)&nbsp;
![HTML5](https://img.shields.io/badge/HTML5-red.svg?&logo=html5&logoColor=white)&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-blue.svg?&logo=css3&logoColor=white)&nbsp;

---

![screenshot(60%)](https://user-images.githubusercontent.com/78434326/151837368-6a951e9c-e118-44b7-909f-d790ff2831f8.png)
