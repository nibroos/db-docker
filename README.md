<h1 align="center">
    <br>
  Backend
  <br>
</h1>

## 📗 Configurations
Copy `.env.example`, rename it to `.env`, Modify to suit your environment, The key name is explanatory itself.

Modify `docker-compose.yml` and `Dockerfile.x` file if you want to experiment.

Modify the database by adding new key or change the value on `configs/../my.cnf` folder as you need.

## 🚀 Quick Start

Starts the containers in the background and leaves them running
```bash
docker-compose up -d
```
> <b>Note</b> : These includes variable/configuration databases

Stops containers and removes containers, networks, volumes, and images
```bash
docker-compose down
```

Since its persisted, if you want to wipe the databases.
```bash
docker-compose down -v
```

## 💎 The Package Features

<p>
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=fff" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/-MySQL-336791?style=for-the-badge&logo=MySQL&logoColor=fff" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/-NGINX-269539?style=for-the-badge&logo=NGINX&logoColor=fff" />
</p>

### 📗 Coming up!
- Make separate database & config file

Feel free to ask if you have any questions or need more details!