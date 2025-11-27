# Atmosphere Utilities v0.2
 
Atmosphere Utilites can now specify where and at what altitude oxygen is present on a planet.
 
# Current Features:
 
1) Can edit specific heights of an atmosphere to have oxygen or not.
2) Custom patches (see below for syntax)
3) Oxygen masks to specify where on the planet oxygen is present or not. !!HAS TO BE A .PNG FILE!!
 
# Current Problems:
 
1) If the atmosphere is too hot or not dense enough kerbals cannot breathe.
 
# Syntax:
 
    @AtmosphereUtilities
    {
        Body
        {
            name = MyCoolPlanet // Planet name
 
            breatheableAreaTexture = MyCoolMod/Textures/PluginData/MyCoolOxygenMask // Oxygen mask path
 
            oxygenThreshold = 0 // Minimum oxygen "value" to make oxygen present.
 
            lower = 15000 // Lower bound of breatheable layer
            upper = 25000 // Upper bound of breatheable layer
 
            warnUpper = 14900 // Altitude of which the warnUpperMessage will be played
            warnLower = 24900 // Altitude of which the warnUpperMessage will be played
 
            warnUpperMessage = Reaching upper bound of breatheable layer!
            warnLowerMessage = Reaching lower bound of breatheable layer!
        }
    }
 
 
# Download:
 
Github: https://github.com/plantman-dev/AtmosphereUtilites.git
Spacedock: https://spacedock.info/mod/4047/Atmosphere%20Utilities
 
# DIscord
https://discord.gg/nwnJdqb9VY
