# Generated file; do not modify.
generated_sources += custom_target(
    'org/freedesktop/UPower/Device__cpp'.underscorify(),
    input: [ '../../../../../yaml/org/freedesktop/UPower/Device.interface.yaml',  ],
    output: [ 'server.cpp', 'server.hpp', 'client.hpp',  ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'cpp',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'org/freedesktop/UPower/Device',
    ],
)

