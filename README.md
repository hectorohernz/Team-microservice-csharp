# Team Service Mircoservice

Team Service is a mircoservice created on the .Net Core Framework. Test Driven Development on XUnit framework. 



| Resource | Action     |     Description  |
| :------------- | :----------: | -----------: |
|  /teams | GET  | Gets list of all teams   |
| /teams/{id}   | GET | Gets details for a single team |
|/teams/{id}/members| GET | Gets members of a team 
|/teams| POST| Creates a new team 
|/teams/{id}/members| POST| Adds a member to a team|
|/teams/{id} | PUT| Updates team properties|
|/teams/{id}/members/{memberId}| PUT| Updates member properties
|/teams/{id}/members/{memberId}| DELETE | Removes a member from the team
|/teams/{id}| DELETE| Removes an entire team
