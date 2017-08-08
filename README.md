# Babble quickstart project

```
# Clone / download the quickstart repository and install dependencies.
git clone git@github.com:oal/babble-quickstart.git my-website
cd my-website
composer install

# Start dev server
composer dump-autoload -o
php -t public/ -S localhost:8000 public/index.php
```