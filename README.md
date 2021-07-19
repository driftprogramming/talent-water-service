# talent-water-service
```commandline
.
├── dist                    
│   ├── talent_water_service.${target}.${env}          # talent water service binary, e.g.: talent_water_service.linux.live       
│   └── profile.cov    # test coverage report
├── scripts                    
│   └── build.sh       # go test, lint and build this repo
├── envs               # local, dev, live, see ./script/build.sh       
│   ├── .env           # common env variables, which will be loaded in all other envs
│   ├── .env.dev       # dev env variables
│   ├── .env.live      # live env variables
│   ├── .env.local     # local env variables     
│   └── .env.test      # test env variables       
└── ...
```
