# How to use

## Clone project
### github server

```shell
git clone https://github.com/ohmcoe/lab-mysql.git
```

### coe server

```shell
git clone http://gitlab.coe.phuket.psu.ac.th/sakarin.k/lab-mysql.git
```

## List container

```shell
docker ps -a
```

## remove container

```shell
docker rm <CONTAINER_NAME>
```

## Start mysql server

```shell
docker-compose up -d
```

### ก่อนการใช้งานจำเป็นต้องแก้ docker-compose.yml ให้ถูกต้องตามสภาพแวดล้อมที่จะใช้งาน
### ในกรณีเกิด error ให้ทำการลบ container เก่าที่ชื่อซ้ำกันออกก่อน


## Stop mysql server

```shell
docker-compose down
```

## Use mysql

```shell
docker exec -it <CONTAINER_NAME> <MYSQL_COMMAND>
```
