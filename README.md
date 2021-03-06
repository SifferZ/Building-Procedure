# Building Procedure

We encourge you to follow this general guide when building in Roblox Studio.
This guide's purpose is to create the best practices and workflow for all team members to work together with ease.

## General:
- Anything that a Script requires access to should be easy to find within the **Explorer**
- Disable Shift lock
- Never allow players to zoom out and see behind a map, breaking their immersion
- **Never Use Terrain**

## Naming Conventions:
- Never use abbverations, names should always be [Verbose](https://dictionary.cambridge.org/dictionary/english/verbose)
- Rule of thumb: If you can't find a specific asset within 10 seconds in Explorer you have a problem

## Scriptables:

## Organization:
- Group assets and parts together in folders. Attempt to group them at the smallest,
yet reasonable level possible (A folder for a room is good. An individual folder for
every part in a room is not).
- In general, group interior builds (ex. inside a house, spaceship) according to rooms;
group exterior builds (islands, villages, parks) according to distinctive areas of the
map.

## Automation:

## Colors and Lighting:
- **Building style: Low poly, cartoony, saturated bright and cheerful**
- In 99% of cases, use smooth plastic material
- Disable [Part.CastShadow](https://developer.roblox.com/en-us/api-reference/property/BasePart/CastShadow) (unless explicitly appropriate)
- Always use [Voxel technology](https://developer.roblox.com/en-us/api-reference/enum/Technology) for lighting (unless stated otherwise)
- Never let lighting/lack of lighting affect the dynamicism of parts

## Do's:
- Always use high ceilings (high enough that players’ head cannot really collide it when
jumping). Exceptions given to areas designed to be small, such as air vents or tiny
tunnels.
- Always use gridlock

## Don't s:
- Never build whole maps in [Blender](https://www.blender.org/). Small 3D assets are fine.
- [Nerver allow Z-Fighting](https://en.wikipedia.org/wiki/Z-fighting)
- Nerver allow walls, ceilings, and floors to be thinner than 2 studs
- Nerver allow players’ head to clip into walls, ceilings, floors, or objects
- Nerver allow gaps in Builds

## Collection Tags:
## Before Publishing:
- Make sure to Playtest EVERYTHING
- Make sure to Anchor EVERYTHING

## Plugins:
- [Collection Tag Editor](https://devforum.roblox.com/t/tag-editor-plugin/)