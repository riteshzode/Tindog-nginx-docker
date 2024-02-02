# Tindog-nginx-docker

Tin-Dog is a Tinder clone created using Bootstrap 5 and CSS styling. It provides a simple and stylish interface for connecting with potential canine companions.

## Requirements
- Bootstrap 5
- Font Awesome (for icons)
- Docker

## Docker Support

Build the image using the following command

```bash
$ docker build -t tin-dog-nginx:latest .
```

Run the Docker container using the command shown below.

```bash
$ docker run -d -p 8080:80 tin-dog-nginx:latest
```
This is because you want to expose the application on port 8080. You can adjust the `-p` flag to your preferred port.

## Deploying with Nginx

If you prefer to deploy Tin-Dog using a traditional Nginx setup without Docker:

- Copy the contents of the project into your Nginx web server directory.
- Make sure Nginx is installed and running.
- Access the application via the configured server.

## Contributors
Name : (@riteshzode)
Feel free to contribute and make Tin-Dog even better!
