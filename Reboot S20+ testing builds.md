# Reboot S20+ testing / builds support


Here i will put some of my tested builds + the features that it comes with like bugs or something i know this repo is about Carbon ch4 and stuff BUT i will show some ways  to get some Expermantall reboot seasons working sice No one is gonna help in the discord

**NOTE:** Currently Reboot is NOT supporting some of the S20 Builds as of right now if u have some questions contact me on discord: **`ducki67`**

Here are the builds that Milxnor tested:

 <img width="436" height="449" alt="image" src="https://github.com/user-attachments/assets/34fb4bbd-9eba-4a4e-ba2e-ffa2305a4d0e" />


## How to get Reboot Season20+ DLL?
### Simply just make it on you own!

Here's a  lil'  Tutorial for the DLL to compile it.

**NOTE:** DON'T DO THIS DLL STUFF IF YOU ARE TOO STUPID FOR IT AND DONT KNOW HOW TO USE CODING SOFTWERS **AND** NO ONE WILL EVER HELP YOU IN REBOOT SUPPORT ABOUT S20+ !!!

**Requirements:**

- Visual Studio 2022
- Reboot GS source code [Here btw](https://github.com/Milxnor/Project-Reboot-3.0)
- Winrar (for extracting the source code BTW not really needed )

## The steps
- **1.** Download the Reboot source code from (**Requirements**) then extract it Using Winrar or anything you have
- **2.** Open the `Project Reboot 3.0.sln` file
- **3.** go to `inc.h` file and on Line 26 remove two slashes (/) to uncomment it! (make sure to do save in the file with `Ctrk + Shift + S` )
- **4.** On top of VS2022 change the `Debug` to **`Release `**  AND right next to it make sure its set to `X64` ( it kinda depends on you / your development what u want to use it for)
- **5.** Go on very to where its says `Build` click on it and chose **`Build Solution`** OR **`Ctrl + Shift + B`**
- **6. (S22 Console dll)** IF your season is broken for the Console dll just go in `dllmain.cpp` file and on Line 904 remove two slashes (/) for **"`#define CLIENT_ONLY`"** IF you do this your Reboot dll will be made as a console dll !!!! ( This is not needed for season between 20.00 - 22.30 and S23+ !!)


And now you made it! now from here on your own. 

IF you are gonna use the source in you project GIVE Credits to the Reboot team or i will come after you.








# Tested / Under testing builds
 
The list of build that i found for testing / you can try

**These builds are Above S19 AKA Above Ch3S1 !!!**

| Build | Download | Source type / From | Tested? |
|--|--|--|--|
| 20.00 | [Link 1](https://public.simplyblk.xyz/20.00.rar) | SimplyBLK | Not yet :/ |
| 20.10 | [Link 1](https://public.simplyblk.xyz/20.10.zip) | SimplyBLK | Not yet :/ |
| 20.20 | [Link 1](https://public.simplyblk.xyz/20.20.zip) | SimplyBLK | Not yet :/ |
| 20.30 | [Link 1](https://galaxiafn.co.uk/20.30.zip) [Link 2](https://cdn.cbn.lol/20.30) | GalaxiaFn / Carbon | Soon :) |
| 20.40 | [Link 1](https://public.simplyblk.xyz/20.40.zip) [Link 2](https://builds.rebootfn.org/20.40.zip) [Link 3](https://cdn.cbn.lol/20.40) | SimplyBLK / RebootFn / Carbon| Tested :)) |
| 21.00 | [Link 1](https://r2.ploosh.dev/21.00.zip) [Link 2](https://cdn.solarisfn.org/21.00.zip) [Link 3](https://builds.fn-builds.net/21.00-CL-20463113.7z) | Ploosh / SolarisFn / ByZN | Tested :)) |
| 21.10 | [Link 1](https://public.simplyblk.xyz/21.10.zip) | SimplyBLK | Note yet
| 21.20 | [Link 1](https://cdn.cbn.lol/21.20) [Link 2](https://builds.fn-builds.net/21.20-CL-21035704.7z) | Carbon / ByZN | Tested :)) |
| 21.30 | [Link 1](https://cdn.cbn.lol/21.30) [Link 2](https://builds.fn-builds.net/21.30-CL-21155462.7z) | Carbon / ByZN | SOON |
| 21.40 | [Link 1](https://cdn.cbn.lol/21.40) [Link 2](https://builds.fn-builds.net/21.40-CL-21407327.7z)| Carbon / ByZN | Tetsed :)) |
| 21.50 | [Link 1](https://public.simplyblk.xyz/21.50.zip) | SimplyBLK| Not yet :/ |
| 21.51 | [Link 1](https://public.simplyblk.xyz/21.51.7z) [Link 2](https://builds.fn-builds.net/21.51-CL-21735703.7z) | SimplyBLK / ByZN | Soon :) |
| 22.00 | [Link 1](https://public.simplyblk.xyz/22.00.7z) | SimplyBLK | Soon:) |
| 22.10 | [Link 1](https://cdn.cbn.lol/22.10) [Link 2](https://builds.fn-builds.net/22.00-CL-22149829.7z) | Carbon / ByZN | Tested :)) |
| 22.20 | [Link 1](https://builds.fn-builds.net/22.20-CL-22600409.7z) | ByZN | Note tested yet :( |
| 22.40 | [Link 1](https://builds.fn-builds.net/22.40-CL-23070899.7z) | ByZN | Note tested yte :( |
| 23.00 | [Link 1](https://public.simplyblk.xyz/23.00.7z) [Link 2](https://builds.fn-builds.net/23.00-CL-23344627.7z) | SimplyBLK / byZN | Not tested / May not work |
| 23.10 | [Link 1](https://public.simplyblk.xyz/23.10.rar) [Link 2](https://builds.fn-builds.net/23.10-CL-23572221.zip) | SimplyBLK / ByZN | Not tested / May not work |
| 23.20 | [Link 1](https://builds.fn-builds.net/23.20-CL-23783097.zip) | ByZN | Not tested / May not work |
| 23.40 | [Link 1](https://public.simplyblk.xyz/23.40.zip) [Link 2](https://builds.fn-builds.net/23.40-CL-24087481.zip) | SimplyBLK / ByZN | Not tested / May not work |
| 23.50 | [Link 1](https://public.simplyblk.xyz/23.50.zip) [Link 2](https://titanac.xyz/23.50.rar) | SimplyBLK / Project Nexa| Tested / Didnt work yet |


## Currently tested by Me:




>## 20.40
>
>IMPORTANT: use **Starfall.dll** as *your* account to get in lobby and after that to host a server swich back to **cobalt.dll** for the host account!!!
>
>- U can load in with skins and pickaxes, 
>- No sprining, 
>- U can mantle itw works fine, 
>- Looting a chest or anything will crash the bost the game and server,
>- U get some hight ping, (since is not supported well)
>- U cant farm mats you gotta use commands,
>
> **For mats and ammo and a set of guns use this command line that I created:** 
```batch
cheat giveitem AthenaAmmoDataShells 9999 | cheat giveitem AmmoDataRockets 9999 | cheat giveitem AmmoDataEnergyCell 9999 | cheat giveitem AthenaAmmoDataBulletsHeavy 9999 | cheat giveitem AthenaAmmoDataBulletsLight 9999 | cheat giveitem AthenaAmmoDataBulletsMedium 9999 | cheat giveitem MetalItemData 999 | cheat giveitem StoneItemData 999 | cheat giveitem WoodItemData 999 | cheat giveitem WID_Shotgun_Standard_Athena_SR_Ore_T03 | cheat giveitem WID_Assault_Auto_Athena_R_Ore_T03 | cheat giveitem WID_Pistol_AutoHeavyPDW_Athena_SR_Ore_T03 | cheat giveitem WID_Sniper_Heavy_Athena_VR_Ore_T03
```

>## 20.40-CL-20244966
> issue image soon
>
> Encrypt error >:(
>- Cant even launch :(
>- Crashes



>## 21.00
>
>IMPORTANT: use **Starfall.dll** as *your* account to get in lobby and after that to host a server swich back to **cobalt.dll** for the host account!!!
>
>- U can load in with skins and pickaxes, 
>- No sprining, 
>- U can mantle itw works fine, 
>- Looting a chest or anything will crash the bost the game and server,
>- U get some hight ping, (since is not supported well)
>- U cant farm mats you gotta use commands,
>
> **For mats and ammo and a set of guns use this command line that I created:** 
```batch
cheat giveitem AthenaAmmoDataShells 9999 | cheat giveitem AmmoDataRockets 9999 | cheat giveitem AmmoDataEnergyCell 9999 | cheat giveitem AthenaAmmoDataBulletsHeavy 9999 | cheat giveitem AthenaAmmoDataBulletsLight 9999 | cheat giveitem AthenaAmmoDataBulletsMedium 9999 | cheat giveitem MetalItemData 999 | cheat giveitem StoneItemData 999 | cheat giveitem WoodItemData 999 | cheat giveitem WID_Shotgun_Standard_Athena_SR_Ore_T03 | cheat giveitem WID_Assault_Auto_Athena_R_Ore_T03 | cheat giveitem WID_Pistol_AutoHeavyPDW_Athena_SR_Ore_T03 | cheat giveitem WID_Sniper_Heavy_Athena_VR_Ore_T03
```



>## 21.20
>[Issue](https://github.com/user-attachments/assets/c63ad6c8-e1a8-4375-869d-a30b9ee23bd5)
>
>- Cant even launch :(
>- Crashes





>## 21.20
>[Issue](https://github.com/user-attachments/assets/261cdde5-9b78-4270-9f52-17927045d76f)
>
>- Cant even launch :(
>- Crashes



# 21.30 (soon)



>## 21.40
>[Issue](https://github.com/user-attachments/assets/c8a18941-16cc-4a84-ae2a-ca09171526ba)
>
>- Cant even launch :(
>- Crashes



>## 22.10
> [Issue](https://github.com/user-attachments/assets/ede93ff4-0efe-478f-a5d9-c147597bdff6)
>
>- Cant even launch :(
>- Crashes




























