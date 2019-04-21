# Half Life 1 SDK LICENSE
Half Life 1 SDK Copyright(c) Valve Corp.  

THIS DOCUMENT DESCRIBES A CONTRACT BETWEEN YOU AND VALVE CORPORATION (“Valve”).  PLEASE READ IT BEFORE DOWNLOADING OR USING THE HALF LIFE 1 SDK (“SDK”). BY DOWNLOADING AND/OR USING THE SOURCE ENGINE SDK YOU ACCEPT THIS LICENSE. IF YOU DO NOT AGREE TO THE TERMS OF THIS LICENSE PLEASE DON’T DOWNLOAD OR USE THE SDK.

You may, free of charge, download and use the SDK to develop a modified Valve game running on the Half-Life engine.  You may distribute your modified Valve game in source and object code form, but only for free. Terms of use for Valve games are found in the Steam Subscriber Agreement located here: http://store.steampowered.com/subscriber_agreement/ 

You may copy, modify, and distribute the SDK and any modifications you make to the SDK in source and object code form, but only for free.  Any distribution of this SDK must include this license.txt and third_party_licenses.txt.  
 
Any distribution of the SDK or a substantial portion of the SDK must include the above copyright notice and the following: 

DISCLAIMER OF WARRANTIES.  THE SOURCE SDK AND ANY OTHER MATERIAL DOWNLOADED BY LICENSEE IS PROVIDED “AS IS”.  VALVE AND ITS SUPPLIERS DISCLAIM ALL WARRANTIES WITH RESPECT TO THE SDK, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, IMPLIED WARRANTIES OF MERCHANTABILITY, NON-INFRINGEMENT, TITLE AND FITNESS FOR A PARTICULAR PURPOSE.  

LIMITATION OF LIABILITY.  IN NO EVENT SHALL VALVE OR ITS SUPPLIERS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF BUSINESS PROFITS, BUSINESS INTERRUPTION, LOSS OF BUSINESS INFORMATION, OR ANY OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR INABILITY TO USE THE ENGINE AND/OR THE SDK, EVEN IF VALVE HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  

If you would like to use the SDK for a commercial purpose, please contact Valve at sourceengine@valvesoftware.com.

# Half-Life Classic
This mod ports features from Retail to the Steam version and adds new ones. Also works on Xash3D.
## Features
1. Weapon Switch

 `hud_fastswitch [0,1,2]`
 * 0 is off (Always open menu)
 * 1 is default fastswitch (Mouse wheel opens menu, Keys switch)
 * 2 is fixed fastswitch (Both wheel and keys switch)
 
2. View Roll

 `cl_rollangle [0-?]`
 `cl_rollspeed [0-?]`
 
3. Weapon Bob

 `cl_bobold [0, 1]`
 
4. Hud layout

 `hud_layout [0,1,2,3]`
 * 0 is default
 * 1 is inverted
 * 2 is centered
 * 3 is unreal
 
5. HUD color

 `hud_color_[r, g, b] [0-255]`
 
6. Removing hud bars

 `hud_bars [0,1]`
 
7. Disabling hud transparency

 `hud_alpha [0,1]`
