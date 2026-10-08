## About This Branch
This branch incorporates some of the fixes I wrote (mainly targeting some issues that occur when the game runs at high frame rates).
To enable/disable my fixes in the code, define/undefine **FIX_BUGS_MAYBE** in **core/config.h**.
Because some of the fixes are contained within the **FIX_BUGS** macro check, define FIX_BUGS in **core/config.h** before using **FIX_BUGS_MAYBE**; **FIX_BUGS_MAYBE** is defined under the **FIX_BUGS** macro.
All of these fixes are experimental; they may not achieve exactly the same effect as the game running at 30 fps and may introduce more issues.
Due to my limited personal ability, I can only attempt to solve basic and obvious problems, and not all issues can be resolved.
I will upload the modified files later and include the details of the fixes.\
