# StarHub 当前基线补库记录｜C 至 MATLAB 第一批

> 当前基线：`starhub-backup-2026-08-10.json`
> 范围：C、C++、Fortran、Shell、Java、MATLAB
> 规则：已与当前 StarHub 全库做精确 `owner/repo` 去重；用户明确不要的项目不纳入增加清单；用户本轮仅列出“不要”的编号，因此其余项目（包括上一轮标为“可加”的项目）均按接受处理。

## 最终增加

### C（3）
- `HDFGroup/hdf5`
- `NOAA-EMC/wgrib2`
- `Deutsches-Klimarechenzentrum/libaec`

用户不要：4 `AquaticEcoDynamics/GLM`、5 `Blosc/c-blosc`

### C++（3）
- `CesiumGS/cesium-native`
- `OpenFOAM/OpenFOAM-dev`
- `KratosMultiphysics/Kratos`

用户不要：2 `fzi-forschungszentrum-informatik/Lanelet2`、5 `idaholab/moose`、6 `carla-simulator/carla`

### Fortran（4）
- `MPAS-Dev/MPAS-Model`
- `ufs-community/ufs-weather-model`
- `NOAA-OWP/noah-owp-modular`
- `fmidev/RoadSurf`

用户不要：3 `earth-system-radiation/rte-rrtmgp`、5 `NOAA-GFDL/MOM6`、6 `MITgcm/MITgcm`、7 `schism-dev/schism`、8 `adcirc/adcirc`

### Shell（1）
- `geoserver/docker`

用户不要：2 `conda-forge/miniforge`、3 `nvm-sh/nvm`、4 `jenv/jenv`、5 `pyenv/pyenv`、6 `scop/bash-completion`

### Java（6）
- `gama-platform/gama`
- `matsim-org/matsim-libs`
- `opentripplanner/OpenTripPlanner`
- `eqasim-org/eqasim-java`
- `Unidata/netcdf-java`
- `Unidata/IDV`

### MATLAB（4）
- `TopoToolbox/topotoolbox3`
- `Shrediquette/PIVlab`
- `mathworks/toolboxdesign`
- `TopoToolbox/TTLEM`

用户不要：2 `sandialabs/tensor_toolbox`、3 `matlab/matlab-agentic-toolkit`

## 汇总

- C：3
- C++：3
- Fortran：4
- Shell：1
- Java：6
- MATLAB：4
- 最终增加合计：21
- 状态：已确认选择，尚未生成 Star 命令
