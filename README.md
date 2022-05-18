# polito-comm-systems-project

- [`DB`](./DB/) contains the .sql file to create the database and tables of the project

- [`inventory-backend`](./inventory-backend/) contains the web service
    - Instructions to run it on your pc are [here](./server_instructions.md)
    - To run the tests, in the `inventory-backend` directory, activate the virtual environment and run `pytest`:
        ```
        source venv/Scripts/activate
        pytest
        ```

- [`raspberry-pi-scripts`](./raspberry-pi-scripts/) contains scripts to run in the rpi, e.g. nfc tag reading.

## Overall architecture of the app
<img src="./architecture.png" width="80%">
