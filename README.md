> [!CAUTION]
> The rig below is old, clunky, and unmaintained.
> It is a fallback in case the other two rigs do not work.
>
> I do not recommend using this for animation.

<details><summary>[ OLDEST ] Mewtwo Scarlet/Violet Rig \[ Blender 3.6+ \]</summary><p>

# \[ OLDEST \] Mewtwo Scarlet/Violet Rig \[ Blender 3.6+ \]

| Simple controls | Shiny toggle | Posable face | Simple face controls |
| --- | --- | --- | --- |
| ![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/89876cb5-d07e-4c06-873c-67295c312607) | ![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/820de701-e114-4cfd-94e9-019adcc35ae1) | ![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/fbd33c42-542f-4409-9bef-a67bfab55270) | ![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/7caf557c-fbef-4ead-914e-38b53d5a352e) |

</p></details>

---

# \[ OLD \] Mewtwo Scarlet/Violet Rigify Rig \[ Blender 3.6+ \]

![controls](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/2f710355-cdf7-4ab4-b4cc-4e7b2a22a1e5)

> [!TIP]
> The Rigify addon needs to be enabled to use this rig.
> 
> Run the script included in this rig's .blend to enable its UI

### Similar to the old rig but with many more controls to make it easier to animate.

## You can change the colors of the model.

The color settings are hidden by default, slide the top slider to Shiny, then slide the Custom slider to reveal the Color sliders, ranging from 0 to 1 instead of 0 to 255. Negative and large numbers can result in weird colors

| Example | Result |
| --- | --- |
| ![customcoloring1](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/5f6258ae-9064-47f3-9fe9-05a076af65d2) | ![customcoloring2](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/86f82dee-0789-4400-9490-14b3e1e6b046) |

---

# \[ NEW \] Mewtwo Scarlet/Violet Rigify Ragdoll Rig \[ Blender 3.6+ \]

![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/3ed7faa1-c3c3-45cd-8e7c-3be0a0dd0b70)

> [!TIP]
> The Rigify addon needs to be enabled to use this rig.
> 
> Run the script included in this rig's .blend to enable its UI

### Only a few changes make it different from the previous Rigify rig.

Changes:
* Tweak and FK bones are hidden by default to reduce clutter.
* The head controller is no longer points towards an "IK" bone as it was creating issues. Head can now be controlled by a large yellow FK control.

New features:
* An animatable Ragdoll. Using the custom UI in the Rigify side panel, you can turn on/off the model's ragdoll.
* Shader-based eyes. This allows you to have fine control over the eyes during animation and are customizable in the Shader Editor.

> [!TIP]
> If you want to throw Mewtwo at something, make sure to turn on the ragdoll right before the rig stops moving during the launch sequence.
> Otherwise mewtwo will not gain any momentum and just drop to the ground.
>
> **This applies for any motion you want to be part of the ragdoll**

> [!WARNING]
> If you have IK Stretch enabled and stretch the arms or legs of the rig before going into a ragdoll, it might result in strange ragdoll behaviour.
> I recommend leaving this setting at 0.0 if you don't want to run into any issues while ragdolling.
> 
> ![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/f9c8e322-ec99-463a-a49d-64f5ea94d037)

| Ragdoll UI | Shader-based eyes for more artistic control |
| --- | --- |
| ![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/378ba09b-4955-4fa5-bc6e-3fff4f00f002) | ![image](https://github.com/Hectoris919/Mewtwo-SV-Rig-Blender/assets/47396668/14f1312a-ce7b-4951-819f-96151956ce46) |

