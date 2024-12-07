//================================================\\
            //* COUNTER STRIKE 2 *\\
//================================================\\

// SETTINGS
sensitivity 2.15
zoom_sensitivity_ratio 0.8
r_fullscreen_gamma "2.1"
rate 1000000
cl_allow_animated_avatars "0"
cl_hud_color "3"
cl_use_opens_buy_menu "0"
cl_color "4"
cl_crosshair_sniper_width 2
cl_player_ping_mute 1
cl_sniper_auto_rezoom 1
cl_teammate_colors_show 1
cl_use_opens_buy_menu 0
cl_showloadout 1
cl_teamcounter_playercount_instead_of_avatars 1
engine_low_latency_sleep_after_client_tick 1
r_show_build_info "0"
cl_obs_interp_enable 0
con_enable 1 
cl_crosshair_recoil false
cl_debounce_zoom 0
fps_max 											"0"
Developer                                           "1"
Con_Enable                                          "1"
voice_modenable	0

//Jump Throw + W Jump Throw
alias "+jumpaction" "+jump;"
alias "+throwaction" "-attack; -attack2"
alias "-jumpaction" "-jump"
bind "," "+jumpaction;+throwaction;"

alias "+runthrow" "+forward;+jump;"
alias "-runthrow" "-jump;-forward"
bind "." "+runthrow;+throwaction"

//Movement Keys
bind "a" "+left"
bind "d" "+right" 
bind "w" "+forward" 
bind "s" "+back"  
bind "ctrl" "+duck" 
bind "shift" "+sprint" 
bind "mwheelup" "+jump"; bind "space" "+jump"


//Unbinds
unbind "alt"
unbind "mouse4"
unbind "k"
unbind "m"
unbind "p"
unbind "i"
unbind "z"
unbind "/"
unbind "f1"
unbind "f2"
unbind "f3"
unbind "f4"
unbind "f5"


//Binds
bind "mouse3" "toggle cl_crosshairsize 999 0"
bind "1" "slot1"
bind "2" "slot2"
bind "3" "slot3"
bind "4" "slot4"
bind "5" "slot5"
bind "6" "viewmodel_offset_y 2; viewmodel_fov 68"
bind "7" "toggle viewmodel_presetpos 3 1"
bind "b" "buymenu"
bind "c" "toggle cl_righthand 0 1"
bind "e" "+use"
bind "f" "+lookatweapon"
bind "g" "drop"
bind "h" "noclip"
bind "l" "+spray_menu"
bind "n" "+voicerecord"
bind "o" "give weapon_flashbang; give weapon_molotov;give weapon_hegrenade; give weapon_smokegrenade;give weapon_ak47"
bind "q" "lastinv"
bind "r" "+reload"
bind "u" "messagemode2"
bind "v" "toggle cl_radar_scale 1 0.3"
bind "x" "player_ping"
bind "y" "messagemode"
bind "[" "+radialradio"
bind "]" "+radialradio2"
bind "`" "toggleconsole"
bind "\" "teammenu"
bind "TAB" "+showscores"
bind "ESCAPE" "cancelselect"
bind "DEL" "mute"
bind "PAUSE" "pause"


//* radar settings *\\
cl_radar_always_centered 				"1"
cl_radar_scale 							"0.7"
cl_hud_radar_scale 						"1.15"
cl_radar_icon_scale_min 				"0.6"
cl_radar_square_with_scoreboard  		"1" 
cl_radar_rotate 						"1"

//==================================================\\
            //* Crosshair Settings *\\
//==================================================\\
// Crosshair code: CSGO-LOGp2-BquMU-tYQcs-98cDk-XqtiB
CrossHair       					 "1" //*Enable Crosshair
Cl_CrossHairAlpha 					"255" //*Crosshair 100% Visible / Enable Crosshair
cl_crosshair_drawoutline 				"1"
cl_crosshair_dynamic_maxdist_splitratio 		            "0.35"
cl_crosshair_dynamic_splitalpha_innermod 		            "1"
cl_crosshair_dynamic_splitalpha_outermod 		            "0.5"
cl_crosshair_dynamic_splitdist 				"5"
cl_crosshair_outlinethickness 				"0.5"
cl_crosshaircolor 					"1"
cl_crosshaircolor_b 					"255"
cl_crosshaircolor_g 					"60"
cl_crosshaircolor_r 					"255"
cl_crosshairdot 					"0"
cl_crosshairgap 					"-10"
cl_crosshairgap_useweaponvalue 				"0"
cl_crosshairsize 					"3.17"
cl_crosshairstyle 					"4"
cl_crosshairthickness 					"0.75"
cl_crosshairusealpha 					"1"
cl_fixedcrosshairgap 					"3"


        //*~~~~~~~~~~~~~~*\\
        //* THIS IS WORKING *\\
//alias _checkw "-forward; alias checkw"; alias +w "+forward; alias checkw _checkw"; alias -w "checkw"; bind w +w
//alias _checks "-back; alias checks"; alias +s "+back; alias checks _checks"; alias -s "checks"; bind s +s
//alias _checka "-left; alias checka"; alias +a "+left; alias checka _checka"; alias -a "checka"; bind a +a
//alias _checkd "-right; alias checkd"; alias +d "+right; alias checkd _checkd"; alias -d "checkd"; bind d +d

//* ShowFPS*\\
cl_showfps       "0"

//* ViewModel Settings*\\
// viewmodel 1
// viewmodel_offset_x 0
// viewmodel_offset_y 2
// viewmodel_offset_z 0
// viewmodel_fov 1

// viewmodel 2
viewmodel_fov 68
viewmodel_offset_x 2.2
viewmodel_offset_y 2
viewmodel_offset_z -2
viewmodel_presetpos 0

// viewmodel 3
//viewmodel_fov "68"
//viewmodel_offset_x "1"
//viewmodel_offset_y "2"
//viewmodel_offset_z "-1"
//viewmodel_presetpos "0"

//* HUD *\\
//* Default is 0. more info when mouse over enemy player *\\
hud_showtargetid 1 
hud_scaling 1
cl_hud_color 8
cl_showloadout 1
safezonex 1
safezoney 1

//* Bunnyhop *\\
//bind "mwheelup" "+jump"; bind "space" "+jump"
