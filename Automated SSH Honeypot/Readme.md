I am building an automated Linux CLI telemetry pipeline.

In this project i will run a fake SSH server(Cowrie) inside a Docker container on my linux PC.and generate simulated attacks (or expose it safely on a local subnet to attack from my windows PC via Powershell/SSH), and write a bash script using jq and standard linux tools to parse the JSON logs into a daily threat report.
