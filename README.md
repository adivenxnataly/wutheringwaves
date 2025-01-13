### Wuthering Waves Config

this is config for optimizing rendering on Android devices.
differences of some configurations:

High:
> still uses the default resolution, but removes details from materials, effects and colors.

Mid:
> using 720p resolution, Low LOD, and removing material details, effects and colors.

Low:
> using 500p resolution, Low LOD, LDRP, removing bloom effects, and details as above.

#### Requirements
this is just a config file, which only needs access in directory `/Android/data`:

    com.kurogames.wutheringwaves.global/files/UE4Games/Client/Client/Saved/Config/

you just need to paste the file and replace it in the directory above, and go straight into the game.

#### Reference & Source
Reference: [AlteriaX](https://github.com/AlteriaX/WuWa-Configs)
Source: [UE4.27 Command](https://framedsc.com/GeneralGuides/ue4_commands.htm)
