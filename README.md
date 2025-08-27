# <p align="center">𝙅𝙇𝙞𝙗</p>
<p align="center"><a href="https://discord.gg/bvhM2aRPXT"><img src="https://img.shields.io/discord/1324751463531937802?style=flat&amp;logo=discord&amp;logoColor=FFFFFF&amp;label=Jenoclip&#39;s%20Doomworks&amp;labelColor=5865F2&amp;color=FFFFFF" alt="Discord"></a> <a href="https://zdoom.org/wiki/ACS"><img src="https://img.shields.io/badge/ACS-1F1F1F?style=flat&amp;label=ZDoom%20Wiki&amp;labelColor=BC001D" alt="Static Badge"></a> <a href="https://wiki.zandronum.com/ACS"><img src="https://img.shields.io/badge/ACS-FFFFFF?style=flat&amp;label=Zandronum%20Wiki&amp;labelColor=5CBD46" alt="Static Badge"></a> <a href="https://github.com/zeta-group/zt-bcc"><img src="https://img.shields.io/badge/Zt--BCC-2b3137?style=flat&amp;logo=github&amp;logoColor=fafbfc" alt="Static Badge"></a></p>

JLib is an open-source ACS library based on [Zt-BCC](https://github.com/zeta-group/zt-bcc), JLib is compatible with ports based on ZDoom 2.8 and higher <sup>[(See more in: Compatibility)](#Compatibility)</sup>.
<br><br/>
### JLib Provides the following list of features and functions
#### JDefs.acs
- Type aliases that can be used everywhere (RGBA8_, NAng_, Flags_, Num_, UInt8 etc)
- Short function aliases (FxD, FxM, SetTID, ACS_NCall etc)
- Mathematical constants (MathC_Pi, MathC_Tau, MathC_E etc)
- Programming constants (Word_Max, UInt32_Max, Int8_Max etc)

#### JCommon.acs
- Creating vectors (2D, 3D, 4D)
- Global variables (MaxPNum, MinPNum etc)

#### JMath.acs
- Rotating 3D and 2D points by all 3 axes
- Converting Cartesian XYZ coordinates into Polar R.A.P.<sup>_(**R**adius, **A**ngle, **P**itch)_</sup> coordinates and vise-versa
- Angle conversion functions (Byte angles, normalized(fixed-point) angles, integer degrees and fixed-point degrees conversions)
- Extra trigonometry (Tan, Csc, Ctg etc)
- Extra integer, fixed-point and any-number-type math functions (Bounce, Mean, Clamp, Map, HalfPoint etc)

#### JWorld.acs
- Extra TID operations (TID_SetZ, TID_SetVXY, TID_AddVYZ, TID_GetPos etc)

#### JGraphic.acs
- Different types of 3D→2D projections (and also UE 2.5 "Corona"-styled projection)
- Virtual HUD scaling functions (FullScreenVFHUD, RatioMap, GetWndRatio, GetRatioScaling etc)
- Color space conversions (RGBA8::To_RGB8, RGB8::From_NV3, HSV8::To_HSVA8 etc)
<br><br/><a name="Compatibility"></a>
### JLib compatibility
#### Ports:
- (R)ZDoom 2.8+
- GZDoom 1.8.6+
- Zandronum 3.2+
- LZDoom (any version)
- VKDoom (any version)
- QZDoom (any version)
- Dude, this list is endless, do you really need to see all the ports [based on ZDoom](https://doomwiki.org/wiki/ZDoom-family) 2.8+?
#### Compilers:
- Zt-BCC v0.10.0 Alpha 6 and higher
