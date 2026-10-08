[English](README.md) | [简体中文](README.zh-CN.md)
***
## About This Branch
This branch incorporates some of the fixes I wrote (mainly targeting some issues that occur when the game runs at high frame rates).
To enable/disable my fixes in the code, define/undefine **FIX_BUGS_MAYBE** in **core/config.h**.
Because some of the fixes are contained within the **FIX_BUGS** macro check, define FIX_BUGS in **core/config.h** before using **FIX_BUGS_MAYBE**; **FIX_BUGS_MAYBE** is defined under the **FIX_BUGS** macro.
All of these fixes are experimental; they may not achieve exactly the same effect as the game running at 30 fps and may introduce more issues.
Due to my limited personal ability, I can only attempt to solve basic and obvious problems, and not all issues can be resolved.
## What I Fixed?
Player to Object's Collision Force(TODO:Improve this.).\
Vehicle's TurnSpeed(Testing Method).\
Chainsaw To NPC's Push Force\
Missile's Flying Speed.\
Several Particle's Animation.\
Several Animations(Rubbish,Screendroplets,WaterSurface,Wheather,etc.)\
Mouse Position Locked even game lost focus\
NPC's Automobile&Bike Horn&Complain


