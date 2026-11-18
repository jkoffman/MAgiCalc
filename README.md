<p align="center"><img src="logo.png" alt="" width="150"></p>

<h1 align="center">Josh's MAgical Calculator</h1>

<p align="center"><strong>GrandMA Parameter Calculator</strong><br>MA Lighting AutoMAgic Parameter Calculator</p>

A parameter calculator for grandMA2 and grandMA3 systems. Add the MA hardware in your session and it shows how many parameters you have, why each device does or doesn't count, and what to add if you're short.

**Use it:** https://jkoffman.github.io/MAgiCalc/

## What it does

- Separate grandMA2 and grandMA3 modes, each showing only the hardware that applies
- Works out console vs onPC rules from the hardware you add
- Enter the parameters your show needs and it shows the spare or the shortfall, with ways to close the gap
- Per-device breakdown, including parameters lost to the session max
- The link copies the exact setup, and the summary pastes into an advance sheet

## Rules

Based on MA Lighting's help pages, current as of grandMA3 v2.5 (November 2026):

- [grandMA3: Calculate the number of parameters](https://help.malighting.com/grandMA3/2.5/HTML/system_parameter_calculate.html)
- [grandMA3: Expand the number of parameters](https://help.malighting.com/grandMA3/2.5/HTML/system_parameter_expand.html)
- [grandMA2: Parameter expansion](https://help.malighting.com/grandMA2/en/help/key_so_parameter_expansion.html)

Assumptions where the docs are silent:

- grandMA3 processing units (M, L, XL) in a grandMA2 session count as an NPU (4,096 each).
- grandMA3 processing unit L adds 8,192 with a grandMA3 console.
- grandMA3 compact, compact XT, replay unit and CRV models follow console rules: only the biggest console counts.

Always confirm the real number in System Info on the desk.

## Problems

Wrong count or missing hardware? [Open an issue](https://github.com/jkoffman/MAgiCalc/issues).

---

Josh's MAgical Calculator is an independent tool. It is not affiliated with or endorsed by MA Lighting. grandMA2 and grandMA3 are trademarks of MA Lighting Technology GmbH.
