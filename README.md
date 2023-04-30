# docker-dev-env-golang-img

[ARCHIVED]
Archiving repo due to changes with docker dev environment
>

    Changes to Dev Environments with Docker Desktop 4.13

    Docker has simplified how you configure your dev environment project. All you need to get started is a compose-dev.yaml file. If you have an existing project with a .docker/ folder this is automatically migrated the next time you launch.

    If you are using .docker/docker-compose.yaml, we move it to ../compose-dev.yaml. If you are using .docker/config.json, we create a ../compose-dev.yaml file with a single service named “app”. It is configured to use the image or Dockerfile referenced in the JSON as a starting point.
