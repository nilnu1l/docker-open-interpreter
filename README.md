# CMD
1. `git clone https://github.com/nilnu1l/docker-open-interpreter.git`
2. `cd docker-open-interpreter`
3. `mkdir $PWD/data`
4. `docker build ./ -t open-interpreter`
5. `docker run --rm -p 8000:8000 --env-file=$PWD/openinterpreter/.env -v ./data:/output-data  -it open-interpreter:latest`
