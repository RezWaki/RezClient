# RezClient
*v1.0 beta*
  RezClient is Half-Life client.dll oriented on multiplayer gaming
  * Commands:
    cl_autojump - [1/0] - Integrated autojump on SPACEBAR key 
    
    cl_doubleduck - [1/0] - Integrated doubleduck on SHIFT key, works faster than doubleduck script
    
    cl_drawteams - [1/0] - Draws teamnames & scores out of scoreboard, if teamplay mode, like in AG
    
      cl_drawteamscores - [1/0] - Enable/disable scores in cl_drawteams
    
    cl_speedometer - [1/0] - Buggy speedometer, probably will be fixed in next version
    
    cl_hudcolor - ["r g b a"]~[cl_hudcolor "0 150 255 255"] - Sets hud color
    
    cl_scrbrd_r/g/b/a - [0-255]~[cl_scrbrd_r 255;cl_scrbrd_g 0;cl_scrbrd_b 0;cl_scrbrd_a 200] - Sets scoreboard background color
    
    cl_specwh - [1/0] - WallHack for **SPECTATORS ONLY**, it woudln't work if you are NOT spectator now

  * Installation instructions
  Download latest RezClient version from https://github.com/RezWaki/RezClient/releases unpack into your "valve" folder

  * Compilation instructions
  Download HLSDK v2.3, then get cl_dll folder from "source_code" & copy it to "src_dll" folder, accept replace, now just open HLSDK v2.3 in VisualStudio & compile client part
