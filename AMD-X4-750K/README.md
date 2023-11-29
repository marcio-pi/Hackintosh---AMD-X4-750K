# Hackintosh - AMD Athlon X4 750K

## Configuration
| Hardware | Model | 
| :---: | :---: |
| CPU | AMD Athlon X4 750K | 
| MotherBoard | ASRock FM2A85X Extreme4 |
| Chipset | AMD A85X (Hudson-D4) | 
| GPU | AMD Radeon HD 7750 | 
| RAM | 2GB DDR3 running at 667 MHz `×2` | 
| Storage | Crucial MX500 250GB | 
| Audio | Realtek ALC892 | 
| Network | Realtek RTL8111E | 
| Monitor | Asus VG248QE 1920x1080 | 

## System Detail
- Version: macOS High Sierra 10.13.6 (17G10021)

![Screenshot](./screenshot/info.png?raw=true) 

- Monitor:

![Screenshot](./screenshot/monitor.png?raw=true) 

## Hardware Support
### Working
- CPU ([AMD Vanilla](https://github.com/AMD-OSX/AMD_Vanilla))
- GPU (native support)
- Audio （`VoodooHDA.kext`）
- Network
### Not Working
- GPU Hardware Acceleration (don't know how its possible, but that's what VDAChecker says)
- CPU not recognized
- USB Map (not properly mapped 😝)
- so many other things...😖

## Working on...
- USB Map
- GPU Hardware Acceleration
- Replacing `VoodooHDA.kext` with `AppleALC.kext`
- Increasing RAM frequency to default `1600MHz`
- Trying to enable `X86PlatformPlugin` and fix <q>Power Management</q>
- fixing some boot warnings...

## Credits
 - [Dortania Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
 - [Dortania Post-Install Guide](https://dortania.github.io/OpenCore-Post-Install/)
 - [inspirating chinese guy](https://github.com/KHwang9883/Hackintosh-AMD-X4-760K/tree/master)
