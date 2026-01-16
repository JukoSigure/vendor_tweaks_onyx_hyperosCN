# Onyx HyperOS 3 CN Vendor Tweaks 3.0.9.0

# What Changed?

• Adjusted vendor props
- dalvik for 8/12gb of ram

• Updated Qualcomm Adreno (TM) Proprietary Binaries

This repository provides information about the Qualcomm Adreno (TM) GPU renderer version: OpenGL ES 3.2, Vulkan 1.4

- OpenGL ES Version: OpenGL V@0842.21
- Vulkan Version: Vulkan 512.842.21 git@114a4db556 (API upstreaming up to 1.4.295)
- Git Commit: git@114a4db556

- [Adreno - Wikipedia](https://en.wikipedia.org/wiki/Adreno)
- [Qualcomm Developer Network](https://developer.qualcomm.com/)

• Tuned Qualcomm cpu performance boost profiles

perfboostsconfig.xml
perfboostselection.xml

• Reworked gpu table
| Clock (MHZ)  | Voltage |
| ------------- | ------------- | 
| 1050 | 288-NOM-L1  |
| 995 | 256-NOM |
| 937 | 224-SVS-L2 |
| 832 | 192-SVS-L1 |
| 763 | 144-SVS-L0 | 
| 688 | 128-SVS  |
| 606 | 64-LOW-SVS |
| 510 | 48-MIN-L1  |
| 443 | 16-RETENTION |
| 362 | 16-RETENTION|
| 264 | 16-RETENTION |
| 138 | 16-RETENTION | 


## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
