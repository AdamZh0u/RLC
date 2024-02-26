# RLCA

- ENV build 
    -  `docker build --pull --rm -f "docker/Dockerfile" -t rl:latest "docker"`
    - win: docker run --network host --name rl -v "%cd%:/workspace"  -it rl:latest # --gpus all
    - max: docker run --network host --name rl -v ${PWD}:/workspace  -it rl:latest
    - connect to running image 

# ref
- https://github.com/lansinuote/More_Simple_Reinforcement_Learning


