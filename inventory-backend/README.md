[`<-- Go back`](../README.md)

# Inventory Backend

## Setup
See: [First-time setup](./server_instructions.md)

## Run
Depending on your case, inside the `inventory-backend` directory you can execute one of the following scripts to launch the server:

- [launch_server.sh](https://github.com/linomp/polito-comm-systems-project/blob/main/inventory-backend/launch_server.sh) - if you have a virtual environment (venv). It connects to our remote DB running on DigitalOcean.
- [launch_server_no_venv.sh](https://github.com/linomp/polito-comm-systems-project/blob/main/inventory-backend/launch_server_no_venv.sh) - if you are using anaconda and not venv. It connects to our remote DB running on DigitalOcean.
- [launch_server_local.sh](https://github.com/linomp/polito-comm-systems-project/blob/main/inventory-backend/launch_server_local.sh) - if you have a virtual environment (venv) and local MySQL installation with the `plcs_db` already in place.
- [launch_server_no_venv_local.sh](https://github.com/linomp/polito-comm-systems-project/blob/main/inventory-backend/launch_server_no_venv_local.sh) - if you are using anaconda and not venv. Requires a local MySQL installation with the `plcs_db` already in place.

## Test
- [test_no_venv.sh](https://github.com/linomp/polito-comm-systems-project/blob/main/inventory-backend/launch_server_no_venv.sh) - if you are using anaconda and not venv. It connects to our remote DB running on DigitalOcean.

- [test_no_venv_local.sh](https://github.com/linomp/polito-comm-systems-project/blob/main/inventory-backend/launch_server_no_venv_local.sh) - if you are using anaconda and not venv. Requires a local MySQL installation with the `plcs_db` already in place.
