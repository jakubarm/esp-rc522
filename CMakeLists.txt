idf_component_register(
    SRCS "rc522.c"
    INCLUDE_DIRS "."
    REQUIRES
        driver
        esp_timer
)