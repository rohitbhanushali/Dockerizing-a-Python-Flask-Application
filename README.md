# Project: Dockerize python flask application

This project helps us understand and know how to dockerize an application (python flask in this case)

## Overview

### Introduction

- Tech stack: `python`, `docker`, `flask`
- To get basic concept of these tools, you could visit: [**devops-basic**](https://github.com/tungbq/devops-basic) repository

### Prerequisite

- You have docker installed on your machine
- Basic knowledge about docker

## 1-Install docker

- See: [how-to-install-docker](https://github.com/tungbq/devops-basic/tree/main/topics/docker#how-to-install-docker)

## 2-Build the docker image

- Run `docker build -t my-flask-app .`
![image](https://github.com/user-attachments/assets/8f4f3047-6fbe-4cae-a34f-bca03825948b)

## 3-Run the Docker container based on the image

- Run `docker run -p 5000:5000 my-flask-app`

![image](https://github.com/user-attachments/assets/7bce8489-647d-4688-b73e-24e0d86b1508)


## 4-Verify the result

- `curl localhost:5000`
- Or open http://localhost:5000/ in your browser

![image](https://github.com/user-attachments/assets/18f47eaf-d014-4a4e-bd89-e71f2212ee0a)


## 5-Bonus

All in one script could be found at [demo_project.sh](./demo_project.sh)

## Related link

- https://pypi.org/project/Flask/
- https://www.docker.com/
- https://github.com/tungbq/devops-basic/blob/main/topics/docker/README.md

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
