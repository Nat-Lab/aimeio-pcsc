aimeio_lib = shared_library(
    'aimeio',
    name_prefix : '',
    include_directories: inc,
    implicit_include_directories : false,
    vs_module_defs : 'aimeio.def',
    link_with: [aimepcsc_lib],
    sources : [
        'aimeio.c',
    ],
)
