# no-code AI app

Welcome to the no-code AI tools project! In this project, you'll use Flowise to work with advanced AI technology without writing any code. Flowise helps you integrate AI capabilities easily, to create and deploy powerful AI solutions.


## Install dependencies 
1. Git
2. Docker

### Clone the Flowise repository

```bash
Git clone https://github.com/FlowiseAI/Flowise.git`
```


### Install with 🐳  Docker

1. Go to `docker` folder at the root of the project
2. Copy `.env.example` file, paste it into the same location, and rename to `.env`
3. Edit `.env` file to uncomment line:9 (to enable CORS policy) and save the file.
4. Build and run container using the command `docker compose up -d`
5. Open [http://localhost:3000](http://localhost:3000)
6. You can bring the containers down by `docker compose stop`
