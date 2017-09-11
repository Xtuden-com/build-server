# Signing Apps

## Run

```
docker-compose up -d
./buildApps <app-list-file>
```

- App lists are stored in folder `channels`
- Helper folder `repo` with checkouts of needed git repos.
- Docker used to provide occ command for signing
- Folder `build` contains apps with signed release version
- Folder `release` contains tarballs

## TODO

- Build one docker image to do all work
- build daily, master and release branches
- mechanism to build on demand (chatOps?)
