project('Rise', 'cpp', default_options : ['cpp_std=c++17'])

engine_dep = dependency('RiEngine', fallback: ['RiEngine', 'RiEngine_dep'])
signals_dep = dependency('RiSignals', fallback: ['RiSignals', 'RiSignals_dep'])
util_dep = dependency('RiUtil', fallback: ['RiUtil', 'RiUtil_dep'])
window_dep = dependency('RiWindow', fallback: ['RiWindow', 'RiWindow_dep'])
Rise_deps = [engine_dep, signals_dep, util_dep, window_dep]
Rise_dep = declare_dependency(dependencies : Rise_deps)
