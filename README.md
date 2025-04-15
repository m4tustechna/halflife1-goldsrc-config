Folders valve and valve_WON should be extracted/copied and overwrite files in /GoldSrc Package 2.4/Half-Life WON

Added map : Bunny race (/valve/maps/bunnyrace_beta2.bsp)
Player model : Astolfo, visible via thirdperson command (/valve/models/player.mdl)

Personal saves : (/valve/SAVE/*.sav)
- aSTART.sav (Save from where the test chamber explodes the door, the game finally opens up for bhoping)
- bunnyrace.sav (Upon launching game, loads this save because main menu is bugged and the only navigation is binds or console commands)

Configuration file with binds (/valve_WON/userconfig.cfg)
exec WON.cfg // Don't remove this
bxt_hud_incorrect_fps_indicator 0
bind z "fps_max 20"
bind x "fps_max 100"
bind capslock "fps_max 4"
bind y "fps_max 23"
bind v "save quick"
bind b "load quick"
bind l "load autosave"
bind p "map c1a0;bxt_hud_timer 1;bxt_timer_reset;bxt_timer_start;bxt_autorecord run"
bind o "load aSTART;bxt_hud_timer 1;bxt_timer_reset;bxt_timer_start;bxt_autorecord run"
bind f1 "gl_texturemode GL_NEAREST_MIPMAP_NEAREST"
bind f2 "gl_texturemode GL_LINEAR_MIPMAP_LINEAR"
bind c "-duck"
bind mwheeldown +jump
default_fov 130
bxt_hud_jumpspeed 1
cl_bob 0
gl_spriteblend 0
cl_showfps 1
hud_fastswitch 1
gl_texturemode GL_NEAREST_MIPMAP_NEAREST
load bunnyrace;bxt_hud_timer 1;bxt_timer_reset
bxt_bhopcap 0

Nothing special, just configuration files so i can download them anywhere anytime...
All sources are available online, i am not a owner of the bunnyrace or astolfo model 

Bunnyrace : https://wiki.sourceruns.org/wiki/Bunnyrace_beta2
Astolfo Playermodel : https://gamebanana.com/mods/167249
