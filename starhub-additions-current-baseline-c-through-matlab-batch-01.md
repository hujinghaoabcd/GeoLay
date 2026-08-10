# StarHub 当前基线补库记录｜C 至 MATLAB 第一批

> 当前基线：`starhub-backup-2026-08-10.json`
> 范围：C、C++、Fortran、Shell、Java、MATLAB
> 规则：已与当前 StarHub 全库做精确 `owner/repo` 去重；用户明确不要的项目不纳入增加清单；“可加”项目默认不自动纳入强推荐增加清单，除非用户明确选择。

## 最终建议增加

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

### Fortran（3）
- `MPAS-Dev/MPAS-Model`
- `ufs-community/ufs-weather-model`
- `NOAA-OWP/noah-owp-modular`

用户不要：3 `earth-system-radiation/rte-rrtmgp`、5 `NOAA-GFDL/MOM6`、6 `MITgcm/MITgcm`、7 `schism-dev/schism`、8 `adcirc/adcirc`
可加但未纳入强推荐：9 `fmidev/RoadSurf`

### Shell（1）
- `geoserver/docker`

用户不要：2 `conda-forge/miniforge`、3 `nvm-sh/nvm`、4 `jenv/jenv`、5 `pyenv/pyenv`、6 `scop/bash-completion`

### Java（5）
- `gama-platform/gama`
- `matsim-org/matsim-libs`
- `opentripplanner/OpenTripPlanner`
- `eqasim-org/eqasim-java`
- `Unidata/netcdf-java`

可加但未纳入强推荐：6 `Unidata/IDV`

### MATLAB（3）
- `TopoToolbox/topotoolbox3`
- `Shrediquette/PIVlab`
- `mathworks/toolboxdesign`

用户不要：2 `sandialabs/tensor_toolbox`、3 `matlab/matlab-agentic-toolkit`
可加但未纳入强推荐：6 `TopoToolbox/TTLEM`

## 汇总

- C：3
- C++：3
- Fortran：3
- Shell：1
- Java：5
- MATLAB：3
- 强推荐增加合计：18
- 状态：已确认选择，尚未生成 Star 命令
