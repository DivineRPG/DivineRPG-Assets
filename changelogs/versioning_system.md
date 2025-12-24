## DivineRPG versioning

**This Document defines the standard for DivineRPG version numbers as of December 24th 2025, after the release of 1.10.9.3**

A version is released as **Alpha**, **Beta** or **Release**, can have a **Name** and contains a maximum of 4 number segments: "**x.x.x.x**",
of which the first segment contains the highest order number and the last the lowest order.
Whenever a higher order number changes, it sets all trailing numbers to zero.
Trailing zeroes are left out, so for example 1.4.0.0 would be trimmed to **1.4**


**The first number defines the iteration**

With the first release it is set to **1** and only changes if the mod gets a complete rewrite and reimagination or gets a release for a different game than Minecraft.
Such a scenario is not likely to happen and thus the number will stay as **1** for the forseeable future.


**The second number defines a functional version set**

An update between versions with the same first and second number is meant to be simply executed by swapping out the file of the old update with the new one.
Whenever further action is required to update, like changing the minecraft version or requiring a new world to be created, the second version number changes.


**The third number describes a content release**

A change in the third version number is usually accompanied by a name similar to "*The --- Update*".
Whenever new content gets added or the new version contains some substantial changes, this number should change.


**The fourth number is for fixes and minor changes**

This segment is for hotfixes and new releases that only contain minor tweaks and changes.
Such updates do not require a name.


A version is released as **Alpha**, if it is missing some essential function and is deemed as "**not working**".
If an alpha release is not compatible with old worlds, it does not require a version number change of second order.

**Beta** is for versions interpreted as "**working, but not complete**"

**Release** is for "**complete**" versions.



Here is a list of old versions released before Dec 24th 2025 with "-- Xxxx x.x.x.x", when they would be different, had they used the new system:
("I will probably update and improve this at some point" - velocityraptor)

Minecraft 1.21.1:
- Release 1.10.9.3 -- Release 1.13.10.1
- Release 1.10.9.2 -- Release 1.13.10
- Release 1.10.9.1 -- Release 1.13.9.1
- Release 1.10.9   -- Release 1.13.9
- Release 1.10.8.4.2 -- Release 1.13.8.2
- Release 1.10.8.4.1 -- Release 1.13.8.1
- Release 1.10.8.4 -- Release 1.13.8
- Release 1.10.8.3 -- Release 1.13.7
- Beta    1.10.8.2 -- Beta 1.13.6.2
- Beta    1.10.8.1 -- Beta 1.13.6.1
- Beta    1.10.8   -- Beta 1.13 (maybe 1.12 or even 1.11)

Minecraft 1.20.1
- Release 1.10.7.6 -- Release 1.12.5.2
- Beta    1.10.7.5 -- Beta 1.12.5.1
- Beta    1.10.7.4 -- Beta 1.12.5
- Beta    1.10.7.3 -- Beta 1.12.4.1
- Beta    1.10.7.2 -- Beta 1.12.4
- Beta    1.10.7.1 -- Beta 1.12.3.1
- Beta    1.10.7   -- Beta 1.12.3
- Beta    1.10.6.1 -- Beta 1.12.2.1
- Beta    1.10.6   -- Beta 1.12.2
- Beta    1.10.5   -- Beta 1.12.1
- Beta    1.10.4   -- Beta 1.12 (maybe 1.11 or even 1.10)

Minecraft 1.19.4:
- Beta    1.10.3   -- Beta 1.11.2
- Beta    1.10.2   -- Beta 1.11.1
- Beta    1.10.1   -- Beta 1.11.0.1
- Beta    1.10.0   -- Beta 1.11 (maybe 1.10 or even 1.9)

Minecraft 1.19.3:
- Beta    1.10.0.2
- Beta    1.10.0.1
- Beta    1.9.7    -- Beta 1.10 (maybe 1.9 or even 1.8)

Minecraft 1.19.2:
- Beta    1.9.6.11 -- Beta 1.9.5.8
- Beta    1.9.6.10 -- Beta 1.9.5.7
- Beta    1.9.6.9  -- Beta 1.9.5.6
- Beta    1.9.6.8  -- Beta 1.9.5.5
- Beta    1.9.6.7  -- Beta 1.9.5.4
- Beta    1.9.6.6  -- Beta 1.9.5.3
- Beta    1.9.6.5  -- Beta 1.9.5.2
- Beta    1.9.6.4  -- Beta 1.9.5.1
- Beta    1.9.6.3  -- Beta 1.9.5
- Beta    1.9.6.2  -- Beta 1.9.4.2
- Beta    1.9.6.1  -- Beta 1.9.4.1
- Beta    1.9.6    -- Beta 1.9.4
- Beta    1.9.5    -- Beta 1.9.3.2
- Beta    1.9.4    -- Beta 1.9.3.1
- Beta    1.9.3
- Beta    1.9.2
- Beta    1.9.1
- Beta    1.9      -- (maybe 1.8 or even 1.7)

Minecraft 1.16.5:
- Release 1.8.27   -- Beta 1.8.5.21
- Beta    1.8.26   -- Beta 1.8.5.20
- Beta    1.8.25   -- Beta 1.8.5.19
- Beta    1.8.24   -- Beta 1.8.5.18
- Beta    1.8.23   -- Beta 1.8.5.17
- Beta    1.8.22   -- Beta 1.8.5.16
- Beta    1.8.21   -- Beta 1.8.5.15
- Beta    1.8.20   -- Beta 1.8.5.14
- Beta    1.8.19   -- Beta 1.8.5.13
- Beta    1.8.18   -- Beta 1.8.5.12
- Beta    1.8.17   -- Beta 1.8.5.11
- Beta    1.8.16   -- Beta 1.8.5.10
- Beta    1.8.15   -- Beta 1.8.5.9
- Beta    1.8.14   -- Beta 1.8.5.8
- Beta    1.8.13   -- Beta 1.8.5.7
- Beta    1.8.12   -- Beta 1.8.5.6
- Beta    1.8.11   -- Beta 1.8.5.5
- Beta    1.8.10   -- Beta 1.8.5.4
- Beta    1.8.9    -- Beta 1.8.5.3
- Beta    1.8.8    -- Beta 1.8.5.2
- Beta    1.8.7    -- Beta 1.8.5.1
- Beta    1.8.6    -- Beta 1.8.5
- Beta    1.8.5    -- Beta 1.8.4.1
- Beta    1.8.4
- Beta    1.8.3
- Beta    1.8.2
- Beta    1.8.1
- Beta    1.8      -- (maybe 1.7 or even 1.6)

Minecraft 1.12.2 - classic versions:
- Release 1.7.1
- Release 1.7      -- (maybe 1.6.7 or even 1.5.10... should check updating from 1.6.4.1)
- Beta    1.6.4.1  -- Beta 1.6.6
- Beta    1.6.4    -- Beta 1.6.5
- Release 1.6.3.1  -- Release 1.6.4.1
- Beta    1.6.3    -- Beta 1.6.4
- Beta    1.6.2.1  -- Beta 1.6.3.1
- Beta    1.6.2    -- Beta 1.6.3
- Beta    1.6.1    -- Beta 1.6.2
- Beta    1.6.0.2  -- Beta 1.6.1
- Beta    1.6.0.1
- Beta    1.6      -- (maybe 1.5.3... should check updating from 1.5.2)
- Beta    1.5.2
- Beta    1.5.1    -- Beta 1.5.1.1
- Beta    1.5      -- Beta 1.5.1
- Beta 1.12.2.0.21b-- Beta 1.5.0.22
- Beta 1.12.2.0.21 -- Beta 1.5.0.21
- Beta   1.12.2.0  -- Beta 1.5

Minecraft 1.7.10 - legacy versions:
- Release 1.4.2.3
- Release 1.4.2.1  -- Release 1.4.2.2
- Release 1.4.2    -- Release 1.4.2.1
- Release 1.4.1.5  -- Release 1.4.2
- Beta    1.4.1.4
- Release 1.4.0.5

Minecraft 1.4.7 - retro versions:
- Release 1.3.0.4

Minecraft 1.4.5:
- v1.1             -- Release 1.2

Minecraft 1.4.2:
- 1.1.6            -- 1.1.1
- 1.1.5            -- 1.1

Minecraft 1.3.2:
- 1.1.4            -- 1.0.4
- 1.1.3            -- 1.0.3
- 1.1.2            -- 1.0.2
