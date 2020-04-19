## Notebook for predicting remaining games of 19/20 Premier league season

### How to run in Docker (which I highly recommend)

Clone this repo to [path_to_git_repo] then run below command on terminal
```
docker run -it -p 8888:8888 -v /home/user/[path_to_git_repo]:/home/jovyan/docs/source/notebooks/local/
```

this opens up your 8888 port to the 8888 container port where you can access [path_to_git_repo] in the [/home/jovyan/docs/source/notebooks/local/] folder.

Open up notebook link and select /notebooks > /local > "premier league prediction 1920.ipynb"

Run cells from start to end

