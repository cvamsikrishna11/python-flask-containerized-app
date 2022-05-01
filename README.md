# Ghost in Shell

Repository for working with a small Python and flask application that displays
and serves static web files (HTML/CSS).

### Prerequisites

- Python 3

### Installation

After cloning the repository, change to the cloned directory and
install the requirements with the following command:

```bash
pip install -r requirements.txt
```


### Usage

To start the Flask application, start the application by simply
calling the app.py file from the root of the cloned repository:

```bash
python3 app.py
```

Please note: the application does work as given.


### Usage as a container

To create a docker image for the application and run the docker image as a container execute the below commands in the project folder

```bash

docker build --tag python-flask-image .

docker run -d -p 5000:5000 python-flask-image

```

### License

MIT


### Ref blogs
* https://www.freecodecamp.org/news/how-to-dockerize-a-flask-app/
* https://www.whitesourcesoftware.com/free-developer-tools/blog/docker-expose-port/
* https://we-are.bookmyshow.com/understanding-expose-in-dockerfile-266938b6a33d
* https://www.baeldung.com/ops/docker/expose-vs-publish

