# odoo on Docker, for demo

This repo has 2 directories:
- `odoo11`
- `odoo12`

## Running odoo 12

- Go inside `odoo12` directory
- `docker-compose -f stack.yml up`
- Browse to `localhost:8069`

## Configuration for demo purposes

`odoo12/stack.yml` is the formula to  orchestate odoo and postgres.

This `yml` file does not include configuration to manage extra `add-ons` or any other `shared` resource between docker containers and host machine.