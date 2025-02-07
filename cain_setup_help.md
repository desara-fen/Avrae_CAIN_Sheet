This alias setups the necessary information for you to be able to use `!cain` and its other subaliases.
> **Note**: Before running this alias, you need to `!import` a character through Avrae since it will attach the information to that particular character. For this, you can make a copy of this [modified gsheet](https://docs.google.com/spreadsheets/d/1gMU3bz5iyONDCOcNyYuYLpztb_8RdL6GaI50PhUkTq0/edit?usp=sharing) that has both the typical Avrae Gsheet information (v1.14) and a few tabs for your CAIN character taken from <@465192139987615765>'s [v1 CAIN Character Gsheet](https://discord.com/channels/426286410496999425/1277789952817627136/1277789952817627136). The necessary fields for the sheet to be valid in Avrae have already been filled out.
** **
**Full Syntax:**
```!cain setup -exorname <exorcist_name> -xid <xid> -name <actual_name> -agenda <agenda> -blasphemy <blasphemy> -sx <exorcist_sex> -height <height> -weight <weight> -hair <hair> -eyes <eyes> -cat <category> -psyche <current_psyche> -sin <current_sin> -sincap <sin_cap> -agony <divine_agony> -stress <current_stress> -stresscap <stress_cap> -kp <current_kp> -xp <current_xp> -xpcap <xp_cap> -advances <advancements> -scrip <current_scrip> [retain]```
** **
All flag arguments are optional, but if you enter none, the alias will output that you've done no edits.
** **
Adding `retain` to the alias will make the resulting embed stay. Otherwise, it will disappear in 1 minute.
** **
**Flag Arguments:**
Here's a breakdown of each and what the alias will expect of them.
> **Note:** Enclose multiple words in quotation marks and do not use said quotation marks in the input. The arguments below will be separated based on whether they take a string (`str`) or an integer (`int`). If you input anything other than an integer in the integer arguments, you WILL get an error you cannot blame me for.
** **
__String Arguments__
*You can put practically anything here as long as they're enclosed in quotes and don't contain quotes.*
- `-exorname` - exorcist name
- `-xid` - exorcist ID number
- `-name` - exorcist's actual name
- `-agenda` - exorcist's  registered agenda
- `-blasphemy` - exorcist's blasphemy
- `-sex` - self explanatory
- `-height` - self explanatory
- `-weight` - self explanatory
- `-hair` - hair color
- `-eyes` - eye color
- `-virtue` - the virtue your exorcist follows, if any
** **
__Integer Arguments__
*Numbers only.*
- `-cat` - category
- `-psyche` - your current amount of psyche blasts
- `-sin` - your current amount of sin
- `-sincap` - your sin cap; defaults to 10 but you're given the option to edit it here in case you've taken an additional blasphemy
- `-agony` - your current amount of divine agony
- `-stress` - your current amount of stress
- `-stresscap` - your current stress cap, or the amount of stress you can take before taking an injury
- `-injury` - your current amount of injuries
- `-kp` - your current kit points
- `-kpcap` - your maximum amount of kit points
- `-xp` - your current XP
- `-xpcap` - your current XP cap; defaults to 4, but you can also modify it
- `-advances` - your advances
- `-scrip` - your current amount of scrip
