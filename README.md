# gxc-SharpHound

<a href="https://github.com/byt3n33dl3/gxc-SharpHoundAD/"><p align="center">
<img width="300" height="300" src="BHAD.svg">
</p></a>

My own custom **SharpHoundAD** kit and extension, BreedHound.

## Compile Instructions

```
dotnet restore.
dotnet build
```

## Requirements

SharpHound is designed targeting .Net 4.6.2. SharpHound must be run from the context of a domain user, either directly through a logon or through another method such as RUNAS.

## Get BreedHound

The latest build of BreedHound will always be found [here](https://github.com/byt3n33dl3/gxc-SharpHoundAD/releases).

To determine the BreedHound version compatible with a deployed **BloodHound** CE instance, login to BloodHound CE's web UI and click on ⚙️ (Settings) → Download Collectors. Then, click either the "Download BreedHound" button in the user interface or use the displayed BreedHound version to download the appropriate [release binary](https://github.com/byt3n33dl3/gxc-SharpHoundAD/releases). Alternatively, compile a BreedHound binary from the corresponding release commit.


## Feature Update

<details><summary>More !</summary>

```sh
src/
│
└── Client
   ├── context.cs ✔              
   ├── enums.cs ✔
   ├── flags.cs ✔
   ├── links.cs ✔
   ├── vulnscan.cs ✔   
   |
   └─── RES
       ├── harpoon.cpp ✔
       ├── harpoon.hpp ✔
       └── utils.cpp 
       |
       |
       └─── NET
            ├── client.cs ✔
            ├── dos.cs
            ├── example.sln ✔
            └─── pwn.cs
            
```
</details>

#### **sharphound.csproj** future update

```py
note: nothing now
```
