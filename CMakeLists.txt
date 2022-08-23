if(CONFIG_LCZ_LWM2M_PRESSURE)
    zephyr_include_directories(include)
    zephyr_sources(source/lcz_lwm2m_pressure.c)
endif()