# ParamHashGUI
Automatically replace name value to parameter with xml(bprm).
GUI version of ParamHash by tkgstrator.
# Rules
1. Don't distribute secondary.
2. Don't use it badly.
3. Besides, don't violate the law.
4. Don't forget to respect tkgstrator.
# How to use?
1. Download the file and launch the "ParamHashGUI.exe" or "ParamHashGUI.pyw".
2. Enter the required information and "スタート".
3. Have fun.
## Before
```xml
<?xml version="1.0" encoding="shift_jis"?>
<Root>
  <isBigEndian Value="False" />
  <BymlFormatVersion Value="3" />
  <C1>
    <C1 Name="a4fa7c89">
      <D2 Name="1021205b" StringValue="7" />
      <D2 Name="175a16e5" StringValue="1" />
      <D2 Name="1781ec" StringValue="60" />
      <D2 Name="1792df5" StringValue="0.02" />
      <D2 Name="1bb9e947" StringValue="0.2" />
      <D1 Name="22d7439b" StringValue="20" />
      <D1 Name="246457be" StringValue="1200" /
```

## After
```xml
<?xml version="1.0" encoding="shift_jis"?>
<Root>
  <isBigEndian Value="False" />
  <BymlFormatVersion Value="3" />
  <C1>
    <C1 Name="param">
      <D2 Name="mBurst_SplashPaintR" StringValue="7" />
      <D2 Name="mRiseFall_AltitudeCheck_OfstY" StringValue="1" />
      <D2 Name="mCollisionRadiusFar" StringValue="60" />
      <D2 Name="unknown" StringValue="0.02" />
      <D2 Name="mRiseFall_ToSquid_GravityDownSt" StringValue="0.2" />
      <D1 Name="mJetFootDamagePerFrame" StringValue="20" />
      <D1 Name="mDamage" StringValue="1200" />
```
# Support
・Sorakana#8466
・[My Server](https://discord.gg/DQB6fcD6qq)
## Credits
* tkgstrator
* OatmealDome
* Simon
* leanny

2022/07/01 By Sorakana

