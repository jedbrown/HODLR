foreach(TARGET 
        tutorial 
        example 
        example_RPY 
        example_matern 
        example_conducting_sphere_plate
       )

  add_executable(${TARGET} 
                 ${TARGET}.cpp
                 ${HODLRlib_SRCS}
                )

endforeach()
