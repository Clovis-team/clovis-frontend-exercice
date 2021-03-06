# Clovis projects dashboard

[![Greenkeeper badge](https://badges.greenkeeper.io/Clovis-team/clovis-frontend-exercise.svg)](https://greenkeeper.io/)
![logo](images/logo-clovis.png)

#### Happy to see you there :sunglasses: !

No time for :beer: let's go..


## Instructions

The Clovis team wants to be able to quickly browse the projects of its users thanks to a magnificent dashboard. (a clovis project is often a building under construction). Remember, our users are architects, designers, construction workers ;) 

Clovis backend developers have already created a REST API to retrieve project information.


Here are the two routes of the API :

#### GET - Projects list
- url : http://localhost:1337/api/projects
```json
[
    {
         "id": 1,
         "name": "A31 - Aire de Malvaux",
         "image": "http://image.canal-plus.com/media_cpa/img/movie/default/280_157/jpg/ANT_1163084_1_280_157.jpg"
    },
...
]
```

#### GET - Project details
- url : http://localhost:1337/api/projects/:id
```json
{
    "id": 1,
    "name": "A31 - Aire de Malvaux",
    "image": "http://image.canal-plus.com/media_cpa/img/movie/default/280_157/jpg/ANT_1163084_1_280_157.jpg",
    "description": "Spicy jalapeno bacon ipsum dolor amet bresaola tongue kevin t-bone ham hock pig pancetta chicken. Prosciutto cow tongue ham jerky. Spare ribs landjaeger burgdoggen, pork belly kevin strip steak pork chop filet mignon. Alcatra strip steak biltong beef ribs pork loin brisket short loin tail filet mignon hamburger beef fatback shankle. Pig leberkas meatloaf kevin doner ground round tenderloin. Andouille salami beef ribs leberkas.",
    "tag": "Aire"
}
```

Your mission is to create a React SPA which display projects tiles and their details when the user selects a project.

You are free to make technical choices (libs, tools), UX and ergonomics!


## Technical details

You can start the API server by running the command :
```
npm start
```

## Closing Remarks

Clovis team does, however, have a few principles:
* She likes robust applications
* She likes scalable applications
* She likes industrialized applications
* She likes tested applications

Good luck !
