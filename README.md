# Agents for Lunar Client
My agents for lunar-client, best used with [lunar-client-qt](https://github.com/Youded-byte/lunar-client-qt).

## LunarAccurateReachDisplay
This agent removes the cap of 3.0 reach in the reach display mod included in lunar client. This cap is unnecesarry and even misleading, as on rare occasions a hit can be landed at a slightly larger distance. This agent also removes the rounding of reach if the decimal ends with a zero, e.g. 0.00 being rounded to 0, as it can be unwanted for the size of the box to change frequently. You can pass the option/argument "round" in order for the agent not to change the rounding system.

## NickHiderLimitless
Allows you to give yourself any custom NickHider username by passing it as an option/argument. Colour codes can be passed but must be passed for example by using "&4" instead of "§4". Also removes restrictions on what custom NickHider name you can add inside of the game.

## LunarPerformance
This agent applies patches to Minecraft and surrounding mods in order to increase performance.

## LunarBetterHurtCam
Allows changing of hurt animation modifier, changing how much the user's camera moves after the player being hurt.
[LunarBetterHurtCam](https://github.com/Youded-byte/LunarBetterHurtCam) is included in my fork of [lunar-client-qt](https://github.com/Youded-byte/lunar-client-qt) and is therefore not included in this repo.

## FastPlace
This agent changes the delay between block placement when right click his held to 0, meaning every tick a new block will be placed, or an egg thrown.
[FastPlace](https://github.com/Youded-byte/FastPlace-Agent) is not included in this repo because it is considered a cheat on many servers. You can download it from it's own repo.
