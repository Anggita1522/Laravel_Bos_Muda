


# Laravel LMS


# Installation
1. Clone this repo
```
git clone https://github.com/emtiazzahid/e-learning.git
```

2. Install composer packages
```
cd e-learning
```
```
composer install
```

3. Create and setup .env file
```
cp .env.example .env
```
```
php artisan key:generate
```

6. Migrate and insert records
```
php artisan migrate --seed
```

