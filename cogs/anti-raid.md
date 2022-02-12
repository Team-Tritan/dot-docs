# **Anti-Raid**
Dot's anti-raid module is filled with commands and functions to help safe guard your server from anything malicious.

- You need to set a alt/raider role for antiraid to use. Run `antiraid altrole [role]

|   Command | Description   | Usage   | Notes | Command Aliases
| ------------ | ------------ | ------------ | ------------ |  ------------ | 
|antialt   | When running this command, dot will configure the actions taken on alt accounts.  |  .antialt [0-3] | If you run this command with no number as an argument, it will show you what options you can use.|  N/A
|  minage  | Sets the minimum account age for the anti-alt system.   |  .minage [number of days] | This command is required for the alt-detector to work. | age
| defaultpfp | Configures the anti-raid system to ignore or take action on accounts with a default avatar. | .defaultpfp [true/false] | The anti-alt config action will be executed on all new joins with a default profile pic. | pfp
| altrole | Configures the role to be given to possible alt accounts on detection. | .altrole [role mention] | Please note that this configuration **needs** to be set for the anti-raid module to work properly. | role, raiderrole 
