# mushroom-prop
A FiveM emissive mushroom prop for scripts, animations, and maps.


![image](https://user-images.githubusercontent.com/119994243/219803078-1bcab539-5f14-4b15-9d52-e09c5a737a2d.png)

[Preview](https://streamable.com/i1uohx_

Streamed prop for GTA FiveM - includes inventory image.

> Original Model by : [rabbiturnal](https://sketchfab.com/rabbiturnal) used under [CC 4.0 License](https://creativecommons.org/licenses/by/4.0/), changes include collision mesh addition embedded textures, scaling, and slight mesh adjustments. 

Emote demonstrated with rpemotes by [TayMcKenzieNZ](https://github.com/TayMcKenzieNZ/rpemotes) 
Emote adapting the prop to add to AnimationListCustom.lua (I'm sure there's a better animation this just works for me):
>    ["mushroom"] = { --- Prop by Bostra
        "mp_player_inteat@burger",
        "mp_player_int_eat_burger",
        "Mushroom",
        AnimationOptions = {
            Prop = 'mushroom',
            PropBone = 60309,
            PropPlacement = {
                0.000,
                0.0300,
                -0.0700,
                60.0000,
                0.0000,
                1.0000
            },
            EmoteMoving = true
        }
    },

