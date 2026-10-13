# Garden City Wahala

A Call of Duty–style wave-survival shooter set at Mile 1 in Port Harcourt. It runs in the browser from one HTML file on Three.js r128, which loads from cdnjs. All the sounds are synthesised, so there are no asset files.

**Play:** open `index.html` in a browser (or serve the folder, e.g. `npx serve .`), choose a side and click **Deploy**.

## Sides
| | Police officer | Axe man |
| --- | --- | --- |
| Mission | Hold Mile 1 junction against Axe Men who have taken the market | Hold the waterside against a police and MOPOL raid |
| Weapons | AK-47, pump action, FN FAL with scope | AK-47, pump action, Dane gun |
| Melee (V) | Baton | Axe (one-hit kill) |
| Throwable (G) | Frag grenade | Petrol bomb (leaves a fire zone) |
| 3-kill streak | Police helicopter: shows every enemy on the minimap | Lookout boys: shows every enemy on the minimap |
| 5-kill streak (4) | Tear gas volley: enemies in the cloud choke, can't shoot and can't see through it | Petrol bomb barrage |

Enemies fight back. Officers throw tear gas, Axe Men throw petrol bombs, and both rush in for melee when you get close.

## The map
Ikwerre Road and Market Road cross at a police checkpoint. Around the junction are the Mile 1 market stalls, God's Grace Hotel, Mama Ibiba's bole-and-fish kitchen, a filling station, kekes, a broken-down bus and waterside zinc shacks along the creek. A gas flare burns on the horizon. Diesel drums explode when shot.

## Controls
| Action | Key |
| --- | --- |
| Move | W A S D |
| Fire / Aim | Left / right mouse button |
| Sprint | Shift |
| Jump | Space |
| Crouch | C |
| Reload | R |
| Melee | V |
| Throw | G |
| Switch weapon | 1 / 2 / 3, Q, mouse wheel |
| Killstreak | 4 |
| Pause | Esc |

Touchscreens get an on-screen stick and buttons.

## Graphics settings
Pick **Low, Medium, High or Ultra** on the main menu or the pause screen. The game remembers your choice. Phones start on Medium and computers on High. If the frame rate drops, the game suggests a lower setting.

| | Low | Medium | High | Ultra |
| --- | --- | --- | --- | --- |
| Render scale | 0.75× | 1× | up to 1.5× | up to 2× |
| Sun shadows | off | 1024 | 2048 soft | 4096 soft |
| Bloom glow, colour grade, film grain, hit fringing | off | off | on | on |
| Multisample anti-aliasing | | | | on (WebGL 2) |

Every setting also gets sky reflections on all surfaces, moving clouds, a rippling creek, textured walls, zinc roofs and roads, brass casings and dust in the air.
