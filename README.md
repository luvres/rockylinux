## Rockylinux 8.6
-----

### Pull image
```
docker pull izone/rockylinux
```

### Run
```
docker run --rm --name rocky -ti izone/rockylinux bash
```

-----
### Build
```
docker build -t izone/rockylinux:latest -f ./Dockerfile .
```
```
docker build -t izone/rockylinux:warewulf -f ./Dockerfile.warewulf .
```
```
docker build -t izone/rockylinux:nvidia -f ./Dockerfile.nvidia .
```
```
docker build -t izone/rockylinux:openmpi -f ./Dockerfile.openmpi .
```
```
docker build -t izone/rockylinux:openhpc -f ./Dockerfile.openhpc .
```


