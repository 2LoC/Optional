project('optional', 'cpp',
    license : 'boost',
    meson_version : '>0.42.0',
    default_options : ['cpp_std=c++11'])

# Dependency
optional = declare_dependency(include_directories : [ '.' ])
install_headers('optional.hpp', install_dir : 'optional')

test_optional = executable('test_optional', [ 'test_optional.cpp' ])
test_type_traits = executable('test_type_traits', [ 'test_type_traits.cpp' ])

test('test optional', test_optional)
test('test type_traits', test_type_traits)
