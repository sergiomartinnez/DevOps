# DevOps

## Table of contents
* [General info](#general-info) 
* [Technologies](#technologies) 
* [Extra information](#Extra)

------------

## General info

What I learned in the course was what DevOps (developers and operators) is like a culture that mix the both teams , automation for reproduce infrastucture, measures how long our common goals take to finish and finally sharing better intern tools for all the coworkers. I learn about terraform that allow us to write code that can be read on different OS and regions. Software test (Unitest, integration test, aceptance test, system test, component test). I learned about **Continuous integration, Continuous delivery and continuous deployment**. i learned the difference between deployments like Blue/green, canary and rolling deployments. how to Incident response and webservice for web monitorig. I learned about the levels of the errors in production (fatak, error, info, uncall, exception trackers) *Extra information below*.

------------

## Technologies
- No technology was used during the course.


------------

## Extra
>- Devops (not a new person on the team, its a team)
>- Unitest, Integration test, aceptance test, system test, component test
>- Unit test use mock, integration test use real dependencies with fixtures, acceptance test use the environment as if the production
>- pull request reviews someone reviews four code before sending to production, fix the code problems that cannot easily to see
>- Continuous integration (CI) It's a workflow used by teams of developers and makes it easy to add functionality to products
>- Continuous delivery (CD) is a CI extension that automates the entire process of adding code to the main branch, so that can be deployed to production at any time manually and safely.
>- Continuous deployment (CD) it goes one step further and the deployment is also automatic. Changes are seen in minutes and you receive customer feedback to quickly iterate
>- Difference between is that continuous delivery is manual and continuous deployment is automatic
>- Blue/green deployment: two tags of the same code, you update one and the other receives the traffic
>- Canary deployments: you have a pool of nodes (3 for example) and instead of modifying all 3 nodes at the same time, you only modify 1 or 2 of those nodes to avoid breaking everything
>- Rollin deployment: pool of machines, you go, you connect to one you give update and you go out and you go to the other and you give update and so on your entire pool
>- SLO/SLI for measure the success 
>- Site reliability engineering is how the companies measure if their product is good
>- Fatal: something is wrong and is killing the service
>- Error: If you control the service and it is internal
>- Info: when a service external to us fails
>- Uncall: a person who is receiving calls and the service goes down
>- Exception trackers: an exception that is not handled in your code, used for when you have too many Logs. Centry.io
