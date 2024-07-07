file(
    GLOB
    source_files
    CONFIGURE_DEPENDS
    "*.cpp"
    "*.hpp"
)

target_sources(
    ${CMAKE_PROJECT_NAME}
    PUBLIC
    ${source_files}
)
