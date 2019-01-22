================================================================

This code should compile fine (albeit with many trivial warnings) under
Visual Studio 2017 in 64 or 32-bit.

I haven't tested the makefiles, this codebase is based on the original 2001
3.21 version of the source code (which is newer than the 3.19 release available on
Id's own Github!) so you may need to make some minor changes to compile for anything
other than Windows.

I've made minimal changes to the code, id386 is no longer defined when targeting
64-bits, which means 32-bit ASM functions use their Unix equivalents.

Added support for a variety of modern common resolutions.

================================================================

This is the complete source code for Quake 2, version 3.21, buildable with
visual C++ 6.0.  The linux version should be buildable, but we haven't
tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license).  
You should read the entire license, but the gist of it is that you can do 
anything you want with the code, including sell your new version.  The catch 
is that if you distribute new binary versions, you are required to make the 
entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational 
purposes, but the GPL does allow commercial exploitation if you obey the 
full license.  If you want to do something commercial and you just can't bear 
to have your source changes released, we could still negotiate a separate 
license agreement (for $$$), but I would encourage you to just live with the 
GPL.

All of the Q2 data files remain copyrighted and licensed under the 
original terms, so you cannot redistribute data from the original game, but if 
you do a true total conversion, you can create a standalone game based on 
this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack
Id Software

