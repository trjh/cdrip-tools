import platform
macports_env = Environment(
    CPPPATH=['/opt/local/include'],
    LIBPATH=['/opt/local/lib'],
    )
default_env = Environment()
default_env = macports_env

default_env.Program('ckcdda', ['ckcdda.c'],
                    CCFLAGS='-O2 -ggdb -std=c99 -Wall')
default_env.Program('splitaudio', ['splitaudio.c'],
                    CCFLAGS='-O2 -ggdb -std=c99 -Wall',
                    LIBS=['sndfile'])
