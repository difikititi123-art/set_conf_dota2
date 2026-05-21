# set_conf_dota2
готовые натсройки игра с 47000 часов в дота 2 настроено 

авто экзе (будет в релизе в рар)

dota_health_hurt_decay_time_max 0
dota_health_hurt_decay_time_min 0
dota_health_hurt_delay 0
dota_pain_decay 0
dota_pain_factor 0
dota_pain_multiplier 0
команды для хп
bind "kp_multiply" "disconnect"
dota_friendly_color 255 255 0
dota_enemy_color 255 0 255
dota_minimap_creep_scale 1.3
dota_minimap_rune_size 500
dota_health_hurt_threshold 1
dota_health_marker_minor_alpha 160
dota_health_marker_major_alpha 255
//Полоска ХП уменьшается сразу, а не с задержкой.
dota_health_hurt_decay_time_max 0
dota_health_hurt_decay_time_min 0
dota_health_hurt_delay 0
dota_pain_decay 0
dota_pain_factor 0
dota_pain_multiplier 0

//Поднятие FPS (Интернет)
rate 80000
cl_updaterate 40
cl_cmdrate 40
cl_interp 0.05
cl_interp_ratio 1
cl_smoothtime 0

//Поднятие FPS (Ухудшает графику в целях поднятия FPS)
dota_cheap_water 1
cl_globallight_shadow_mode 0
r_deferrer 0
r_deferred_height_fog 0
r_screenspace_aa 0
gpu_level 0
cpu_level 0
r_deferred_specular 0
r_deferred_specular_bloom 0
dota_portrait_animate 0
r_deferred_additive_pass 0
r_deferred_simple_light 0
r_renderoverlayfragment 0
r_shadowrendertotexture 0
r_WaterDrawReflection 0
r_ssao 0
mat_picmip 2
mat_vsync 0
mat_triplebuffered 0
rate 80000
cl_cmdrate 31
cl_interp 0.01
cl_interp_ratio 1
cl_lagcompensation 1
cl_pred_optimize 2
cl_smooth 1
cl_smoothtime 0.01
cl_updaterate 31
cl_spectator_cmdrate_factor 0.5
cl_spectator_interp_ratio 2
dota_set_avatar 9
dota_force_right_click_attack 1
dota_minimap_hero_size 500
dota_embers 0
dota_disable_range_finder 0
developer 0
dota_hud_healthbars 3
dota_sf_game_end_delay 0
glow_outline_effect_enable 0
-softparticlesdefaultoff - отключает мягкие частицы
-r_drawparticles 0 - отключает рендеринг частиц в игре
-dota_embers 0 - Отключает отображение эмберов (маленьких частиц огня, искр)
-engine_low_latency_sleep_after_client_tick 1 - уменьшаяет инпутлаг
+mat_hdr_level 0 - отключает HDR
-noaafonts - отключает сглаживание шрифтов
-heapsize 20000000 - аперативка (в байтах)
+cl_clock_recvmargin_enable 0 (настройка соурс-движка, управляет механизмом компенсации задержек синхронизации времени между клиентом и сервером) (вкл - стабильная картинка при нестабильном инете, выкл - меньше дилея
(выключать ток при норм инете))
+dota_health_hurt_threshold 0 (процент здоровься при котором экран начинает мигать красным (от 0 до 100))

-mapdota (прогружает карту в момент захода в игру(доту а не катку), если вас не загружает в первую игру и вы лутаете лп)
-limitvsconst 0 (задает предел на число вершинных шейдеров
-cursor_scale_percent 450 (размер курсора)
-autoconfig
cl_cq_min_queue 0 (чем лучше инет тем меньше значение ставить(уменьшает инпутлаг), если есть профризы из за хуевого инета ставишь значение 1\2 (индивидуально), сгладит эти проблемы)
-condebug - логирование консольных сообщений(сохраняет весь консольный текст в файл console.log) для выявления багов\лагов.



параметры запуска используеться минифу он есть в репозиторе https://github.com/difikititi123-art/Minify
-exe autoexec.cfg +fps_max 0 -novid -high -prewarm -map dota -console -el_clock_recmargin_enable 0 -language russian
