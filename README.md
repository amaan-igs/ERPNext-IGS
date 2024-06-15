# ERPNext-IGS

[![Build Stable](https://github.com/frappe/frappe_docker/actions/workflows/build_stable.yml/badge.svg)](https://github.com/frappe/frappe_docker/actions/workflows/build_stable.yml)
[![Build Develop](https://github.com/frappe/frappe_docker/actions/workflows/build_develop.yml/badge.svg)](https://github.com/frappe/frappe_docker/actions/workflows/build_develop.yml)

Welcome to ERPNext-IGS, provided by Inotech Global Solutions (IGS). This repository contains everything you need to deploy ERPNext and Frappe in containers.

## Getting Started

To get started, you'll need to have Docker, docker-compose, and git set up on your machine. If you're new to Docker, refer to the [official Docker documentation](http://docs.docker.com) for basics and best practices.

### Try in Play With Docker

If you'd like to experiment in a pre-configured sandbox, simply click the button below:

<a href="https://labs.play-with-docker.com/?stack=https://raw.githubusercontent.com/frappe/frappe_docker/main/pwd.yml">
  <img src="https://raw.githubusercontent.com/play-with-docker/stacks/master/assets/images/button.png" alt="Try in PWD"/>
</a>

### Try on your Dev environment

First, clone this repository:

```sh
git clone https://github.com/amaan-igs/ERPNext-IGS.git
cd ERPNext-IGS

Then, run the following command to start the containers:
docker compose -f pwd.yml -d
