# Atmosphere Utilities
Atmosphere Utilities is a custom plugin made for KSP planets.
It allows planet modders to specify which parts of an atmosphere can be breatheable within a custom height threshold.

# Current Features:

1) Can edit specific heights of an atmosphere to have oxygen or not.
2) Custom patches (see below for syntax)

# Current Problems:

1) If the atmosphere is too hot or not dense enough kerbals cannot breathe.

# Syntax:

    @AtmosphereUtilities
    {
        Body
        {
            name = MyCoolPlanet // 
            lower = 3000 // Lower bopund of breatheable atmosphere
            upper = 26000 // Upper bound of bretheable atmopshere
        }
    }

# Download:
