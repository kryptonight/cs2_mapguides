# CS2 Mapguides by woe

Extract the cfg and annotations folders into %STEAM%\steamapps\common\Counter-Strike Global Offensive\game\csgo

example: C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo

Add "exec woe_praccmode.cfg" to your autoexec cfg file

Use the mapguides_help / mg_help command in-game for an overview of commands like this:

# In-Game Commands
* woe_guide(s) / woe_mapguides / mapguides_help / mg_help - Load this list
* mapguides_on / mg_on - Turn Map Guides (annotations) ON
* mapguides_off / mg_off - Turn Map Guides (annotations) OFF
* prac / pracc / pracc_mode / prac_mode / smoke - Load Pracc CFG
* prac_MapName / pracc_MapName - Load Pracc cfg AND Map annotations / Map Guides
* go_MapName - Create Local Server on X Map (ex. go_inf or go_inferno)
  
..................................................................................
* util_rethrow		- Rethrow Last Util
* util_drop			- Drop all util
* util_buy			- Buy all util
* util_get			- Buy all util
* util_rethrow		- Rethrow Last Util
* util_molly		- Get Molotov
  
..........................................
* local_rr / l_rr	- mp_restartgame 1
* rcon_rr / r_rr 	- rcon mp_restartgame 1


## Load annotation file ("Map Guides")
* woe_overpass / woe_op
* woe_inferno / woe_inf
* woe_train
* woe_dust2 / woe_d2
* woe_nuke
* woe_ancient / woe_anc
* woe_anubis
* woe_vertigo / woe_vert
* woe_mirage / woe_mir


## THE IN-BUILT IN-ENGINE COMMANDS TO MAKE MAP GUIDES

* sv_allow_annotations TRUE
* annotation_load TITLE (
* annotation_save TITLE
* annotation_append TITLE
* annotation_create grenade LABEL
* annotation_create position LABEL
* annotation_create text TITLE DESCRIPTION float
* annotation_create text TITLE DESCRIPTION surface
* annotation_create spot
* annotation_create line float new
* annotation_create line surface new
* workshop_annotation_submit
* -
* annotation folder structure:
* \annotations\local\filename\filename.txt
