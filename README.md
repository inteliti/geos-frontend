[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=EL-BID_geos-frontend&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=EL-BID_geos-frontend)

# Guia Edutec Repository - Open Source

## Front-end project


Access to other projects
* [Back-end](https://github.com/EL-BID/geos-backend)
* [Database](https://github.com/EL-BID/geos-database)


---
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

---
## Troubleshooting

Make sure `docker-compose.yml` has network `geos-network` created.
```
networks:
  geos-network:
```

## Dev environment

```
npm i
node run start 
```

---
_The Guia Edutec was originally developed by CIEB. The process of opening the code has made possible by financial support of Fundación ProFuturo._
