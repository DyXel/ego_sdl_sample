project('ego_sdl_sample', 'cpp', default_options : 'cpp_std=c++17')

ego_dep = dependency('ego', fallback : ['ego', 'ego_dep'])
sdl_dep = dependency('sdl2')
sdl_image_dep = dependency('SDL2_image')

ego_sdl_sample_src = files([
	'src/main.cpp',
	'src/sdl_utility.cpp',
	'src/game_instance.cpp'
])

ego_sdl_sample_exe = executable('ego_sdl_sample', ego_sdl_sample_src, dependencies : [ego_dep, sdl_dep, sdl_image_dep], gui_app : true)
