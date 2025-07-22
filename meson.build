# Root Meson Build File

# Base project import
project( 'linux-device-driver', 'cpp', meson_version: '>=1.5' )

# Import dependencies here

# Define include directory
inc = [ include_directories( 'include' ) ]

# Import Meson.builds from subdirectories - these usually contain source definitions
subdir( 'src' )
subdir( 'test' )
subdir( 'include' )

# Define final output executable(s)
executable( 'linux-device-driver',
            [ sources ],
            include_directories: inc#,
            # dependencies: [ <Insert whatever libraries this project depends on here> ]
 )