
## Install

### 1. Clone the source code or create new project.

```shell
git clone https://github.com/guru2921/laravel-docker.git
```

### 2. Set up Docker environment

docker-compose up

Confirm that you have configured the docker-compose.yml and Dockerfile correctly.

### 3. Install the extended package dependency.

Install the `Laravel` extended repositories: 

```shell
composer install -vvv
```

Install the `Vuejs` extended repositories: 

```shel
npm install
```

Compile the js code: 

```shel
npm run dev

// OR

npm run watch

// OR

npm run production
```

### 4. Run the blog install command, the command will run the `migrate` command and generate test data.

```shell
php artisan blog:install
```

## Basic Features

- Manage users, articles, discussions and media
- Statistical tables
- Categorize articles
- Label classification
- Content moderation
- Own comments system
- Multi-language switching
- Markdown Editor
- Roles & Permissions
- and more...

[PJ Blog](https://github.com/jcc/blog) Laravel 5.*

## Server Requirements

- PHP >= 7.1.0
- Node >= 6.x
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension

## Preview

![New Blog](https://cdn.pigjian.com/cover/2018/09/07/d2T4cAjTagf5L1rXH1FjLsFkJVffsPIGPkHEl2A5.jpg)

![New Blog](https://cdn.pigjian.com/cover/2018/09/07/4b7ExtB6NHZVh8n5KnW2673Ej6gwtLm1SUAubtpa.jpg)


