# Kerbalism Companion Calculator
K³ implements an antenna planner for Kerbalism.

**Maintained fork:** https://github.com/Aebestach/KerbalismCompanionCalculator

### Compatibility
* Stock CommNet only (not RemoteTech)
* All kind of planet packs
* ResearchBodies support
* NFeX Reflectors support

### Build
1. Copy `KerbalismCompanionCalculator.props.user.example` to `KerbalismCompanionCalculator.props.user`
2. Set `KSPBT_GameRoot` to a KSP 1.12 install that already has Kerbalism (`GameData/Kerbalism/Kerbalism.dll`)
3. Build:

```bash
dotnet build KerbalismCompanionCalculator.sln -c Release
```

Optional: set `KCC_DeployToKsp` to `true` in the props.user file to copy `GameData/KerbalismCompanionCalculator` into that install after build.

![image](https://i.imgur.com/tzt9ruC.png "Planner GUI")

### License
* Project code and assets (except as noted below): [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
* UI sprite sheet by Nertea: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
* `ResearchBodiesWrapper.cs`: MIT (Jamie Leighton)

Originally by [Valentin Bischof](https://github.com/ValentinBischof/KerbalismCompanionCalculator). Maintained at [Aebestach/KerbalismCompanionCalculator](https://github.com/Aebestach/KerbalismCompanionCalculator). Redistribution under the same licenses: credit the original author, note any changes, keep derivatives under CC BY-SA 4.0, and keep Nertea’s sprites non-commercial under CC BY-NC-SA 4.0.
