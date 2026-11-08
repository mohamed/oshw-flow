# Open-Source HW Design flow

## Building the container

```
apptainer build --fakeroot oshw-flow.sif oshw-flow.def
apptainer run oshw-flow.sif
```


## Included Tools

- [verilator](https://github.com/verilator/verilator)
- [yosys](https://github.com/YosysHQ/yosys)
- [OpenSTA](https://github.com/parallaxsw/OpenSTA)
- [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD)
- [xschem](https://github.com/StefanSchippers/xschem)
- [magic](https://github.com/rtimothyedwards/magic)
- [netgen](https://github.com/rtimothyedwards/netgen)
