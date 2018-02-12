# angular-nginx-docker-compose

angular nginx docker-compose

## Install Homebrew

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### Make sure Homebrew is up to date

    brew update

### Install Node (npm will be installed with Node)

    brew install node

### Update Node if already installed

    brew upgrade node

## Install Angular CLI

    npm install -g @angular/cli
    npm install -g typescript

## Create Angular application

    ng new angular-nginx --service-worker --routing --style scss

## Starts and creates all containers/services/images/volumes

    docker-compose up -d

