#idf_component_register(SRCS "ethernet_connect.c"
#                    INCLUDE_DIRS "include")
                    
# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS "src/ModbusMaster.cpp"
)
set(COMPONENT_ADD_INCLUDEDIRS "src" 
							  "../arduino/cores/esp32"		
							  "../arduino/tools/sdk/include/spi_flash"					
							  "../arduino/variants/esp32"					
							
							)

register_component()                    
                    