# Generated file; do not modify.
subdir('Entry')
subdir('LicenseManager')
generated_others += custom_target(
    'com/ibm/License/LicenseManager__markdown'.underscorify(),
    input: [ '../../../../yaml/com/ibm/License/LicenseManager.interface.yaml',  ],
    output: [ 'LicenseManager.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/ibm/License/LicenseManager',
    ],
)

