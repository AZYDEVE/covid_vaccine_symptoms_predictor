To run dockerized service,
first cd into the root directory of the project.

in terminal,

to build the container:

$docker build -f Dockerfile -t app:latest .

to run the docker service:

$docker run -p 8501:8501 app:latest

visit http://localhost:8501/ on your local browser.