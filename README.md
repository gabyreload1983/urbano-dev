# URBANO MYSQL DEV

Urbano Database

![MySQL](https://raw.githubusercontent.com/github/explore/main/topics/mysql/mysql.png)

## Technologies Used

- MySQL
- Docker

## Getting Stared

To set up MySQL Database and get it running on your local development environment, follow these steps:

### Prerequisites

- Linux or Windows
- Visual Studio
- NODE.js >= 18
- Workbench
- Docker
- Dcoker-Compose

## Installation

1. Download urbano.yml
2. Complete environmet variables MYSQL_ROOT_PASSWORD, MYSQL_DATABASE and port.
3. Create container

```bash
docker-compose -f urbano.yml up -d
```

4. Stop container

```bash
docker stop urbano-dev
```

5. Get an urbano database backup, copy and paste into your ~/path/db. You need to get permitions for that folder
6. Start container

```bash
docker start urbano-dev
```
