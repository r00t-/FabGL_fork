idf_component_register(
	SRCS "canvas.cpp" "codepages.cpp" "collisiondetector.cpp" "devdrivers/DS3231.cpp" "devdrivers/MCP23S17.cpp" "devdrivers/keyboard.cpp" "devdrivers/mouse.cpp" "devdrivers/kbdlayouts.cpp" "dispdrivers/SSD1306Controller.cpp" "dispdrivers/TFTControllerSpecif.cpp" "dispdrivers/TFTControllerGeneric.cpp" "displaycontroller.cpp" "fabfonts.cpp" "fabui.cpp" "fabutils.cpp" "network/ICMP.cpp" "network/netutils.cpp" "scene.cpp" "terminal.cpp" "terminfo.cpp"
	INCLUDE_DIRS "."
	#REQUIRES arduino
	REQUIRES esp_wifi driver esp_timer fatfs esp_http_client spiffs
)
