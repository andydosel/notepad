# notepad

## System

slmgr -ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D

slmgr -skms kms.03k.org

slmgr -ato

---

## \Office16  OSPP.VBS

cscript ospp.vbs /sethst:kms.03k.org

cscript ospp.vbs /act

### Xiaohe

'''
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Microsoft\InputMethod\Settings\CHS]
"Enable Cloud Candidate"=dword:00000000
"Enable Dynamic Candidate Ranking"=dword:00000001
"EnableExtraDomainType"=dword:00000001
"Enable self-learning"=dword:00000001
"EnableSmartSelfLearning"=dword:00000001
"EnableLiveSticker"=dword:00000000
"Enable EUDP"=dword:00000001
"Enable Double Pinyin"=dword:00000001
"UserDefinedDoublePinyinScheme0"="xiaohe*2*^*iuvdjhcwfg^xmlnpbksqszxkrltvyovt"
"DoublePinyinScheme"=dword:0000000a
'''

## Game Mode

### Color

1. Nvida Control Panel
1. Video Color Setting
1. Dynamic range -> Full(0-255)
1. Resolution
1. Output Dynamic range -> Full
1. Refresh rate -> Highest
1. 3D Settings
1. Preferred refresh rate -> Highest
1. Low latency mode -> On or Highest

### Mouse

Precision -> Off

### Keyboard

Repeat delay -> Lowest

### Power Plan

1. Hard disk off after -> 240 min
1. Wireless adapter -> Highest performance
1. USB pause -> off

### Device Manager

1. System Device
1. Programmable interrupt controller -> banned
1. High-precision event timer -> banned

### LOL

Delete Cross

### Powershell

(ROOT)

mmagent

set-mmagent

8GB RAM -> 2048

16GB RAM or higher -> 4096

disble-mmagent -MemoryCompression
disble-mmagent -PageCombining

### Regedit

1. LOCAL_MACHINE
1. SYSTEM
1. CurrentControlSet
1. Control
1. Session Manager
1. Memory Management
1. LargeSystemCache -> 1
1. SessionPoolSize -> 6(1080p) or 2(2k) or 4(4k)
1. SessionViewSize -> 62(1080p) or 122(2k) or 244(4k)

### FullScreen Optimize

win10 1903 or higher or win11 on

else off

### Video Settings

1. Nvida Control Panel
1. 3D Setting
1. App Setting
1. Lol Client
1. Low latency mode -> Highest
1. Anisotropic filtration -> 8X
1. Power manage mode -> Highest performance
1. Trilinear optimization -> off
1. Anisotropic sampling optimization -> off
1. Negative LOD offset -> lock
1. Desktop Size and Position
1. Scaling Mode -> no scaling
1. Scaling on -> GPU
