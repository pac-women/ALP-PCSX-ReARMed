# ALP PCSX-ReARMed

How To Build PCSX-ReARMed for ALP

- Source: https://github.com/notaz/pcsx_rearmed
- Build steps
```	
# prepare
git clone https://github.com/notaz/pcsx_rearmed.git
cd pcsx_rearmed
git submodule update --init --recursive

# build
source /opt/rk3399env.sh
make -f Makefile.libretro
```
- executable output:
	**pcsx_rearmed_libretro.so

