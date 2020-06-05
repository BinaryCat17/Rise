project('RiSignals', 'cpp', default_options : ['cpp_std=c++17'])

thread_dep = dependency('threads')
RiSignals_deps = [threads_dep]
RiSignals_inc = include_directories('include')
RiSignals_lib = library('RiSignals_lib', srs/signals.cpp)
RiSignals_dep = declare_dependency(link_with: RiSignals_lib,
    include_directories : RiSignals_inc, dependencies : RiSignals_deps)
