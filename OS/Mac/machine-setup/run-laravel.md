## New Machine Rapid Setup for Laravel

1. Install [Homebrew](https://brew.sh/)

```
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Add Homebrew to `PATH`

```
  echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/gm/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
```

3. Install PHP via Homebrew

```
  brew install php
```

4. Download [Composer](https://getcomposer.org/download/)

```
  php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '55ce33d7678c5a611085589f1f3ddf8b3c52d662cd01d4ba75c0ee0459970c2200a51f492d557530c71c15d8dba01eae') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```

5. Move Composer to `PATH`

```
  sudo mv composer.phar /usr/local/bin/composer
```

6. Install `laravel` command  using Composer

```
  composer global require laravel/installer
```


7. Expand `~` on `PATH` for Composer

```
  export PATH="$HOME/.composer/vendor/bin:$PATH"
```

8. Create laravel app

```
  laravel new x-artisan
```
