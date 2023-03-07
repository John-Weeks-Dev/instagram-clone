# Instagram Clone (instagram-clone)

### Tutorial showing you how to build Instagram 

If you'd like a step by step guide on how to build this just **CLICK THE IMAGE BELOW**

[![GO TO JOHN WEEKS DEV TUTORIAL VIDEOS](https://user-images.githubusercontent.com/108229029/223138285-642a5296-2013-428c-a9d6-f27754c3a477.png)](https://www.youtube.com/watch?v=MjkamZQJY_8)

Come and check out my YOUTUBE channel for lots more tutorials -> https://www.youtube.com/@johnweeksdev

**LIKE**, **SUBSCRIBE**, and **SMASH THE NOTIFICATION BELL**!!!

## App Setup

```
git clone https://github.com/John-Weeks-Dev/instagram-clone.git

composer install 

cp .env.example .env 

php artisan cache:clear 

composer dump-autoload 

php artisan key:generate

composer require laravel/breeze --dev

php artisan breeze:install vue --ssr

php artisan serve
```
Create the DB
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=instagram_clone
DB_USERNAME=root
DB_PASSWORD=
```
Now migrate your DB
```
php artisan migrate

```

Now run this command to start the project 
```
npm i

npm run dev
```

You should be good to go!

# Application Images

<img width="1436" src="https://user-images.githubusercontent.com/108229029/222710711-fe1dc595-b7c5-4ab6-8783-2a1753cd4879.png">
<img width="1436" src="https://user-images.githubusercontent.com/108229029/222711203-c00395d4-3f08-4c15-8bba-aef6fa0a736f.png">
<img width="1436" src="https://user-images.githubusercontent.com/108229029/222711321-d9b50939-2d9c-494f-91d2-8f1926cf6ace.png">
<img width="1436" src="https://user-images.githubusercontent.com/108229029/222712057-a34c9700-835d-4144-b958-cfad6d74e4dc.png">
<img width="1436" src="https://user-images.githubusercontent.com/108229029/222712230-4d3a39fb-b6cf-4a29-a80b-e5b7882562c0.png">
<img width="1436" src="https://user-images.githubusercontent.com/108229029/222712419-fc6755a7-6914-4fd1-b5c8-b704c7583f01.png">

<div>
    <img width="380" src="https://user-images.githubusercontent.com/108229029/222880031-b1c7d304-0e5e-483c-8d29-9da2e55cd133.png">
    <img width="380" src="https://user-images.githubusercontent.com/108229029/222880056-9c2246a3-1981-492f-a90a-46daedb1c007.png">
</div>

<div>
    <img width="300" src="https://user-images.githubusercontent.com/108229029/222713541-04e14e99-a672-46ff-8479-01045071a16e.png">
    <img width="300" src="https://user-images.githubusercontent.com/108229029/222713690-df7d5217-217d-45ef-9c76-dd7668e7b044.png">
    <img width="300" src="https://user-images.githubusercontent.com/108229029/222713748-1a2116ed-ce4c-47aa-b1fc-ff5e813529d2.png">
</div>



