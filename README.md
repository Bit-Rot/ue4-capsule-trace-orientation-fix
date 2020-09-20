# ue4-capsule-trace-orientation-fix
A fix for UE4's capsule trace functions, which don't include orientation as a parameter (unlike box trace)

It's just a copy paste of the engine code, but I've added orientation as a parameter.

Note that you'll need to replace the ATROPHY_API macro to match your project's settings.
