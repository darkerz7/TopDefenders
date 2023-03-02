## topdefenders_perk
### TopDefenders, TopInfectors, Perks, built-in Downloadlist, Show Damage (Current damage, Kills, Total damage), Show Infect (Nickname victim, Total infected), Store Integration. 
### Perk - Trail/Sprite/Model, Add Speed, Reduced Gravity, immunity to first infection and more

### Top Defenders Config
```
- Configure perk/HUD position/Hud colors in addons\sourcemod\configs\topdefenders.cfg
- Built-in Downloadlist in addons\sourcemod\configs\topdefenders_downloadlist.ini
- You can configure a few perks per place(only one of the type), see ConfigFile
- In order to integrate the shop you must uncomment #define SHOP and configure function names SHOP_SET_CREDITS_FUNC(Shop_SetClientCredits) and SHOP_GET_CREDITS_FUNC(Shop_GetClientCredits)
```
Cvar | Parameter | Description
--- | --- | ---
`sm_topdefenders_enable` | <0/1> | Enable/Disable plugin
`sm_topdefenders_topcount` | <3/15> | Number of top defenders to display
`sm_topdefenders_perk` | <0/1> | Enable top defender perks
`sm_topdefenders_cashdiv` | <0/50> | Money for damage - Damage divider (Cash=Cash+Damage/Divider) 0 - Disable
`sm_topdefenders_infectors_enable` | <0/1> | Enable Top Infector Addon
`sm_topdefenders_infectors_topcount` | <3/15> | Number of people to top Infector
`sm_topdefenders_infectors_perk` | <0/1> | Gives Infector perk for the top Infector
`sm_topdefenders_immunity_chance` | <0/100> | Сhance of immunity from infection if prescribed in the configuration file
`sm_topdefenders_immunity_minplayers` | <10/64> | Minimum players for immunity
`sm_topdefenders_showdamage` | <0/1> | Enable/Disable Show Hint Damage Addon

Admin Command | Description
--- | ---
`sm_topdefenders_config_test1` | Test Config Top Defenders
`sm_topdefenders_config_test2` | Test Config Top Infectors
`sm_topdefenders_refresh` | Refresh Config without show

Client Command | Description
--- | ---
`sm_pr` | Remove Perk from yourself
