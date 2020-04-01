# Migration scripts for ReportPortal
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FHardNorth%2Fmigrations.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FHardNorth%2Fmigrations?ref=badge_shield)


### Usage

#### Update to latest revision
```sh
docker-compose run --rm migrations
```

#### Downgrade to previous revision
```sh
docker-compose run --rm migrations down
```

#### Downgrade to N revisions back
```sh
docker-compose run --rm migrations down N
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FHardNorth%2Fmigrations.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FHardNorth%2Fmigrations?ref=badge_large)