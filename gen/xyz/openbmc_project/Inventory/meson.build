# Generated file; do not modify.
generated_sources += custom_target(
    'xyz/openbmc_project/Inventory__cpp'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Inventory.errors.yaml',  ],
    output: [ 'error.cpp', 'error.hpp',  ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'cpp',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Inventory',
    ],
)

subdir('Connector')
subdir('Decorator')
subdir('Item')
generated_others += custom_target(
    'xyz/openbmc_project/Inventory/Item__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Inventory/Item.interface.yaml',  ],
    output: [ 'Item.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Inventory/Item',
    ],
)

subdir('Manager')
generated_others += custom_target(
    'xyz/openbmc_project/Inventory/Manager__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Inventory/Manager.interface.yaml',  ],
    output: [ 'Manager.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Inventory/Manager',
    ],
)

subdir('Source')
