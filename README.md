# VL.IO.DotEnvFile

Small wrapper for https://github.com/nozzlegear/dotenvfile to work with [vvvv-gamma](https://vvvv.org)

### Installation

```sh
TODO: NUGET
```

### About
A `.env` file, used to store environment variables, e.g. variables defined per environment, such maybe database url, database password, any sensitive information, that should be available as early as possible during startup, and should not be leaked away. Normally `.env` should always be added to `.gitignore`, instead you should provide an `.env-example` with definitions of variables, yor system should expect. You can continue reading this [article](https://upsun.com/blog/what-is-env-file/). 

`.env` originating from `nodejs` you can check [dotenv#rules](https://www.npmjs.com/package/dotenv#rules) for `.env` rules. (Hope some of theme work) 
Original usage of `.env` file, is to allow to run application in multiple `CICD` environments, e.g. `tests`, `satage`, `prod`. So you can have you `secrets` stored and setted up explicitly per environment...

### Contrubuting

The original [DotEnvFile](https://github.com/nozzlegear/dotenvfile) provides methods like:
```cs
DotEnvFile.InjectIntoEnvironment(System.EnvironmentVariableTarget.Process, variables);
```
Witch were not including in initial release. If `one` would like to include this, we would gladly accept `PR's` starting with `feat/` feature, or `fix/` bugfix`

### Credits

- [nozzlegear](https://github.com/nozzlegear)
- [antokhio](https://github.com/antokhio)
