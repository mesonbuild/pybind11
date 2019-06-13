project('pybind11', 'cpp', default_options : ['cpp_std=c++11'], license : 'BSD-style', version : '2.3.0')

py3_dep = dependency('python3')

pybind11_incdir = include_directories('include')

pybind11_dep = declare_dependency(
	include_directories : pybind11_incdir,
	dependencies : py3_dep
)
