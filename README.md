# Building Procedure

We encourge you to follow this general guide when building in Roblox Studio.
This guide's purpose is to create the best practices and workflow for all team members to work together with ease.

## General:
- Anything that a Script requires access to should be easy to find within the **[Explorer](https://user-images.githubusercontent.com/55673217/110210189-13bfee00-7ec3-11eb-95ef-3e2c6d74804f.png)**
- [Disable Shift lock](https://user-images.githubusercontent.com/55673217/110210274-75805800-7ec3-11eb-8328-355c477006d8.png)
- Never allow players to zoom out and see behind a map, breaking their immersion
- **Never Use Terrain**

## Naming Conventions:
- Never use abbverations, names should always be [Verbose](https://dictionary.cambridge.org/dictionary/english/verbose)
- Names must not include special characters. ie "Left Door" should be named as "LeftDoor"
## Scriptables:
- Model must have a [PrimaryPart called "Root"](https://user-images.githubusercontent.com/55673217/110210457-64841680-7ec4-11eb-9717-7fa827c12672.png)
- Model's PrimaryPart must be facing Forward [as you can see the Hinge](https://user-images.githubusercontent.com/55673217/110210567-d0667f00-7ec4-11eb-8397-1794ebc6a46d.png) is pointing Forward

## Organization:
Rule of thumb: If you can't find a specific asset within 10 seconds in Explorer you have a problem
- Group assets and parts together in folders. Attempt to group them at the smallest,
yet reasonable level possible (A folder for a room is good. An individual folder for
every part in a room is not).
- In general, group interior builds (ex. inside a house, spaceship) according to rooms;
group exterior builds (islands, villages, parks) according to distinctive areas of the
map.
- [Example 1](https://user-images.githubusercontent.com/55673217/110210612-0441a480-7ec5-11eb-8c1f-a50b214e61c0.png), [Example 2](https://user-images.githubusercontent.com/55673217/110210677-54b90200-7ec5-11eb-953e-b153858aa4e3.png)

## Automation:

## Colors and Lighting:
**Building style: Low poly, cartoony, saturated bright and cheerful**
- In 99% of cases, use [smooth plastic material](https://user-images.githubusercontent.com/55673217/110210876-52a37300-7ec6-11eb-8d4c-c71deff6d7c9.png)
- Disable [Part.CastShadow](https://user-images.githubusercontent.com/55673217/110210856-30115a00-7ec6-11eb-90fa-7f42d295165e.png) (unless explicitly appropriate)
- Always use [Voxel technology](https://user-images.githubusercontent.com/55673217/110210800-f04a7280-7ec5-11eb-9345-1157b0dc5ee3.png) for lighting (unless stated otherwise)
- Never let lighting/lack of lighting affect the dynamicism of parts

## Do's:
- Always use high ceilings (high enough that players’ head cannot really collide it when
jumping). Exceptions given to areas designed to be small, such as air vents or tiny
tunnels.
- Always use [Snap To Grid](https://user-images.githubusercontent.com/55673217/110211019-250af980-7ec7-11eb-9255-72edd8d8f1f2.png)

## Don't s:
- Never build whole maps in [Blender](https://www.blender.org/). Small 3D assets are fine.
- [Nerver allow Z-Fighting](https://en.wikipedia.org/wiki/Z-fighting)
- Nerver allow walls, ceilings, and floors to be thinner than 2 studs
- Nerver allow players’ head to clip into walls, ceilings, floors, or objects
- Nerver allow gaps in Builds

## Collection Tags:
[Collection Tag Editor](https://devforum.roblox.com/t/tag-editor-plugin/)
- Invisible
- Collision
- Interactable
- Lights

## Before Publishing:
- Make sure to [Playtest](https://user-images.githubusercontent.com/55673217/110210916-a3b36700-7ec6-11eb-8304-bbae85ba57f5.png) EVERYTHING 
- Make sure to [Anchor](https://user-images.githubusercontent.com/55673217/110210944-d65d5f80-7ec6-11eb-931e-a37d2dcfdb85.png) EVERYTHING

## Plugins:
- [Collection Tag Editor](https://devforum.roblox.com/t/tag-editor-plugin/)