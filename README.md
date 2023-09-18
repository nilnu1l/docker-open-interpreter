# CMD
1. `mkdir $PWD/data`
2. `docker build ./ -t open-interpreter`
3. `docker run --rm -p 8000:8000 --env-file=$PWD/openinterpreter/.env -v ./data:/output-data  -it open-interpreter:latest`
