
# Build FEniCS container 

## Build writable container from the recipe 

```bash
$ sudo singularity build --writable fenics.img Singularity 
```

## Run FEniCS (python) 

```bash
$ singularity exec fenics.img python ./heat.py
```
Or
```bash 
$ ./fenics.img ./heat.py
```
