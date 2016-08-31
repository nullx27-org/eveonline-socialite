# Eve Online Provider for Laravel Socialite

Install Larvel Socialite (see here: https://github.com/laravel/socialite/blob/2.0/readme.md)

Add the follwing to your .env file:

```
EVEONLINE_CLIENT_ID=
EVEONLINE_CLIENT_SECRET=
EVEONLINE_REDIRECT=
```

Add the following to your config/app.php
```
nullx27\Socialite\EveOnline\EveOnlineServiceProvider::class,
```

Get your Eve Online SSO credentials here: https://developers.eveonline.com/applications/
