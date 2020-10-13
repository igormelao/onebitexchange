
# [One Bit Exchange](https://github.com/igormelao/onebitexchange) 
![ruby](https://img.shields.io/badge/Ruby-2.6.5-red.svg)
![rails](https://img.shields.io/badge/Rails-6.0.2-red.svg)
![docker](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)
![Codeship Status for igormelao/onebitexchange](https://app.codeship.com/projects/2ddb03a0-efc5-0138-2aba-623498a99a86/status?branch=master)
<div>
  <h4>Quanto está a cotação agora?</h4>
  <h5>Converta cambio e saiba quanto custa uma conversão de moedas agora mesmo!</h5>
  <h5>Rápido, fácil e intuitivo</h5>
</div>


# Basic Overview

<p>Saiba rapidamente quanto uma cotação está valendo nesse exato momento. Basta apenas escolher a moeda a ser convertida e a moeda destino. Coloque o valor a ser convertido e pronto.</p>

Enjoy it!


# Demo

<a href="https://onebitexchange2020.herokuapp.com/">One Bit Exchange</a>

# Require
```
  * Rails 6.0.2
  * Ruby 2.6.5
  * Docker
  * Docker Compose
  * Postgres
  * Bootstrap
  * Rest-client
  * FFaker
  * FactoryBot
  * Rspec
  * Capybara
```


# Getting Started

### 1. Do a fork at original repository
```
  git@github.com:igormelao/onebitexchange.git
```

### 2. Clone your fork at a local repository

### 3. Build you project with docker-compose
```
   $ docker-compose build      
```

### 4. Start docker-compose
```
   $ docker-compose up
```

### 4. Run all migrations
```
   $ docker-compose run --rm app rails db:create db:migrate      
```

### 5. How to execute other commands
```
$ docker-compose run --rm app commandName
```

### 6. Install new gems
```
Always when you install a new gem execute step 3
```

### 7. Start APP
```
$ docker-compose up
```

### 8. Test App
```
$ docker-compose run --rm app rails rspec
```

## How to contribute to the project

### 1. Add the remote repository source at your local repositoy
```
$ git remote add upstream git@github.com:igormelao/onebitexchange.git
```

### 2. Sync your repository with the original repository
```
$ git fetch upstream
```

### 3. Update your local repository
```
$ git checkout master
$ git merge upstream/master
```

### 4. Work on it and send your changes
```
$ git push origin master
```

### 5. Do a pull request at your fork on GitHub


\\_o_// HAO! Live long and prosper!
