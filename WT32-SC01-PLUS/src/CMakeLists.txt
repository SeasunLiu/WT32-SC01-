SET(SOURCES screens/ui_MainScreen.c
    screens/ui_OptionsScreen.c
    screens/ui_WiFiScreen.c
    screens/ui_LocationScreen.c
    screens/ui_BrightnessScreen.c
    screens/ui_RadioScreen.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_bg3_png.c
    images/ui_img_optionsbtn_png.c
    images/ui_img_pinpoint_png.c
    images/ui_img_clear_sky_png.c
    images/ui_img_temphum_png.c
    images/ui_img_rain_png.c
    images/ui_img_thunderstorm_png.c
    images/ui_img_ligth_rain_png.c
    images/ui_img_fog_png.c
    images/ui_img_1041181811.c
    images/ui_img_brokencloudsimg_png.c
    images/ui_img_wifioffimg_png.c
    images/ui_img_wifionimg_png.c
    images/ui_img_backimg_png.c
    images/ui_img_wifi_handshakeimg_png.c
    images/ui_img_playbuttonimg_png.c
    images/ui_img_stopbuttonimg_png.c)

add_library(ui ${SOURCES})
