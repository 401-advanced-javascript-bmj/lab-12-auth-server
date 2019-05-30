# OAuth Comparative Analysis

## Wordpress

### Research Conducted By: Morgana, Rebecca, Joé

### Overall Score and Comments

#### Score (Out of 10): 7

#### General Comments

_Describe the stack (front-end only? full stack?), database, efficiency, etc. Describe the general usability and learnability_

#### Pros

- Well documented
- Google integration
- Easy to integrate
- Access to many properties {name, email, firstName, lastName, …}
- Login with email link

#### Cons

- Less control than auth0
- Limited integration with other providers
- No restriction to publish on http
- Not as pervasive as other integrations

### Ratings and Reviews

#### Documentation

The documention is well written and contains examples. Links on the side bar could be better grouped for the User section. API documentation is not interactive (like Swagger).

#### Systems Requirements

_Above and beyond 'node' and 'linux', what dependencies or core requirements exist for this framework? Can it play at AWS/Heroku? Does it require a certain database?_

It is currently setup to work with Mongo but it can work with any other DB. There's no reason to believe that we can't deploy this app on another provider.

#### Ramp-Up Projections

_How long would/should it take a team of mid-junior developers to become productive?_

If they are familiar with oauth2, the implementation is very straight forward. They should be able to implement within a day.

#### Community Support and Adoption levels

_How popular is this framework? What big companies are running on it? How is it "seen" in the general JS community? Is there an active community of developers supporting and growing it?_

WordPress is the most popular CMS, but having a WordPress.com account is not as pervasive as having a Google or a Twitter account. Although since it is possible to sign in with Google as part of the WordPress integration, the coverage is pretty decent.

### Links and Resources

- [framework](https://www.wordpress.com)
- [docs](https://developer.wordpress.com/docs/oauth2/)
- [examples/tutorials](https://developer.wordpress.com/docs/oauth2/)

### Code Demos

- Live application:
  - [Front-end](https://github.com/401-advanced-javascript-bmj/lab-12-www-server/tree/switch-to-wordpress)
  - [Back-end](https://github.com/401-advanced-javascript-bmj/lab-12-auth-server/tree/switch-to-wordpress)
- Code repository
  - [Front-end](https://lab-12-front-end.herokuapp.com/)
  - [Back-end](https://lab-12-backend.herokuapp.com/)

### Operating Instructions

If someone were to download your repo (above), what steps do they need to take to run the application

- `npm start`
- Endpoint: `/foo/bar/`
  - Returns a JSON object with abc in it.
- Endpoint: `/bing/zing/`
  - Returns a JSON object with xyz in it.
