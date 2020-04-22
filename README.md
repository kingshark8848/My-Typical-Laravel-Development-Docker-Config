
## Directory Structure

- included in this git repository:
    + docker-compose.yml
    + docker-config: store docker configurations

- git ignored:
    + docker-data: store volumes data (persisted) 
    + src: used to save laravel project source code

without update php compose packages/migrations, you can run: 
`docker-compose -f docker-compose.yml -f docker-compose_no-install.yml up`

or just run `./docker-up_no_install.sh` (a shortcut script) 