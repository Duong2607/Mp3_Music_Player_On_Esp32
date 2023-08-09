# set(COMPONENT_SRCS "DACOutput.cpp")
# set(app_src input_iot.c)
set(pri_req)
idf_component_register(SRCS "esp_spiffs.cpp" "SPIFFS.cpp"
                    INCLUDE_DIRS "."
                    REQUIRES ${pri_req})
# register_component()
