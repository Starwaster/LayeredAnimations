LayeredAnimations
=================

Adds layers to KSP's ModuleAnimateGeneric

When to use:
If you have multiple animations on a single part, give each one a unique layer ID.

Example: Porkjet's Centrifuge habitat does not work properly because playing one animation cancels another.
This is bad if you start the habitat spinning because then it deflates and Kerbals cannot board and eat snacks.

SOLUTION: If Porkjet replaces his animation modules with the following code, everything works! Hurray!

MODULE
{
