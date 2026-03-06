
set(SimpleThreshold_SOURCE SimpleThreshold.cxx)
GENERATECLP(SimpleThreshold_SOURCE SimpleThreshold.xml)


add_executable(SimpleThreshold_${yuamiao} ${SimpleThreshold_SOURCE})
target_link_libraries(SimpleThreshold_${yuamiao} ${ITK_LIBRARIES})
