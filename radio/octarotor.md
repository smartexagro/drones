# General

```
Name PX4 OCTA
EEprom Size 519 bytes
Model Image X650pro
Throttle Source: THR Trim idle only: No Warning: Yes Reversed: No
Trims Step: Fine Display: Never Extended: No
Center Beep Throttle
Switch
Warnings
```
## SA↑ SB↑ SC↑ SD↑ SE↑ SF↑ SG↑

```
Pot Warnings Mode: OFF
Other Extended Limits: No Display Checklist: No Global Functions:
Yes
Timers Time Switch CountdownMin.call Persist
Tmr1 00:00:00 OFF Silent No OFF
Tmr2 00:00:00 OFF Silent No OFF
Tmr3 00:00:00 OFF Silent No OFF
```
# Modules

```
Internal Radio
System
```
```
Protocol: FrSky XJT (D16) Channels: 1-8 Receiver: 1
Failsafe Mode: No pulses
External Radio
Module
```
```
Protocol: OFF
```
```
Trainer port Mode: Master/Jack
```
# Flight modes

```
Flight mode Switch F.In F.Out TrmR TrmE TrmT TrmA
FM0:STABILIZE---- 0 0 0 0 0 0
FM1:STABILIZE---- 0 0 FM0 FM0 FM0 FM
FM2:RTL SC- 0 0 FM0 FM0 FM0 FM
FM3:LAND SC↓ 0 0 FM0 FM0 FM0 FM
FM4:STABILIZESD↑ 0 0 FM0 FM0 FM0 FM
FM5:ALTHOLD SD- 0 0 FM0 FM0 FM0 FM
FM6:LOITER SD↓ 0 0 FM0 FM0 FM0 FM
FM7 ---- 0 0 FM0 FM0 FM0 FM
FM8 ---- 0 0 FM0 FM0 FM0 FM
Global vars GV1 GV2 GV3 GV4 GV5 GV6 GV7 GV8 GV
Name
Unit
Prec 0._ 0._ 0._ 0._ 0._ 0._ 0._ 0._ 0._
Min -1024 -1024 -1024 -1024-1024 -1024 -1024 -1024 -
Max 1024 1024 1024 1024 1024 1024 1024 1024 1024
Popup N N N N N N N N N
Flight mode
FM0:STABILIZE 0 0 0 0 0 0 0 0 0
```

## FM1:STABILIZEFM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

## FM2:RTL FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

## FM3:LAND FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

## FM4:STABILIZEFM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

## FM5:ALTHOLD FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

## FM6:LOITER FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

## FM7 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

## FM8 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM0 FM

# Inputs

```
I1:Thr Ail Weight(+100%)
I2:Ail Rud Weight(+100%)
I3:Ele Ele Weight(+100%)
I4:Rud Thr Weight(+100%)
```
# Mixers

```
CH1 I1:Thr Weight(+100%)
CH2 I4:Rud Weight(+100%)
CH3 I3:Ele Weight(+100%)
CH4 I2:Ail Weight(+100%)
CH5 SD Weight(+20%) Flight mode(FM0:STABILIZE) Switch(SD↑)
NoTrim Offset(-70%)
:= SD Weight(+20%) Flight mode(FM4:STABILIZE) Switch(SD-)
NoTrim Offset(-70%)
:= SD Weight(+20%) Flight mode(FM5:ALTHOLD) Switch(SD↓)
NoTrim Offset(-50%)
:= SD Weight(+20%) Flight mode(FM6:LOITER) Switch(SC↑)
NoTrim
:= SD Weight(+5%) Flight mode(FM2:RTL) Switch(SC-) NoTrim
Offset(5%)
:= SD Weight(+5%) Flight mode(FM3:LAND) Switch(SC↓) NoTrim
Offset(40%)
CH7 SF Weight(+100%)
CH8 SH Weight(+100%)
```
# Outputs

```
Channel SubtrimMin Max Direct Curve PPM Linear
CH1 +0.0% -100.0%+100.0%NOR ---- 1500 N
CH2 +0.0% -100.0%+100.0%NOR ---- 1500 N
CH3 +0.0% -100.0%+100.0%NOR ---- 1500 N
CH4 +0.0% -100.0%+100.0%NOR ---- 1500 N
CH5 +0.0% -100.0%+100.0%NOR ---- 1500 N
CH7 +0.0% -100.0%+100.0%NOR ---- 1500 N
CH8 +0.0% -100.0%+100.0%NOR ---- 1500 N
```
# Special Functions

```
SF1 SG↓ - Volume (S2)
```

# Telemetry

```
Protocol FrSky S.PORT
RSSI Alarms Low: < 45; Critical: < 42; Telemetry audio: Enable
Altimetry Vario source: RxBt
Vario limits > Sink max: -10; Sink min: -0.5; Climb
in: 0.5; Climb max: 10; Center silent: No
Top Bar Volts source: None; Altitude source: None
Multi sensors Enable
```
# Telemetry Sensors

```
Name Type Parameters
TELE1:RSSI Custom Id: F101 Inst: 25 Unit: dB Prec: 0 Ratio: 0 Offset:
0 A/Offset: N Filter: N Positive: N Log: Y
TELE2:RxBt Custom Id: F104 Inst: 25 Unit: V Prec: 1 Ratio: 13.
Offset: 0 A/Offset: N Filter: Y Positive: N Log: Y
```

