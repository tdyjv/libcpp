project('libc', 'c')

inc = include_directories('../../../../arm-tools-dev/arm-none-eabi/include/',is_system : true)

libc_compile_flags = '-nostdinc'

libc_dep = declare_dependency(include_directories : inc, compile_args : libc_compile_flags)
