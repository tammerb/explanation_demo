add_executable(explanation_demo_test src/explanation_demo_test.cpp)

target_link_libraries(explanation_demo_test ${catkin_LIBRARIES} ${Boost_LIBRARIES})
install(TARGETS explanation_demo_test DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
