# qb-driftmode
Toggle drift mode on qb-core FiveM

## Build for qb-core (resmon: 0.00ms)
- <a href="https://github.com/qbcore-framework">qb-core | GitHub</a>
- <a href="https://discord.gg/qbcore">qb-core | Discord</a>

### More stuff from me 💜
- <a href="https://www.youtube.com/user/mtacstolk/videos">StolK88 | YouTube</a>
- <a href="https://stolk.tebex.io/category/qb-scripts-by-stolk">StolK88 | Tebex</a>

## README!!
1. Add the lines below to you're qb-radialmenu/config.lua
```
{
  id = 'driftmode',
  title = 'Drift mode',
  icon = 'car-side',
  type = 'client',
  event = 'qbdriftmode:DriftMode',
  shouldClose = true
},
```

It should look something like:
```
                    }, {
                        id = 'extra12',
                        title = 'Extra 12',
                        icon = 'box-open',
                        type = 'client',
                        event = 'qb-radialmenu:client:setExtra',
                        shouldClose = false
                    }, {
                        id = 'extra13',
                        title = 'Extra 13',
                        icon = 'box-open',
                        type = 'client',
                        event = 'qb-radialmenu:client:setExtra',
                        shouldClose = false
                    }
                }
            }, {
                id = 'driftmodus',
                title = 'Drift modus',
                icon = 'car-side',
                type = 'client',
                event = 'qbdriftmode:DriftMode',
                shouldClose = true
            },
```

# Disclaimer
Use at your own risk

With ❤ from StolK


# Licence
2022 StolK

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>
