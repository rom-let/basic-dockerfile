# basic-dockerfile
Just a basic dockerfile

---

## How to use

*Supposing you already installed Docker on your machine*

1. Download the Dockerfile
2. Place it at the root of your project
3. run `sudo docker images`. It will show all images you have before the creation of your repo
4. run `sudo docker build -t nameOfYourRepo .`
5. run `sudo docker run nameOfYourRepo`
The code inside of the Dockerfile will then run, showing `Hello, Captain!` as expected
6. you can then rerun `sudo docker images` : you’ll find your repo in the list.

## Source

Project idea provided by [roadmap.sh](https://roadmap.sh/projects/basic-dockerfile)

