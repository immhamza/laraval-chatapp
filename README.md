<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>


## To run the project



- Download or git clone project.
- Copy .envexample file and make new file named it .env.
- Set up your database and update the DB name in .env file.
- Update .env

PUSHER_APP_ID=anyID
PUSHER_APP_KEY=anyKey
PUSHER_APP_SECRET=anySecret
PUSHER_APP_CLUSTER=mt1


- php artisan migrate.
- run npm install then npm run dev.
- run php artisan websocket:serve in one terminal. 
- php artisan serve in other terminal.
- Remember that for image uplaod run php artisan link:storage and update the APP_URL=http://localhost to APP_URL=http://localhost:8000






