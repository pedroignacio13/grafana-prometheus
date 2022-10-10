# Grafana + Prometheus lab

This is a simple lab so you can get started using prometheus and grafana.
You can see a whole step-by-step video by "The Digital Life" explanation here (https://www.youtube.com/watch?v=9TJx7QTrTyo).
The files contained in this repository were built in a manner so you can deploy all the needed resources at once.

## Requirements

Since we're using a docker-compose file, the Docker engine is the only requirement.

## Steps

1. Clone this repository
2. Make sure Docker is running in your computer
3. Make sure to insert the ABSOLUTE PATH to your prometheus.yml file in the docker-compose prometheus volume's declaration
4. Open a terminal instance inside the folder which contains the files you downloaded
5. Execute the following command:

```bash
docker-compose up -d
```

To take the resources down without deleting them, execute the command:

```bash
docker-compose stop
```
