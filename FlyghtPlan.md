## STACKATHON PLAN

### Build database

[] Users model
[] Flights Model
[x] Airports Model

#### Associations:

users have many flights
flights have many users

need to use airports model to look up flight origin and destination lat/long

### Flight input form

render form 3x on page (?)

### Animate Flight Routes

use deck-gl and shader layers

### Export video of Animated Routes

is this even possible?
[] look into kepler.gl

## Less Important

### Add Popups for Airports

### OAuth setup

get api key from google

- To use OAuth with Google, complete the steps with a real client ID and client secret supplied from Google
  - You can get them from the [Google APIs dashboard][google-apis].

[google-apis]: https://console.developers.google.com/apis/credentials

```
process.env.GOOGLE_CLIENT_ID = 'hush hush'
process.env.GOOGLE_CLIENT_SECRET = 'pretty secret'
process.env.GOOGLE_CALLBACK = '/auth/google/callback'
```

### Deploy

heroku setup
