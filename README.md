# VL.IO.DotEnvFile

Small wrapper for https://github.com/nozzlegear/dotenvfile to work with [vvvv-gamma](https://vvvv.org)

### Installation

```sh
TODO: NUGET
```

### About
A `.env` file, used to store environment variables, e.g. variables defined per environment, such maybe database url, database password, any sensitive information, that should be available during as early as possible and should not be leaked away. Normally `.env` allways should be added to `.gitignore`, instead you should provide an `.env-example` with definitions of variables, yor system should expect. You can continue reading this [article](https://upsun.com/blog/what-is-env-file/). 

`.env` originating from `nodejs` you can check [dotenv#rules](https://www.npmjs.com/package/dotenv#rules) for `.env` rules. (Hope some of theme work) 
Original usage of `.env` file, is to allow to run application in multiple `CICD` environments, e.g. `tests`, `satage`, `prod`. So you can have you `secrets` stored and setted up explicitly per environment...

### Credits

- [nozzlegear](https://github.com/nozzlegear)
- [antokhio](https://github.com/antokhio)
