include_directories(../libcore)
add_executable(cgview main.cpp)

target_link_libraries(cgview core ${QT_QTCORE_LIBRARY} ${QT_QTGUI_LIBRARY} ${QT_QT3SUPPORT_LIBRARY})

# do not install example code...
# install(TARGETS cgview ${INSTALL_TARGETS_DEFAULT_ARGS} )
