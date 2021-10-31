project(
    'fmt',
    'cpp',
    version : '8.0.1',
    license: 'MIT',
    default_options : [
        'cpp_std=c++17',
    ]
)

inc = include_directories('include')
src = files(
    'src/format.cc',
    'src/os.cc',
)
lib = library('fmt', src, include_directories : inc)

fmt_dep = declare_dependency(include_directories : inc, link_with : lib)
