# Laravel GB CRM

## What's inside

- Adminpanel with AdminLTE 3 and two roles
- Users/Roles/permissions management function (based on Spatie Roles-Permissions)
- Everything that is needed for CRUDs: model+migration+controller+requests+views


__Notice__: AdminLTE 3 version was not released officially. At the time of writing (April 2019), the latest was [v3.0.0-Alpha 2 release in May 2018](https://github.com/ColorlibHQ/AdminLTE/releases/tag/v3.0.0-alpha.2). But, at current alpha state, the theme is good enough to use for simple CRUDs like ours.

## Screenshots

![Laravel + AdminLTE3 screenshot 01]()

![Laravel + AdminLTE3 screenshot 02]()

![Laravel + AdminLTE3 screenshot 03]()

![Laravel + AdminLTE3 screenshot 04]()

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL or go to __/login__ and login with default credentials __admin@admin.com__ - __password__

## License

Basically, feel free to use and re-use any way you want.
