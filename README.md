Docker and related files for my personal environment

Use `.env.example` for environment variables needed to setup services.

Note: If you are using Portainer for deploying these, for any values that have dollar signs, double it. I.E., if a password is "123$abc", set it to "123$$ABC".  This may not apply to using docker-compose directly.  See: https://docs.docker.com/compose/compose-file/#interpolation
