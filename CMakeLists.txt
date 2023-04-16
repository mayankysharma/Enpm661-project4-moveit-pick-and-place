add_executable(pick_place_tutorial src/pick_place_tutorial.cpp)
add_executable(pick_place_custom src/pick_place_custom.cpp)

target_link_libraries(pick_place_tutorial ${catkin_LIBRARIES} ${Boost_LIBRARIES})
target_link_libraries(pick_place_custom ${catkin_LIBRARIES} ${Boost_LIBRARIES})

install(TARGETS pick_place_tutorial DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
