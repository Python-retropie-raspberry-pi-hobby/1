Here is the log file:
```
Log started at: Sun Dec 27 13:27:40 EST 2020

RetroPie-Setup version: 4.7.2 (ac8d8775)
System: rpi4 (aarch64) - Raspbian GNU/Linux 10 (buster) - Linux retropie 5.4.79-v8+ #1373 SMP PREEMPT Mon Nov 23 13:32:41 GMT 2020 aarch64 GNU/Linux

= = = = = = = = = = = = = = = = = = = = =
Installing dependencies for 'lr-dolphin' : Gamecube/Wii emulator - Dolphin port for libretro
= = = = = = = = = = = = = = = = = = = = =

/home/pi/RetroPie-Setup/tmp/build/lr-dolphin /home/pi

= = = = = = = = = = = = = = = = = = = = =
Getting sources for 'lr-dolphin' : Gamecube/Wii emulator - Dolphin port for libretro
= = = = = = = = = = = = = = = = = = = = =

git clone --recursive --depth 1 --branch master "https://github.com/libretro/dolphin" "/home/pi/RetroPie-Setup/tmp/build/lr-dolphin"
Cloning into '/home/pi/RetroPie-Setup/tmp/build/lr-dolphin'...
Checking out files:  62% (3913/6300)   
Checking out files:  63% (3969/6300)   
Checking out files:  64% (4032/6300)   
Checking out files:  65% (4095/6300)   
Checking out files:  66% (4158/6300)   
Checking out files:  67% (4221/6300)   
Checking out files:  68% (4284/6300)   
Checking out files:  69% (4347/6300)   
Checking out files:  70% (4410/6300)   
Checking out files:  71% (4473/6300)   
Checking out files:  72% (4536/6300)   
Checking out files:  73% (4599/6300)   
Checking out files:  74% (4662/6300)   
Checking out files:  75% (4725/6300)   
Checking out files:  76% (4788/6300)   
Checking out files:  77% (4851/6300)   
Checking out files:  78% (4914/6300)   
Checking out files:  79% (4977/6300)   
Checking out files:  80% (5040/6300)   
Checking out files:  81% (5103/6300)   
Checking out files:  82% (5166/6300)   
Checking out files:  83% (5229/6300)   
Checking out files:  84% (5292/6300)   
Checking out files:  85% (5355/6300)   
Checking out files:  86% (5418/6300)   
Checking out files:  87% (5481/6300)   
Checking out files:  88% (5544/6300)   
Checking out files:  89% (5607/6300)   
Checking out files:  90% (5670/6300)   
Checking out files:  91% (5733/6300)   
Checking out files:  92% (5796/6300)   
Checking out files:  93% (5859/6300)   
Checking out files:  94% (5922/6300)   
Checking out files:  95% (5985/6300)   
Checking out files:  96% (6048/6300)   
Checking out files:  97% (6111/6300)   
Checking out files:  98% (6174/6300)   
Checking out files:  99% (6237/6300)   
Checking out files: 100% (6300/6300)   
Checking out files: 100% (6300/6300), done.
Submodule 'Externals/Qt' (https://github.com/dolphin-emu/ext-win-qt.git) registered for path 'Externals/Qt'
Cloning into '/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/Qt'...
Submodule path 'Externals/Qt': checked out '5ab31b5fdf1cdc59b9e8c82a0f7c12d5fe878cd8'
HEAD is now in branch 'master' at commit 'a2afe5334bef76b8a6e0f7807ebdc074ac11fe2d'
/home/pi
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin /home/pi

= = = = = = = = = = = = = = = = = = = = =
Building 'lr-dolphin' : Gamecube/Wii emulator - Dolphin port for libretro
= = = = = = = = = = = = = = = = = = = = =

-- The C compiler identification is GNU 8.3.0
-- The CXX compiler identification is GNU 8.3.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found Git: /usr/bin/git (found version "2.20.1") 
-- Detected architecture: aarch64
-- Performing Test FLAG_C_HAVE_ARCH_ARMV8
-- Performing Test FLAG_C_HAVE_ARCH_ARMV8 - Success
-- Performing Test FLAG_CXX_HAVE_ARCH_ARMV8
-- Performing Test FLAG_CXX_HAVE_ARCH_ARMV8 - Success
-- Performing Test FLAG_C_HAVE_WALL
-- Performing Test FLAG_C_HAVE_WALL - Success
-- Performing Test FLAG_CXX_HAVE_WALL
-- Performing Test FLAG_CXX_HAVE_WALL - Success
-- Performing Test FLAG_C_TYPE_LIMITS
-- Performing Test FLAG_C_TYPE_LIMITS - Success
-- Performing Test FLAG_CXX_TYPE_LIMITS
-- Performing Test FLAG_CXX_TYPE_LIMITS - Success
-- Performing Test FLAG_C_SIGN_COMPARE
-- Performing Test FLAG_C_SIGN_COMPARE - Success
-- Performing Test FLAG_CXX_SIGN_COMPARE
-- Performing Test FLAG_CXX_SIGN_COMPARE - Success
-- Performing Test FLAG_C_IGNORED_QUALIFIERS
-- Performing Test FLAG_C_IGNORED_QUALIFIERS - Success
-- Performing Test FLAG_CXX_IGNORED_QUALIFIERS
-- Performing Test FLAG_CXX_IGNORED_QUALIFIERS - Success
-- Performing Test FLAG_C_UNINITIALIZED
-- Performing Test FLAG_C_UNINITIALIZED - Success
-- Performing Test FLAG_CXX_UNINITIALIZED
-- Performing Test FLAG_CXX_UNINITIALIZED - Success
-- Performing Test FLAG_C_LOGICAL_OP
-- Performing Test FLAG_C_LOGICAL_OP - Success
-- Performing Test FLAG_CXX_LOGICAL_OP
-- Performing Test FLAG_CXX_LOGICAL_OP - Success
-- Performing Test FLAG_C_SHADOW
-- Performing Test FLAG_C_SHADOW - Success
-- Performing Test FLAG_CXX_SHADOW
-- Performing Test FLAG_CXX_SHADOW - Success
-- Performing Test FLAG_C_INIT_SELF
-- Performing Test FLAG_C_INIT_SELF - Success
-- Performing Test FLAG_CXX_INIT_SELF
-- Performing Test FLAG_CXX_INIT_SELF - Success
-- Performing Test FLAG_C_MISSING_DECLARATIONS
-- Performing Test FLAG_C_MISSING_DECLARATIONS - Success
-- Performing Test FLAG_CXX_MISSING_DECLARATIONS
-- Performing Test FLAG_CXX_MISSING_DECLARATIONS - Success
-- Performing Test FLAG_C_MISSING_VARIABLE_DECLARATIONS
-- Performing Test FLAG_C_MISSING_VARIABLE_DECLARATIONS - Failed
-- Performing Test FLAG_CXX_MISSING_VARIABLE_DECLARATIONS
-- Performing Test FLAG_CXX_MISSING_VARIABLE_DECLARATIONS - Failed
-- Performing Test FLAG_C_NO_STRICT_ALIASING
-- Performing Test FLAG_C_NO_STRICT_ALIASING - Success
-- Performing Test FLAG_CXX_NO_STRICT_ALIASING
-- Performing Test FLAG_CXX_NO_STRICT_ALIASING - Success
-- Performing Test FLAG_C_NO_EXCEPTIONS
-- Performing Test FLAG_C_NO_EXCEPTIONS - Success
-- Performing Test FLAG_CXX_NO_EXCEPTIONS
-- Performing Test FLAG_CXX_NO_EXCEPTIONS - Success
-- Performing Test FLAG_C_VISIBILITY_INLINES_HIDDEN
-- Performing Test FLAG_C_VISIBILITY_INLINES_HIDDEN - Failed
-- Performing Test FLAG_CXX_VISIBILITY_INLINES_HIDDEN
-- Performing Test FLAG_CXX_VISIBILITY_INLINES_HIDDEN - Success
-- Performing Test FLAG_C_VISIBILITY_HIDDEN
-- Performing Test FLAG_C_VISIBILITY_HIDDEN - Success
-- Performing Test FLAG_CXX_VISIBILITY_HIDDEN
-- Performing Test FLAG_CXX_VISIBILITY_HIDDEN - Success
-- Performing Test FLAG_C_FOMIT_FRAME_POINTER
-- Performing Test FLAG_C_FOMIT_FRAME_POINTER - Success
-- Performing Test FLAG_CXX_FOMIT_FRAME_POINTER
-- Performing Test FLAG_CXX_FOMIT_FRAME_POINTER - Success
-- Performing Test FLAG_C_GGDB
-- Performing Test FLAG_C_GGDB - Success
-- Performing Test FLAG_CXX_GGDB
-- Performing Test FLAG_CXX_GGDB - Success
-- Looking for pthread.h
-- Looking for pthread.h - found
-- Looking for pthread_create
-- Looking for pthread_create - not found
-- Looking for pthread_create in pthreads
-- Looking for pthread_create in pthreads - not found
-- Looking for pthread_create in pthread
-- Looking for pthread_create in pthread - found
-- Found Threads: TRUE  
-- Performing Test FLAG_C_FPIC
-- Performing Test FLAG_C_FPIC - Success
-- Performing Test FLAG_CXX_FPIC
-- Performing Test FLAG_CXX_FPIC - Success
-- Found PkgConfig: /usr/bin/pkg-config (found version "0.29") 
-- Found OpenGL: /usr/lib/arm-linux-gnueabihf/libGL.so   
-- Looking for XOpenDisplay in /usr/lib/arm-linux-gnueabihf/libX11.so;/usr/lib/arm-linux-gnueabihf/libXext.so
-- Looking for XOpenDisplay in /usr/lib/arm-linux-gnueabihf/libX11.so;/usr/lib/arm-linux-gnueabihf/libXext.so - found
-- Looking for gethostbyname
-- Looking for gethostbyname - found
-- Looking for connect
-- Looking for connect - found
-- Looking for remove
-- Looking for remove - found
-- Looking for shmat
-- Looking for shmat - found
-- Looking for IceConnectionNumber in ICE
-- Looking for IceConnectionNumber in ICE - found
-- Found X11: /usr/lib/arm-linux-gnueabihf/libX11.so
-- Xrandr found
-- Checking for module 'xi>=1.5.0'
--   Found xi, version 1.7.9
-- X11 support enabled
-- Checking for module 'egl'
--   Found egl, version 1.5
-- Found EGL: /usr/include  
-- EGL OpenGL interface enabled
-- Found LIBUDEV: /lib/arm-linux-gnueabihf/libudev.so  
-- Found libevdev: /usr/lib/arm-linux-gnueabihf/libevdev.so  
-- libevdev/libudev found, enabling evdev controller backend
-- Using named pipes as controller inputs
-- Watching game memory for changes
-- Performing Test FLAG_C_CXX11
-- Performing Test FLAG_C_CXX11 - Failed
-- Performing Test FLAG_CXX_CXX11
-- Performing Test FLAG_CXX_CXX11 - Success
CMake Warning at CMakeLists.txt:553 (find_package):
  By not providing "Findfmt.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "fmt", but
  CMake did not find one.

  Could not find a package configuration file provided by "fmt" (requested
  version 6.0) with any of the following names:

    fmtConfig.cmake
    fmt-config.cmake

  Add the installation prefix of "fmt" to CMAKE_PREFIX_PATH or set "fmt_DIR"
  to a directory containing one of the above files.  If "fmt" provides a
  separate development package or SDK, be sure it has been installed.


-- Using static fmt from Externals
-- Version: 6.1.2
-- Build type: Release
-- CXX_STANDARD: 11
-- Performing Test has_std_11_flag
-- Performing Test has_std_11_flag - Success
-- Performing Test has_std_0x_flag
-- Performing Test has_std_0x_flag - Success
-- Performing Test SUPPORTS_VARIADIC_TEMPLATES
-- Performing Test SUPPORTS_VARIADIC_TEMPLATES - Success
-- Performing Test SUPPORTS_USER_DEFINED_LITERALS
-- Performing Test SUPPORTS_USER_DEFINED_LITERALS - Success
-- Performing Test FMT_HAS_VARIANT
-- Performing Test FMT_HAS_VARIANT - Success
-- Looking for strtod_l
-- Looking for strtod_l - not found
-- Could NOT find pugixml (missing: pugixml_LIBRARIES pugixml_INCLUDE_DIRS) 
-- Using static pugixml from Externals
-- Using static enet from Externals
-- Looking for fcntl
-- Looking for fcntl - found
-- Looking for poll
-- Looking for poll - found
-- Looking for getaddrinfo
-- Looking for getaddrinfo - found
-- Looking for getnameinfo
-- Looking for getnameinfo - found
-- Looking for gethostbyname_r
-- Looking for gethostbyname_r - found
-- Looking for gethostbyaddr_r
-- Looking for gethostbyaddr_r - found
-- Looking for inet_pton
-- Looking for inet_pton - found
-- Looking for inet_ntop
-- Looking for inet_ntop - found
-- Performing Test HAS_MSGHDR_FLAGS
-- Performing Test HAS_MSGHDR_FLAGS - Success
-- Check size of socklen_t
-- Check size of socklen_t - done
-- Using static xxhash from Externals
-- Found BZip2: /usr/lib/arm-linux-gnueabihf/libbz2.so (found version "1.0.6") 
-- Looking for BZ2_bzCompressInit
-- Looking for BZ2_bzCompressInit - found
-- Using shared bzip2
-- Looking for lzma_auto_decoder in /usr/lib/arm-linux-gnueabihf/liblzma.so
-- Looking for lzma_auto_decoder in /usr/lib/arm-linux-gnueabihf/liblzma.so - found
-- Looking for lzma_easy_encoder in /usr/lib/arm-linux-gnueabihf/liblzma.so
-- Looking for lzma_easy_encoder in /usr/lib/arm-linux-gnueabihf/liblzma.so - found
-- Looking for lzma_lzma_preset in /usr/lib/arm-linux-gnueabihf/liblzma.so
-- Looking for lzma_lzma_preset in /usr/lib/arm-linux-gnueabihf/liblzma.so - found
-- Found LibLZMA: /usr/include (found version "5.2.4") 
-- Looking for lzma.h
-- Looking for lzma.h - found
-- Using shared lzma
-- Shared zstd not found, falling back to the static library
-- Looking for sys/types.h
-- Looking for sys/types.h - found
-- Looking for stdint.h
-- Looking for stdint.h - found
-- Looking for stddef.h
-- Looking for stddef.h - found
-- Check size of off64_t
-- Check size of off64_t - done
-- Looking for fseeko
-- Looking for fseeko - found
-- Looking for unistd.h
-- Looking for unistd.h - found
-- Found ZLIB: /usr/lib/arm-linux-gnueabihf/libz.so (found version "1.2.11") 
-- Using shared zlib
-- Checking for module 'minizip>=2.0.0'
--   No package 'minizip' found
-- Shared minizip not found, falling back to the static library
-- Using shared lzo
-- Using static libpng from Externals
-- Using static FreeSurround from Externals
-- Could NOT find CUBEB (missing: CUBEB_INCLUDE_DIR CUBEB_LIBRARY) 
-- Using static cubeb from Externals
-- Performing Test COMPILER_HAS_HIDDEN_VISIBILITY
-- Performing Test COMPILER_HAS_HIDDEN_VISIBILITY - Success
-- Performing Test COMPILER_HAS_HIDDEN_INLINE_VISIBILITY
-- Performing Test COMPILER_HAS_HIDDEN_INLINE_VISIBILITY - Success
-- Performing Test COMPILER_HAS_DEPRECATED_ATTR
-- Performing Test COMPILER_HAS_DEPRECATED_ATTR - Success
-- Looking for include file AudioUnit/AudioUnit.h
-- Looking for include file AudioUnit/AudioUnit.h - not found
-- Looking for include file pulse/pulseaudio.h
-- Looking for include file pulse/pulseaudio.h - found
-- Looking for include file alsa/asoundlib.h
-- Looking for include file alsa/asoundlib.h - found
-- Looking for include file jack/jack.h
-- Looking for include file jack/jack.h - found
-- Looking for include file audioclient.h
-- Looking for include file audioclient.h - not found
-- Looking for include files windows.h, mmsystem.h
-- Looking for include files windows.h, mmsystem.h - not found
-- Looking for include file SLES/OpenSLES.h
-- Looking for include file SLES/OpenSLES.h - not found
-- Looking for include file android/log.h
-- Looking for include file android/log.h - not found
-- Looking for include file sndio.h
-- Looking for include file sndio.h - found
-- Looking for include file kai.h
-- Looking for include file kai.h - not found
-- Checking for module 'libusb-1.0'
--   Found libusb-1.0, version 1.0.22
-- Found libusb-1.0: /usr/include/libusb-1.0, /usr/lib/arm-linux-gnueabihf/libusb-1.0.so
-- Using shared LibUSB
-- Found SFML 2.5 in /usr/include
-- Using shared SFML
-- Performing Test MBEDTLS_VERSION_OK
-- Performing Test MBEDTLS_VERSION_OK - Success
-- Found MBEDTLS: /usr/include  
-- Using shared mbed TLS
-- Found CURL: /usr/lib/arm-linux-gnueabihf/libcurl.so (found version "7.64.0") 
-- Using static libcurl from Externals
-- Could NOT find HIDAPI (missing: HIDAPI_LIBRARY HIDAPI_INCLUDE_DIR) 
-- Using static HIDAPI from Externals
-- Could NOT find SYSTEMD (missing: SYSTEMD_LIBRARIES SYSTEMD_INCLUDE_DIRS) 
-- libsystemd not found, disabling traversal server watchdog support
-- Using static gtest from Externals
-- Found PythonInterp: /usr/bin/python (found version "2.7.16") 
-- Check if compiler accepts -pthread
-- Check if compiler accepts -pthread - yes
-- Could NOT find OpenSLES (missing: OPENSLES_LIBRARY OPENSLES_INCLUDE_DIR) 
-- ALSA explicitly disabled, disabling ALSA sound backend
-- PulseAudio explicitly disabled, disabling PulseAudio sound backend
-- Found BlueZ: /usr/lib/arm-linux-gnueabihf/libbluetooth.so  
-- BlueZ found, enabling bluetooth support
-- Found Qt version 5.11.3
-- Found Gettext: /usr/bin/msgmerge (found version "0.19.8.1") 
-- Configuring done
CMake Error at Source/Core/Core/CMakeLists.txt:1 (add_library):
  Target "core" links to target "LibLZMA::LibLZMA" but the target was not
  found.  Perhaps a find_package() call is missing for an IMPORTED target, or
  an ALIAS target is missing?


CMake Error at Source/Core/DiscIO/CMakeLists.txt:1 (add_library):
  Target "discio" links to target "LibLZMA::LibLZMA" but the target was not
  found.  Perhaps a find_package() call is missing for an IMPORTED target, or
  an ALIAS target is missing?


CMake Error at Source/Core/VideoCommon/CMakeLists.txt:1 (add_library):
  Target "videocommon" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?


CMake Error at Source/Core/VideoBackends/OGL/CMakeLists.txt:1 (add_library):
  Target "videoogl" links to target "LibLZMA::LibLZMA" but the target was not
  found.  Perhaps a find_package() call is missing for an IMPORTED target, or
  an ALIAS target is missing?


CMake Error at Source/Core/VideoBackends/Null/CMakeLists.txt:1 (add_library):
  Target "videonull" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?


CMake Error at Source/Core/VideoBackends/Software/CMakeLists.txt:1 (add_library):
  Target "videosoftware" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?


CMake Error at Source/Core/VideoBackends/Vulkan/CMakeLists.txt:1 (add_library):
  Target "videovulkan" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?


CMake Error at Source/Core/DolphinNoGUI/CMakeLists.txt:1 (add_executable):
  Target "dolphin-nogui" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?


CMake Error at Source/Core/DolphinQt/CMakeLists.txt:16 (add_executable):
  Target "dolphin-emu" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?


CMake Error at Source/Core/DolphinLibretro/CMakeLists.txt:2 (add_library):
  Target "dolphin_libretro" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "BitFieldTest" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:1 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "CommonFuncsTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:6 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "BusyLoopTest" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:5 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "FixedSizeQueueTest" links to target "LibLZMA::LibLZMA" but the
  target was not found.  Perhaps a find_package() call is missing for an
  IMPORTED target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:9 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "SPSCQueueTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:14 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "BitSetTest" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:2 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "MathUtilTest" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:12 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "CryptoEcTest" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:7 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "BitUtilsTest" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:3 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "FlagTest" links to target "LibLZMA::LibLZMA" but the target was not
  found.  Perhaps a find_package() call is missing for an IMPORTED target, or
  an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:10 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "BlockingLoopTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:4 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "EventTest" links to target "LibLZMA::LibLZMA" but the target was
  not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:8 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "FloatUtilsTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:11 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "NandPathsTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:13 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "StringUtilTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:15 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "SwapTest" links to target "LibLZMA::LibLZMA" but the target was not
  found.  Perhaps a find_package() call is missing for an IMPORTED target, or
  an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Common/CMakeLists.txt:16 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "PageFaultTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Core/CMakeLists.txt:2 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "DSPAssemblyTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Core/CMakeLists.txt:6 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "CoreTimingTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Core/CMakeLists.txt:3 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "DSPAcceleratorTest" links to target "LibLZMA::LibLZMA" but the
  target was not found.  Perhaps a find_package() call is missing for an
  IMPORTED target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Core/CMakeLists.txt:5 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "FileSystemTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Core/CMakeLists.txt:15 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "MMIOTest" links to target "LibLZMA::LibLZMA" but the target was not
  found.  Perhaps a find_package() call is missing for an IMPORTED target, or
  an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Core/CMakeLists.txt:1 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "ESFormatsTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/Core/CMakeLists.txt:13 (add_dolphin_test)


CMake Error at Source/UnitTests/CMakeLists.txt:14 (add_executable):
  Target "VertexLoaderTest" links to target "LibLZMA::LibLZMA" but the target
  was not found.  Perhaps a find_package() call is missing for an IMPORTED
  target, or an ALIAS target is missing?
Call Stack (most recent call first):
  Source/UnitTests/VideoCommon/CMakeLists.txt:1 (add_dolphin_test)


-- Generating done
-- Build files have been written to: /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/build
Scanning dependencies of target cpp-optparse
Scanning dependencies of target pugixml
Scanning dependencies of target imgui
[  0%] Building CXX object Externals/cpp-optparse/CMakeFiles/cpp-optparse.dir/OptionParser.cpp.o
[  0%] Building CXX object Externals/pugixml/CMakeFiles/pugixml.dir/pugixml.cpp.o
[  0%] Building CXX object Externals/imgui/CMakeFiles/imgui.dir/imgui.cpp.o
Scanning dependencies of target glslang
[  0%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/GenericCodeGen/CodeGen.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/pugixml/pugixml.cpp:4453:112: warning: 'unsigned-integer-overflow' attribute directive ignored [-Wattributes]
  template <typename U> PUGI__FN PUGI__UNSIGNED_OVERFLOW U string_to_integer(const char_t* value, U minv, U maxv)
                                                                                                                ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/pugixml/pugixml.cpp:4584:133: warning: 'unsigned-integer-overflow' attribute directive ignored [-Wattributes]
  template <typename U> PUGI__FN PUGI__UNSIGNED_OVERFLOW char_t* integer_to_string(char_t* begin, char_t* end, U value, bool negative)
                                                                                                                                     ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/pugixml/pugixml.cpp:8418:77: warning: 'unsigned-integer-overflow' attribute directive ignored [-Wattributes]
  PUGI__FN PUGI__UNSIGNED_OVERFLOW unsigned int hash_string(const char_t* str)
                                                                             ^
[  0%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/GenericCodeGen/Link.cpp.o
[  0%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/attribute.cpp.o
[  0%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/Constant.cpp.o
[  1%] Linking CXX static library libcpp-optparse.a
[  1%] Built target cpp-optparse
Scanning dependencies of target enet
[  1%] Building C object Externals/enet/CMakeFiles/enet.dir/callbacks.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/compress.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/host.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/list.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/packet.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/peer.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/protocol.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/unix.c.o
[  2%] Building C object Externals/enet/CMakeFiles/enet.dir/win32.c.o
[  2%] Linking C static library libenet.a
[  2%] Built target enet
[  2%] Building CXX object Externals/imgui/CMakeFiles/imgui.dir/imgui_draw.cpp.o
[  2%] Building CXX object Externals/imgui/CMakeFiles/imgui.dir/imgui_widgets.cpp.o
[  2%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/glslang_tab.cpp.o
[  2%] Linking CXX static library libpugixml.a
[  2%] Built target pugixml
Scanning dependencies of target xxhash
[  2%] Building C object Externals/xxhash/CMakeFiles/xxhash.dir/xxhash.c.o
[  2%] Linking C static library libxxhash.a
[  2%] Built target xxhash
Scanning dependencies of target zstd
[  2%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/debug.c.o
[  2%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/entropy_common.c.o
[  2%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/error_private.c.o
[  2%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/fse_decompress.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/pool.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/threading.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/xxhash.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/common/zstd_common.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/fse_compress.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/hist.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/huf_compress.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_compress.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_compress_literals.c.o
[  3%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_compress_sequences.c.o
[  4%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_double_fast.c.o
[  4%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_fast.c.o
[  5%] Linking CXX static library libimgui.a
[  5%] Built target imgui
Scanning dependencies of target minizip
[  5%] Building C object Externals/minizip/CMakeFiles/minizip.dir/ioapi.c.o
In function 'file_build_ioposix',
    inlined from 'fopen_file_func.constprop' at /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:124:16,
    inlined from 'fopendisk_file_func' at /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:193:15:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:106:5: warning: 'strncpy' specified bound depends on the length of the source argument [-Wstringop-overflow=]
     strncpy((char*)ioposix->filename, filename, ioposix->filenameLength);
     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c: In function 'fopendisk_file_func':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:104:36: note: length computed here
     ioposix->filenameLength = (int)strlen(filename) + 1;
                                    ^~~~~~~~~~~~~~~~
In function 'file_build_ioposix',
    inlined from 'fopen64_file_func' at /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:143:16:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:106:5: warning: 'strncpy' specified bound depends on the length of the source argument [-Wstringop-overflow=]
     strncpy((char*)ioposix->filename, filename, ioposix->filenameLength);
     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c: In function 'fopen64_file_func':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:104:36: note: length computed here
     ioposix->filenameLength = (int)strlen(filename) + 1;
                                    ^~~~~~~~~~~~~~~~
In function 'file_build_ioposix',
    inlined from 'fopen_file_func' at /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:124:16:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:106:5: warning: 'strncpy' specified bound depends on the length of the source argument [-Wstringop-overflow=]
     strncpy((char*)ioposix->filename, filename, ioposix->filenameLength);
     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c: In function 'fopen_file_func':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:104:36: note: length computed here
     ioposix->filenameLength = (int)strlen(filename) + 1;
                                    ^~~~~~~~~~~~~~~~
In function 'file_build_ioposix',
    inlined from 'fopen64_file_func.constprop' at /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:143:16,
    inlined from 'fopendisk64_file_func' at /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:168:15:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:106:5: warning: 'strncpy' specified bound depends on the length of the source argument [-Wstringop-overflow=]
     strncpy((char*)ioposix->filename, filename, ioposix->filenameLength);
     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c: In function 'fopendisk64_file_func':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/minizip/ioapi.c:104:36: note: length computed here
     ioposix->filenameLength = (int)strlen(filename) + 1;
                                    ^~~~~~~~~~~~~~~~
[  5%] Building C object Externals/minizip/CMakeFiles/minizip.dir/unzip.c.o
[  5%] Linking C static library libminizip.a
[  5%] Built target minizip
Scanning dependencies of target png
[  5%] Building C object Externals/libpng/CMakeFiles/png.dir/png.c.o
[  5%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_lazy.c.o
[  5%] Building C object Externals/libpng/CMakeFiles/png.dir/pngerror.c.o
[  5%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/InfoSink.cpp.o
[  5%] Building C object Externals/libpng/CMakeFiles/png.dir/pngget.c.o
[  6%] Building C object Externals/libpng/CMakeFiles/png.dir/pngmem.c.o
Scanning dependencies of target FreeSurround
[  6%] Building CXX object Externals/FreeSurround/CMakeFiles/FreeSurround.dir/source/ChannelMaps.cpp.o
[  6%] Building C object Externals/libpng/CMakeFiles/png.dir/pngpread.c.o
[  6%] Building C object Externals/libpng/CMakeFiles/png.dir/pngread.c.o
[  6%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/Initialize.cpp.o
[  6%] Building C object Externals/libpng/CMakeFiles/png.dir/pngrio.c.o
[  6%] Building CXX object Externals/FreeSurround/CMakeFiles/FreeSurround.dir/source/KissFFT.cpp.o
[  6%] Building C object Externals/libpng/CMakeFiles/png.dir/pngrtran.c.o
[  6%] Building CXX object Externals/FreeSurround/CMakeFiles/FreeSurround.dir/source/KissFFTR.cpp.o
[  6%] Building CXX object Externals/FreeSurround/CMakeFiles/FreeSurround.dir/source/FreeSurroundDecoder.cpp.o
[  6%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_ldm.c.o
[  6%] Building C object Externals/libpng/CMakeFiles/png.dir/pngrutil.c.o
[  6%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstd_opt.c.o
[  6%] Linking CXX static library libFreeSurround.a
[  6%] Built target FreeSurround
Scanning dependencies of target SoundTouch
[  6%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/AAFilter.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/BPMDetect.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/cpu_detect_x86.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/FIFOSampleBuffer.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/FIRFilter.cpp.o
[  7%] Building C object Externals/libpng/CMakeFiles/png.dir/pngset.c.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/InterpolateCubic.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/InterpolateLinear.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/InterpolateShannon.cpp.o
[  7%] Building C object Externals/libpng/CMakeFiles/png.dir/pngtrans.c.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/mmx_optimized.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/PeakFinder.cpp.o
[  7%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/RateTransposer.cpp.o
[  7%] Building C object Externals/libpng/CMakeFiles/png.dir/pngwio.c.o
[  7%] Building C object Externals/libpng/CMakeFiles/png.dir/pngwrite.c.o
[  7%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/Intermediate.cpp.o
[  8%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/SoundTouch.cpp.o
[  8%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/sse_optimized.cpp.o
[  8%] Building CXX object Externals/soundtouch/CMakeFiles/SoundTouch.dir/TDStretch.cpp.o
[  8%] Linking CXX static library libSoundTouch.a
[  8%] Building C object Externals/libpng/CMakeFiles/png.dir/pngwtran.c.o
[  8%] Built target SoundTouch
[  8%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/compress/zstdmt_compress.c.o
[  9%] Building C object Externals/libpng/CMakeFiles/png.dir/pngwutil.c.o
[  9%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/decompress/huf_decompress.c.o
[  9%] Linking C static library libpng.a
[  9%] Built target png
[  9%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/intermOut.cpp.o
[  9%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/decompress/zstd_ddict.c.o
[ 10%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/IntermTraverse.cpp.o
[ 10%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/iomapper.cpp.o
[ 10%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/limits.cpp.o
[ 10%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/decompress/zstd_decompress.c.o
[ 10%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/linkValidate.cpp.o
Scanning dependencies of target curl
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/amigaos.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/asyn-ares.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/asyn-thread.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/base64.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/conncache.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/connect.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/content_encoding.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/cookie.c.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/cookie.c: In function 'cookie_output':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/cookie.c:1315:7: warning: this 'if' clause does not guard... [-Wmisleading-indentation]
       if(!use_stdout)
       ^~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/cookie.c:1317:9: note: ...this statement, but the latter is misleadingly indented as if it were guarded by the 'if'
         return 1;
         ^~~~~~
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_addrinfo.c.o
[ 10%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_des.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_endian.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_fnmatch.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_gethostname.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_gssapi.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_memrchr.c.o
[ 11%] Building C object Externals/zstd/CMakeFiles/zstd.dir/lib/decompress/zstd_decompress_block.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_multibyte.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_ntlm_core.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_ntlm_wb.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_rtmp.c.o
[ 11%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_sasl.c.o
Scanning dependencies of target speex
[ 11%] Building C object Externals/cubeb/CMakeFiles/speex.dir/src/speex/resample.c.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c: In function 'update_filter':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c:674:20: warning: comparison of integer expressions of different signedness: 'int' and 'unsigned int' [-Wsign-compare]
          for (j=0;j<st->filt_len;j++)
                    ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c: In function 'speex_resampler_process_float':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c:946:21: warning: comparison of integer expressions of different signedness: 'int' and 'unsigned int' [-Wsign-compare]
            for(j=0;j<ichunk;++j)
                     ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c:949:20: warning: comparison of integer expressions of different signedness: 'int' and 'unsigned int' [-Wsign-compare]
           for(j=0;j<ichunk;++j)
                    ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c: In function 'speex_resampler_process_int':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c:1002:19: warning: comparison of integer expressions of different signedness: 'int' and 'unsigned int' [-Wsign-compare]
          for(j=0;j<ichunk;++j)
                   ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c:1009:19: warning: comparison of integer expressions of different signedness: 'int' and 'unsigned int' [-Wsign-compare]
          for(j=0;j<ichunk;++j)
                   ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/speex/resample.c:1019:16: warning: comparison of integer expressions of different signedness: 'int' and 'unsigned int' [-Wsign-compare]
      for (j=0;j<ochunk+omagic;++j)
                ^
[ 12%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_sspi.c.o
[ 12%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/curl_threads.c.o
[ 12%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/dict.c.o
[ 12%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/dotdot.c.o
[ 12%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/easy.c.o
[ 13%] Linking C static library libzstd.a
[ 13%] Built target speex
[ 13%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/parseConst.cpp.o
[ 13%] Built target zstd
[ 13%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/ParseContextBase.cpp.o
[ 13%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/escape.c.o
[ 13%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/file.c.o
[ 13%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/fileinfo.c.o
[ 13%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/formdata.c.o
[ 13%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/ftp.c.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/ftplistparser.c.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/getenv.c.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/getinfo.c.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/gopher.c.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hash.c.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hmac.c.o
Scanning dependencies of target fmt
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hostasyn.c.o
[ 14%] Building CXX object Externals/fmt/CMakeFiles/fmt.dir/src/format.cc.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hostcheck.c.o
Scanning dependencies of target hidapi
[ 14%] Building C object Externals/hidapi/CMakeFiles/hidapi.dir/linux/hid.c.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hostip.c.o
[ 14%] Linking C static library libhidapi.a
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hostip4.c.o
[ 14%] Built target hidapi
[ 14%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/ParseHelper.cpp.o
[ 14%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hostip6.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/hostsyn.c.o
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/fmt/src/format.cc:8:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/fmt/include/fmt/format-inl.h:87:14: warning: no previous declaration for 'int fmt::v6::internal::safe_strerror(int, char*&, std::size_t)' [-Wmissing-declarations]
 FMT_FUNC int safe_strerror(int error_code, char*& buffer,
              ^~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/fmt/include/fmt/format-inl.h:145:15: warning: no previous declaration for 'void fmt::v6::internal::format_error_code(fmt::v6::internal::buffer<char>&, int, fmt::v6::string_view)' [-Wmissing-declarations]
 FMT_FUNC void format_error_code(internal::buffer<char>& out, int error_code,
               ^~~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/fmt/include/fmt/format-inl.h:172:15: warning: no previous declaration for 'void fmt::v6::internal::fwrite_fully(const void*, size_t, size_t, FILE*)' [-Wmissing-declarations]
 FMT_FUNC void fwrite_fully(const void* ptr, size_t size, size_t count,
               ^~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/fmt/include/fmt/format-inl.h:180:15: warning: no previous declaration for 'void fmt::v6::internal::report_error(fmt::v6::internal::format_func, int, fmt::v6::string_view)' [-Wmissing-declarations]
 FMT_FUNC void report_error(format_func func, int error_code,
               ^~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/fmt/include/fmt/format-inl.h:480:13: warning: no previous declaration for 'fmt::v6::internal::fp fmt::v6::internal::get_cached_power(int, int&)' [-Wmissing-declarations]
 FMT_FUNC fp get_cached_power(int min_exponent, int& pow10_exponent) {
             ^~~~~~~~~~~~~~~~
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/http.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/http2.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/http_chunks.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/http_digest.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/http_negotiate.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/http_ntlm.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/http_proxy.c.o
[ 15%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/PoolAlloc.cpp.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/idn_win32.c.o
[ 15%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/if2ip.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/imap.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/inet_ntop.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/inet_pton.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/krb5.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/ldap.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/llist.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/md4.c.o
Scanning dependencies of target discio
[ 16%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/Blob.cpp.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/md5.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/memdebug.c.o
[ 16%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/mprintf.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/multi.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/netrc.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/non-ascii.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/nonblock.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/nwlib.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/nwos.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/openldap.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/parsedate.c.o
[ 17%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/CISOBlob.cpp.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/pingpong.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/pipeline.c.o
[ 17%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/pop3.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/progress.c.o
[ 18%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/CompressedBlob.cpp.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/rawstr.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/rtsp.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/security.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/select.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/sendf.c.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/sendf.c: In function 'Curl_send_plain':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/sendf.c:372:28: warning: logical 'or' of equal expressions [-Wlogical-op]
       (EWOULDBLOCK == err) || (EAGAIN == err) || (EINTR == err) ||
                            ^~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/sendf.c: In function 'Curl_recv_plain':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/sendf.c:439:28: warning: logical 'or' of equal expressions [-Wlogical-op]
       (EWOULDBLOCK == err) || (EAGAIN == err) || (EINTR == err)
                            ^~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/sendf.c: In function 'Curl_read_plain':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/sendf.c:638:39: warning: logical 'or' of equal expressions [-Wlogical-op]
     return_error = EWOULDBLOCK == err || EAGAIN == err || EINTR == err;
                                       ^~
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/share.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/slist.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/smb.c.o
[ 18%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/smtp.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/socks.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/socks_gssapi.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/socks_sspi.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/speedcheck.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/splay.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/ssh.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/strdup.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/strequal.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/strerror.c.o
[ 19%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/strtok.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/strtoofft.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/system_win32.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/telnet.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/tftp.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/timeval.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/transfer.c.o
[ 20%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/DirectoryBlob.cpp.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/url.c.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/url.c: In function 'ConnectionExists':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/url.c:3213:17: warning: variable 'hostname' set but not used [-Wunused-but-set-variable]
     const char *hostname;
                 ^~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/url.c: In function 'parse_connect_to_slist':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/url.c:5495:12: warning: variable 'ipv6host' set but not used [-Wunused-but-set-variable]
       bool ipv6host;
            ^~~~~~~~
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/cleartext.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/cram.c.o
[ 20%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/digest.c.o
[ 20%] Building CXX object Externals/fmt/CMakeFiles/fmt.dir/src/posix.cc.o
[ 21%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/digest_sspi.c.o
[ 21%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/krb5_gssapi.c.o
[ 21%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/krb5_sspi.c.o
[ 21%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/ntlm.c.o
[ 21%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/ntlm_sspi.c.o
[ 21%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/oauth2.c.o
[ 21%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/spnego_gssapi.c.o
[ 22%] Linking CXX static library libfmt.a
[ 22%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/spnego_sspi.c.o
[ 22%] Built target fmt
[ 22%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vauth/vauth.c.o
Scanning dependencies of target unittests_stubhost
[ 23%] Building CXX object Source/UnitTests/CMakeFiles/unittests_stubhost.dir/StubHost.cpp.o
[ 23%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/version.c.o
[ 23%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/axtls.c.o
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WiiEncryptionCache.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.h:20,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__insertion_sort(_RandomAccessIterator, _RandomAccessIterator, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobPartition::WriteDirectory(const File::FSTEntry&, u32*, u32*, u64*, u32, u64)::<lambda(const File::FSTEntry&, const File::FSTEntry&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
     __insertion_sort(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/cyassl.c.o
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/darwinssl.c.o
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/gskit.c.o
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/gtls.c.o
[ 25%] Built target unittests_stubhost
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__unguarded_linear_insert(_RandomAccessIterator, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >; _Compare = __gnu_cxx::__ops::_Val_comp_iter<DiscIO::DirectoryBlobReader::SetPartitions(std::vector<DiscIO::DirectoryBlobReader::PartitionWithType>&&)::<lambda(const DiscIO::DirectoryBlobReader::PartitionWithType&, const DiscIO::DirectoryBlobReader::PartitionWithType&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1821:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
     __unguarded_linear_insert(_RandomAccessIterator __last,
     ^~~~~~~~~~~~~~~~~~~~~~~~~
[ 25%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/DiscExtractor.cpp.o
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/mbedtls.c.o
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__insertion_sort(_RandomAccessIterator, _RandomAccessIterator, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobReader::SetPartitions(std::vector<DiscIO::DirectoryBlobReader::PartitionWithType>&&)::<lambda(const DiscIO::DirectoryBlobReader::PartitionWithType&, const DiscIO::DirectoryBlobReader::PartitionWithType&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
     __insertion_sort(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/mbedtls.c:34:
/usr/include/mbedtls/net.h:30:2: warning: #warning "Deprecated header file: Superseded by mbedtls/net_sockets.h" [-Wcpp]
 #warning "Deprecated header file: Superseded by mbedtls/net_sockets.h"
  ^~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/mbedtls.c: In function 'mbed_connect_step1':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/mbedtls.c:167:19: warning: unused variable 'addr' [-Wunused-variable]
   struct in6_addr addr;
                   ^~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/mbedtls.c:164:8: warning: variable 'sni' set but not used [-Wunused-but-set-variable]
   bool sni = TRUE; /* default is SNI enabled */
        ^~~
In file included from /usr/include/c++/8/bits/stl_algo.h:61,
                 from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WiiEncryptionCache.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.h:20,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.cpp:5:
/usr/include/c++/8/bits/stl_heap.h: In function 'void std::__adjust_heap(_RandomAccessIterator, _Distance, _Distance, _Tp, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >; _Distance = int; _Tp = DiscIO::DirectoryBlobReader::PartitionWithType; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobReader::SetPartitions(std::vector<DiscIO::DirectoryBlobReader::PartitionWithType>&&)::<lambda(const DiscIO::DirectoryBlobReader::PartitionWithType&, const DiscIO::DirectoryBlobReader::PartitionWithType&)> >]':
/usr/include/c++/8/bits/stl_heap.h:214:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
     __adjust_heap(_RandomAccessIterator __first, _Distance __holeIndex,
     ^~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_heap.h: In function 'void std::__make_heap(_RandomAccessIterator, _RandomAccessIterator, _Compare&) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobReader::SetPartitions(std::vector<DiscIO::DirectoryBlobReader::PartitionWithType>&&)::<lambda(const DiscIO::DirectoryBlobReader::PartitionWithType&, const DiscIO::DirectoryBlobReader::PartitionWithType&)> >]':
/usr/include/c++/8/bits/stl_heap.h:326:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
     __make_heap(_RandomAccessIterator __first, _RandomAccessIterator __last,
     ^~~~~~~~~~~
/usr/include/c++/8/bits/stl_heap.h:326:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_heap.h: In function 'void std::__pop_heap(_RandomAccessIterator, _RandomAccessIterator, _RandomAccessIterator, _Compare&) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobReader::SetPartitions(std::vector<DiscIO::DirectoryBlobReader::PartitionWithType>&&)::<lambda(const DiscIO::DirectoryBlobReader::PartitionWithType&, const DiscIO::DirectoryBlobReader::PartitionWithType&)> >]':
/usr/include/c++/8/bits/stl_heap.h:243:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
     __pop_heap(_RandomAccessIterator __first, _RandomAccessIterator __last,
     ^~~~~~~~~~
/usr/include/c++/8/bits/stl_heap.h:243:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_heap.h:243:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/nss.c.o
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WiiEncryptionCache.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.h:20,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__introsort_loop(_RandomAccessIterator, _RandomAccessIterator, _Size, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >; _Size = int; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobReader::SetPartitions(std::vector<DiscIO::DirectoryBlobReader::PartitionWithType>&&)::<lambda(const DiscIO::DirectoryBlobReader::PartitionWithType&, const DiscIO::DirectoryBlobReader::PartitionWithType&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
     __introsort_loop(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
In file included from /usr/include/c++/8/bits/stl_algo.h:61,
                 from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WiiEncryptionCache.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.h:20,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.cpp:5:
/usr/include/c++/8/bits/stl_heap.h:408:19: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
    std::__pop_heap(__first, __last, __last, __comp);
    ~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WiiEncryptionCache.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.h:20,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h:1954:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
    std::__introsort_loop(__cut, __last, __depth_limit, __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1672:23: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
       std::__make_heap(__first, __middle, __comp);
       ~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/openssl.c.o
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/polarssl.c.o
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/polarssl_threadlock.c.o
[ 25%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/schannel.c.o
[ 26%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/vtls/vtls.c.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/vtls.c: In function 'Curl_pin_peer_pubkey':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/vtls.c:825:5: warning: 'mbedtls_sha256' is deprecated [-Wdeprecated-declarations]
     curlssl_sha256sum(pubkey, pubkeylen,
     ^~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/mbedtls.h:29,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/vtls.h:35,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/curl/lib/vtls/vtls.c:61:
/usr/include/mbedtls/sha256.h:273:25: note: declared here
 MBEDTLS_DEPRECATED void mbedtls_sha256( const unsigned char *input,
                         ^~~~~~~~~~~~~~
[ 26%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/warnless.c.o
/usr/include/c++/8/bits/stl_algo.h: In member function 'void DiscIO::DirectoryBlobReader::SetPartitions(std::vector<DiscIO::DirectoryBlobReader::PartitionWithType>&&)':
/usr/include/c++/8/bits/stl_algo.h:1968:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
    std::__introsort_loop(__first, __last,
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
     std::__lg(__last - __first) * 2,
     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     __comp);
     ~~~~~~~              
/usr/include/c++/8/bits/stl_algo.h:1885:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
    std::__insertion_sort(__first, __first + int(_S_threshold), __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1890:23: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::DirectoryBlobReader::PartitionWithType*, std::vector<DiscIO::DirectoryBlobReader::PartitionWithType> >' changed in GCC 7.1
  std::__insertion_sort(__first, __last, __comp);
  ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
[ 26%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/wildcard.c.o
In file included from /usr/include/c++/8/bits/stl_algo.h:61,
                 from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WiiEncryptionCache.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.h:20,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.cpp:5:
/usr/include/c++/8/bits/stl_heap.h: In function 'void std::__adjust_heap(_RandomAccessIterator, _Distance, _Distance, _Tp, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >; _Distance = int; _Tp = File::FSTEntry; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobPartition::WriteDirectory(const File::FSTEntry&, u32*, u32*, u64*, u32, u64)::<lambda(const File::FSTEntry&, const File::FSTEntry&)> >]':
/usr/include/c++/8/bits/stl_heap.h:214:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
     __adjust_heap(_RandomAccessIterator __first, _Distance __holeIndex,
     ^~~~~~~~~~~~~
[ 26%] Building C object Externals/curl/lib/CMakeFiles/curl.dir/x509asn1.c.o
[ 26%] Linking C static library libcurl.a
[ 26%] Built target curl
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/DiscScrubber.cpp.o
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WiiEncryptionCache.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.h:20,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/DirectoryBlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__introsort_loop(_RandomAccessIterator, _RandomAccessIterator, _Size, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >; _Size = int; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::DirectoryBlobPartition::WriteDirectory(const File::FSTEntry&, u32*, u32*, u64*, u32, u64)::<lambda(const File::FSTEntry&, const File::FSTEntry&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
     __introsort_loop(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_algo.h:1954:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
    std::__introsort_loop(__cut, __last, __depth_limit, __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h: In member function 'void DiscIO::DirectoryBlobPartition::WriteDirectory(const File::FSTEntry&, u32*, u32*, u64*, u32, u64)':
/usr/include/c++/8/bits/stl_algo.h:1968:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
    std::__introsort_loop(__first, __last,
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
     std::__lg(__last - __first) * 2,
     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     __comp);
     ~~~~~~~              
/usr/include/c++/8/bits/stl_algo.h:1885:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
    std::__insertion_sort(__first, __first + int(_S_threshold), __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1890:23: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
  std::__insertion_sort(__first, __last, __comp);
  ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/DriveBlob.cpp.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/Enums.cpp.o
[ 27%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/preprocessor/Pp.cpp.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/FileBlob.cpp.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/FileSystemGCWii.cpp.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/Filesystem.cpp.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/LaggedFibonacciGenerator.cpp.o
Scanning dependencies of target cubeb
[ 27%] Building C object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb.c.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/NANDImporter.cpp.o
[ 27%] Building CXX object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_mixer.cpp.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/ScrubbedBlob.cpp.o
[ 27%] Building CXX object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_resampler.cpp.o
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h: In constructor 'processor::processor(uint32_t)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:62:5: warning: declaration of 'channels' shadows a member of 'processor' [-Wshadow]
     : channels(channels)
     ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:75:18: note: shadowed declaration is here
   const uint32_t channels;
                  ^~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h: In constructor 'cubeb_resampler_speex_one_way<T>::cubeb_resampler_speex_one_way(uint32_t, uint32_t, uint32_t, int)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:183:3: warning: declaration of 'source_rate' shadows a member of 'cubeb_resampler_speex_one_way<T>' [-Wshadow]
   : processor(channels)
   ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:364:18: note: shadowed declaration is here
   const uint32_t source_rate;
                  ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:183:3: warning: declaration of 'channels' shadows a member of 'cubeb_resampler_speex_one_way<T>' [-Wshadow]
   : processor(channels)
   ^
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:75:18: note: shadowed declaration is here
   const uint32_t channels;
                  ^~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h: In constructor 'delay_line<T>::delay_line(uint32_t, uint32_t, uint32_t)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:386:5: warning: declaration of 'sample_rate' shadows a member of 'delay_line<T>' [-Wshadow]
     : processor(channels)
     ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:499:12: note: shadowed declaration is here
   uint32_t sample_rate;
            ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:386:5: warning: declaration of 'channels' shadows a member of 'delay_line<T>' [-Wshadow]
     : processor(channels)
     ^
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:75:18: note: shadowed declaration is here
   const uint32_t channels;
                  ^~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In constructor 'passthrough_resampler<T>::passthrough_resampler(cubeb_stream*, cubeb_data_callback, void*, uint32_t, uint32_t)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:48:69: warning: declaration of 'sample_rate' shadows a member of 'passthrough_resampler<T>' [-Wshadow]
                                                 uint32_t sample_rate)
                                                                     ^
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:112:12: note: shadowed declaration is here
   uint32_t sample_rate;
            ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In constructor 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>::cubeb_resampler_speex(InputProcessor*, OutputProcessor*, cubeb_stream*, cubeb_data_callback, void*)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:95:37: warning: declaration of 'output_processor' shadows a member of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>' [-Wshadow]
                           void * ptr)
                                     ^
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:155:37: note: shadowed declaration is here
   std::unique_ptr<OutputProcessing> output_processor;
                                     ^~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:95:37: warning: declaration of 'input_processor' shadows a member of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>' [-Wshadow]
                           void * ptr)
                                     ^
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:154:36: note: shadowed declaration is here
   std::unique_ptr<InputProcessing> input_processor;
                                    ^~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'passthrough_resampler<T>::passthrough_resampler(cubeb_stream*, cubeb_data_callback, void*, uint32_t, uint32_t) [with T = short int; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int); uint32_t = unsigned int]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:528:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = short int; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:293:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:44:1: warning: declaration of 'sample_rate' shadows a member of 'passthrough_resampler<short int>' [-Wshadow]
 passthrough_resampler<T>::passthrough_resampler(cubeb_stream * s,
 ^~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:112:12: note: shadowed declaration is here
   uint32_t sample_rate;
            ^~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h: In instantiation of 'cubeb_resampler_speex_one_way<T>::cubeb_resampler_speex_one_way(uint32_t, uint32_t, uint32_t, int) [with T = short int; uint32_t = unsigned int]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:538:9:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = short int; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:293:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:179:3: warning: declaration of 'source_rate' shadows a member of 'cubeb_resampler_speex_one_way<short int>' [-Wshadow]
   cubeb_resampler_speex_one_way(uint32_t channels,
   ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:364:18: note: shadowed declaration is here
   const uint32_t source_rate;
                  ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:179:3: warning: declaration of 'channels' shadows a member of 'cubeb_resampler_speex_one_way<short int>' [-Wshadow]
   cubeb_resampler_speex_one_way(uint32_t channels,
   ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:75:18: note: shadowed declaration is here
   const uint32_t channels;
                  ^~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h: In instantiation of 'delay_line<T>::delay_line(uint32_t, uint32_t, uint32_t) [with T = short int; uint32_t = unsigned int]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:562:24:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = short int; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:293:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:385:3: warning: declaration of 'sample_rate' shadows a member of 'delay_line<short int>' [-Wshadow]
   delay_line(uint32_t frames, uint32_t channels, uint32_t sample_rate)
   ^~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:499:12: note: shadowed declaration is here
   uint32_t sample_rate;
            ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:385:3: warning: declaration of 'channels' shadows a member of 'delay_line<short int>' [-Wshadow]
   delay_line(uint32_t frames, uint32_t channels, uint32_t sample_rate)
   ^~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:75:18: note: shadowed declaration is here
   const uint32_t channels;
                  ^~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>::cubeb_resampler_speex(InputProcessor*, OutputProcessor*, cubeb_stream*, cubeb_data_callback, void*) [with T = short int; InputProcessing = cubeb_resampler_speex_one_way<short int>; OutputProcessing = cubeb_resampler_speex_one_way<short int>; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:578:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = short int; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:293:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'output_processor' shadows a member of 'cubeb_resampler_speex<short int, cubeb_resampler_speex_one_way<short int>, cubeb_resampler_speex_one_way<short int> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:155:37: note: shadowed declaration is here
   std::unique_ptr<OutputProcessing> output_processor;
                                     ^~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'input_processor' shadows a member of 'cubeb_resampler_speex<short int, cubeb_resampler_speex_one_way<short int>, cubeb_resampler_speex_one_way<short int> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:154:36: note: shadowed declaration is here
   std::unique_ptr<InputProcessing> input_processor;
                                    ^~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>::cubeb_resampler_speex(InputProcessor*, OutputProcessor*, cubeb_stream*, cubeb_data_callback, void*) [with T = short int; InputProcessing = cubeb_resampler_speex_one_way<short int>; OutputProcessing = delay_line<short int>; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:585:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = short int; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:293:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'output_processor' shadows a member of 'cubeb_resampler_speex<short int, cubeb_resampler_speex_one_way<short int>, delay_line<short int> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:155:37: note: shadowed declaration is here
   std::unique_ptr<OutputProcessing> output_processor;
                                     ^~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'input_processor' shadows a member of 'cubeb_resampler_speex<short int, cubeb_resampler_speex_one_way<short int>, delay_line<short int> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:154:36: note: shadowed declaration is here
   std::unique_ptr<InputProcessing> input_processor;
                                    ^~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>::cubeb_resampler_speex(InputProcessor*, OutputProcessor*, cubeb_stream*, cubeb_data_callback, void*) [with T = short int; InputProcessing = delay_line<short int>; OutputProcessing = cubeb_resampler_speex_one_way<short int>; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:592:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = short int; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:293:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'output_processor' shadows a member of 'cubeb_resampler_speex<short int, delay_line<short int>, cubeb_resampler_speex_one_way<short int> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:155:37: note: shadowed declaration is here
   std::unique_ptr<OutputProcessing> output_processor;
                                     ^~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'input_processor' shadows a member of 'cubeb_resampler_speex<short int, delay_line<short int>, cubeb_resampler_speex_one_way<short int> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:154:36: note: shadowed declaration is here
   std::unique_ptr<InputProcessing> input_processor;
                                    ^~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'passthrough_resampler<T>::passthrough_resampler(cubeb_stream*, cubeb_data_callback, void*, uint32_t, uint32_t) [with T = float; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int); uint32_t = unsigned int]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:528:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = float; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:301:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:44:1: warning: declaration of 'sample_rate' shadows a member of 'passthrough_resampler<float>' [-Wshadow]
 passthrough_resampler<T>::passthrough_resampler(cubeb_stream * s,
 ^~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:112:12: note: shadowed declaration is here
   uint32_t sample_rate;
            ^~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h: In instantiation of 'cubeb_resampler_speex_one_way<T>::cubeb_resampler_speex_one_way(uint32_t, uint32_t, uint32_t, int) [with T = float; uint32_t = unsigned int]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:538:9:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = float; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:301:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:179:3: warning: declaration of 'source_rate' shadows a member of 'cubeb_resampler_speex_one_way<float>' [-Wshadow]
   cubeb_resampler_speex_one_way(uint32_t channels,
   ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:364:18: note: shadowed declaration is here
   const uint32_t source_rate;
                  ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:179:3: warning: declaration of 'channels' shadows a member of 'cubeb_resampler_speex_one_way<float>' [-Wshadow]
   cubeb_resampler_speex_one_way(uint32_t channels,
   ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:75:18: note: shadowed declaration is here
   const uint32_t channels;
                  ^~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h: In instantiation of 'delay_line<T>::delay_line(uint32_t, uint32_t, uint32_t) [with T = float; uint32_t = unsigned int]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:562:24:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = float; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:301:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:385:3: warning: declaration of 'sample_rate' shadows a member of 'delay_line<float>' [-Wshadow]
   delay_line(uint32_t frames, uint32_t channels, uint32_t sample_rate)
   ^~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:499:12: note: shadowed declaration is here
   uint32_t sample_rate;
            ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:385:3: warning: declaration of 'channels' shadows a member of 'delay_line<float>' [-Wshadow]
   delay_line(uint32_t frames, uint32_t channels, uint32_t sample_rate)
   ^~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:75:18: note: shadowed declaration is here
   const uint32_t channels;
                  ^~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>::cubeb_resampler_speex(InputProcessor*, OutputProcessor*, cubeb_stream*, cubeb_data_callback, void*) [with T = float; InputProcessing = cubeb_resampler_speex_one_way<float>; OutputProcessing = cubeb_resampler_speex_one_way<float>; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:578:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = float; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:301:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'output_processor' shadows a member of 'cubeb_resampler_speex<float, cubeb_resampler_speex_one_way<float>, cubeb_resampler_speex_one_way<float> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:155:37: note: shadowed declaration is here
   std::unique_ptr<OutputProcessing> output_processor;
                                     ^~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'input_processor' shadows a member of 'cubeb_resampler_speex<float, cubeb_resampler_speex_one_way<float>, cubeb_resampler_speex_one_way<float> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:154:36: note: shadowed declaration is here
   std::unique_ptr<InputProcessing> input_processor;
                                    ^~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>::cubeb_resampler_speex(InputProcessor*, OutputProcessor*, cubeb_stream*, cubeb_data_callback, void*) [with T = float; InputProcessing = cubeb_resampler_speex_one_way<float>; OutputProcessing = delay_line<float>; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:585:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = float; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:301:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'output_processor' shadows a member of 'cubeb_resampler_speex<float, cubeb_resampler_speex_one_way<float>, delay_line<float> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:155:37: note: shadowed declaration is here
   std::unique_ptr<OutputProcessing> output_processor;
                                     ^~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'input_processor' shadows a member of 'cubeb_resampler_speex<float, cubeb_resampler_speex_one_way<float>, delay_line<float> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:154:36: note: shadowed declaration is here
   std::unique_ptr<InputProcessing> input_processor;
                                    ^~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp: In instantiation of 'cubeb_resampler_speex<T, InputProcessing, OutputProcessing>::cubeb_resampler_speex(InputProcessor*, OutputProcessor*, cubeb_stream*, cubeb_data_callback, void*) [with T = float; InputProcessing = delay_line<float>; OutputProcessing = cubeb_resampler_speex_one_way<float>; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:592:12:   required from 'cubeb_resampler* cubeb_resampler_create_internal(cubeb_stream*, cubeb_stream_params*, cubeb_stream_params*, unsigned int, cubeb_data_callback, void*, cubeb_resampler_quality) [with T = float; cubeb_resampler = cubeb_resampler; cubeb_stream = cubeb_stream; cubeb_data_callback = long int (*)(cubeb_stream*, void*, const void*, void*, long int)]'
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:301:60:   required from here
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'output_processor' shadows a member of 'cubeb_resampler_speex<float, delay_line<float>, cubeb_resampler_speex_one_way<float> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:155:37: note: shadowed declaration is here
   std::unique_ptr<OutputProcessing> output_processor;
                                     ^~~~~~~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:90:1: warning: declaration of 'input_processor' shadows a member of 'cubeb_resampler_speex<float, delay_line<float>, cubeb_resampler_speex_one_way<float> >' [-Wshadow]
 cubeb_resampler_speex<T, InputProcessor, OutputProcessor>
 ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler.cpp:19:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_resampler_internal.h:154:36: note: shadowed declaration is here
   std::unique_ptr<InputProcessing> input_processor;
                                    ^~~~~~~~~~~~~~~
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/TGCBlob.cpp.o
[ 27%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/Volume.cpp.o
Scanning dependencies of target common
[ 27%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Analytics.cpp.o
[ 27%] Building CXX object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_panner.cpp.o
[ 27%] Building CXX object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_log.cpp.o
[ 27%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/preprocessor/PpAtom.cpp.o
In file included from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_log.cpp:10:
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_ringbuffer.h: In constructor 'audio_ring_buffer_base<T>::audio_ring_buffer_base(int, int)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_ringbuffer.h:368:5: warning: declaration of 'channel_count' shadows a member of 'audio_ring_buffer_base<T>' [-Wshadow]
     : channel_count(channel_count)
     ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_ringbuffer.h:475:7: note: shadowed declaration is here
   int channel_count;
       ^~~~~~~~~~~~~
[ 27%] Building C object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_strings.c.o
[ 27%] Building C object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_pulse.c.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_pulse.c:599:1: warning: no previous declaration for 'pulse_init' [-Wmissing-declarations]
 pulse_init(cubeb ** context, char const * context_name)
 ^~~~~~~~~~
[ 28%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/VolumeDisc.cpp.o
[ 28%] Building C object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_alsa.c.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_alsa.c:8: warning: "_DEFAULT_SOURCE" redefined
 #define _DEFAULT_SOURCE
 
<command-line>: note: this is the location of the previous definition
[ 28%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/CDUtils.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_alsa.c:748:1: warning: no previous declaration for 'alsa_init' [-Wmissing-declarations]
 alsa_init(cubeb ** context, char const * context_name)
 ^~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_alsa.c: In function 'alsa_stream_stop':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_alsa.c:1211:9: warning: declaration of 'r' shadows a previous local [-Wshadow]
     int r = alsa_stream_stop(stm->other_stream);
         ^
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_alsa.c:1205:7: note: shadowed declaration is here
   int r;
       ^
[ 28%] Building CXX object Externals/cubeb/CMakeFiles/cubeb.dir/src/cubeb_jack.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp:9: warning: "_DEFAULT_SOURCE" redefined
 #define _DEFAULT_SOURCE
 
<command-line>: note: this is the location of the previous definition
[ 29%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/preprocessor/PpContext.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp: In function 'int cbjack_process(jack_nframes_t, void*)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp:355:30: warning: comparison of integer expressions of different signedness: 'long int' and 'jack_nframes_t' {aka 'unsigned int'} [-Wsign-compare]
           for (long f = 0; f < nframes; f++) {
                            ~~^~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp:364:30: warning: comparison of integer expressions of different signedness: 'long int' and 'jack_nframes_t' {aka 'unsigned int'} [-Wsign-compare]
           for (long f = 0; f < nframes; f++) {
                            ~~^~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp:410:32: warning: comparison of integer expressions of different signedness: 'long int' and 'jack_nframes_t' {aka 'unsigned int'} [-Wsign-compare]
             for (long f = 0; f < nframes; f++) {
                              ~~^~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp:419:32: warning: comparison of integer expressions of different signedness: 'long int' and 'jack_nframes_t' {aka 'unsigned int'} [-Wsign-compare]
             for (long f = 0; f < nframes; f++) {
                              ~~^~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp: In function 'void cbjack_interleave_capture(cubeb_stream*, float**, jack_nframes_t, bool)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp:554:24: warning: comparison of integer expressions of different signedness: 'long int' and 'jack_nframes_t' {aka 'unsigned int'} [-Wsign-compare]
     for (long f = 0; f < nframes; f++) {
                      ~~^~~~~~~~~
[ 29%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/VolumeFileBlobReader.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp: In function 'int cbjack_enumerate_devices(cubeb*, cubeb_device_type, cubeb_device_collection*)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/cubeb/src/cubeb_jack.cpp:1034:23: warning: 'rate' may be used uninitialized in this function [-Wmaybe-uninitialized]
     cur->default_rate = rate;
     ~~~~~~~~~~~~~~~~~~^~~~~~
[ 30%] Linking CXX static library libcubeb.a
[ 30%] Built target cubeb
[ 30%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/preprocessor/PpScanner.cpp.o
[ 30%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/VolumeGC.cpp.o
[ 30%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/VolumeVerifier.cpp.o
[ 30%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/preprocessor/PpTokens.cpp.o
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/ColorUtil.cpp.o
[ 31%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/VolumeWad.cpp.o
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/CommonFuncs.cpp.o
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Config/Config.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWad.cpp:13:
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {long long unsigned int&}; _Tp = long long unsigned int; _Alloc = std::allocator<long long unsigned int>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<long long unsigned int>::iterator' {aka '__gnu_cxx::__normal_iterator<long long unsigned int*, std::vector<long long unsigned int> >'} changed in GCC 7.1
       vector<_Tp, _Alloc>::
       ^~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/vector.tcc: In member function 'virtual std::vector<long long unsigned int> DiscIO::VolumeWAD::GetContentOffsets() const':
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<long long unsigned int*, std::vector<long long unsigned int> >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
[ 31%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/VolumeWii.cpp.o
[ 31%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/propagateNoContraction.cpp.o
In file included from /usr/include/c++/8/bits/stl_algo.h:61,
                 from /usr/include/c++/8/algorithm:62,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:7:
/usr/include/c++/8/bits/stl_heap.h: In function 'void std::__adjust_heap(_RandomAccessIterator, _Distance, _Distance, _Tp, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >; _Distance = int; _Tp = DiscIO::VolumeVerifier::BlockToVerify; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::VolumeVerifier::SetUpHashing()::<lambda(const DiscIO::VolumeVerifier::BlockToVerify&, const DiscIO::VolumeVerifier::BlockToVerify&)> >]':
/usr/include/c++/8/bits/stl_heap.h:214:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
     __adjust_heap(_RandomAccessIterator __first, _Distance __holeIndex,
     ^~~~~~~~~~~~~
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Config/ConfigInfo.cpp.o
In file included from /usr/include/c++/8/algorithm:62,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:7:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__insertion_sort(_RandomAccessIterator, _RandomAccessIterator, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::VolumeVerifier::SetUpHashing()::<lambda(const DiscIO::VolumeVerifier::BlockToVerify&, const DiscIO::VolumeVerifier::BlockToVerify&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
     __insertion_sort(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Config/Layer.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {}; _Tp = DiscIO::RedumpVerifier::PotentialMatch; _Alloc = std::allocator<DiscIO::RedumpVerifier::PotentialMatch>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::RedumpVerifier::PotentialMatch>::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::RedumpVerifier::PotentialMatch*, std::vector<DiscIO::RedumpVerifier::PotentialMatch> >'} changed in GCC 7.1
       vector<_Tp, _Alloc>::
       ^~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {const DiscIO::Partition&}; _Tp = DiscIO::Partition; _Alloc = std::allocator<DiscIO::Partition>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::Partition>::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >'} changed in GCC 7.1
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {DiscIO::VolumeVerifier::BlockToVerify}; _Tp = DiscIO::VolumeVerifier::BlockToVerify; _Alloc = std::allocator<DiscIO::VolumeVerifier::BlockToVerify>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::VolumeVerifier::BlockToVerify>::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >'} changed in GCC 7.1
In file included from /usr/include/c++/8/map:60,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:5:
/usr/include/c++/8/bits/stl_tree.h: In function 'std::_Rb_tree<_Key, _Val, _KeyOfValue, _Compare, _Alloc>::iterator std::_Rb_tree<_Key, _Val, _KeyOfValue, _Compare, _Alloc>::_M_emplace_hint_unique(std::_Rb_tree<_Key, _Val, _KeyOfValue, _Compare, _Alloc>::const_iterator, _Args&& ...) [with _Args = {const std::piecewise_construct_t&, std::tuple<const DiscIO::Partition&>, std::tuple<>}; _Key = DiscIO::Partition; _Val = std::pair<const DiscIO::Partition, unsigned int>; _KeyOfValue = std::_Select1st<std::pair<const DiscIO::Partition, unsigned int> >; _Compare = std::less<DiscIO::Partition>; _Alloc = std::allocator<std::pair<const DiscIO::Partition, unsigned int> >]':
/usr/include/c++/8/bits/stl_tree.h:2411:7: note: parameter passing for argument of type 'std::_Rb_tree<DiscIO::Partition, std::pair<const DiscIO::Partition, unsigned int>, std::_Select1st<std::pair<const DiscIO::Partition, unsigned int> >, std::less<DiscIO::Partition>, std::allocator<std::pair<const DiscIO::Partition, unsigned int> > >::const_iterator' {aka 'std::_Rb_tree_const_iterator<std::pair<const DiscIO::Partition, unsigned int> >'} changed in GCC 7.1
       _Rb_tree<_Key, _Val, _KeyOfValue, _Compare, _Alloc>::
       ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/c++/8/map:61,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:5:
/usr/include/c++/8/bits/stl_map.h: In static member function 'static _Res std::_Function_handler<_Res(_ArgTypes ...), _Functor>::_M_invoke(const std::_Any_data&, _ArgTypes&& ...) [with _Res = std::unique_ptr<std::__future_base::_Result_base, std::__future_base::_Result_base::_Deleter>; _Functor = std::__future_base::_Task_setter<std::unique_ptr<std::__future_base::_Result<void>, std::__future_base::_Result_base::_Deleter>, std::thread::_Invoker<std::tuple<DiscIO::VolumeVerifier::Process()::<lambda(size_t, u64)>, unsigned int, long long unsigned int> >, void>; _ArgTypes = {}]':
/usr/include/c++/8/bits/stl_map.h:499:8: note: parameter passing for argument of type 'std::_Rb_tree<DiscIO::Partition, std::pair<const DiscIO::Partition, unsigned int>, std::_Select1st<std::pair<const DiscIO::Partition, unsigned int> >, std::less<DiscIO::Partition>, std::allocator<std::pair<const DiscIO::Partition, unsigned int> > >::const_iterator' {aka 'std::_Rb_tree_const_iterator<std::pair<const DiscIO::Partition, unsigned int> >'} changed in GCC 7.1
    __i = _M_t._M_emplace_hint_unique(__i, std::piecewise_construct,
/usr/include/c++/8/bits/stl_map.h:499:8: note: parameter passing for argument of type 'std::_Rb_tree<DiscIO::Partition, std::pair<const DiscIO::Partition, unsigned int>, std::_Select1st<std::pair<const DiscIO::Partition, unsigned int> >, std::less<DiscIO::Partition>, std::allocator<std::pair<const DiscIO::Partition, unsigned int> > >::const_iterator' {aka 'std::_Rb_tree_const_iterator<std::pair<const DiscIO::Partition, unsigned int> >'} changed in GCC 7.1
    __i = _M_t._M_emplace_hint_unique(__i, std::piecewise_construct,
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In member function 'std::vector<DiscIO::RedumpVerifier::PotentialMatch> DiscIO::RedumpVerifier::ScanDatfile(const std::vector<unsigned char>&, const string&)':
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::RedumpVerifier::PotentialMatch*, std::vector<DiscIO::RedumpVerifier::PotentialMatch> >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
[ 31%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/reflection.cpp.o
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Crypto/AES.cpp.o
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Crypto/bn.cpp.o
In file included from /usr/include/c++/8/algorithm:62,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:7:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__introsort_loop(_RandomAccessIterator, _RandomAccessIterator, _Size, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >; _Size = int; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::VolumeVerifier::SetUpHashing()::<lambda(const DiscIO::VolumeVerifier::BlockToVerify&, const DiscIO::VolumeVerifier::BlockToVerify&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
     __introsort_loop(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_algo.h:1954:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
    std::__introsort_loop(__cut, __last, __depth_limit, __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h: In member function 'void DiscIO::VolumeVerifier::SetUpHashing()':
/usr/include/c++/8/bits/stl_algo.h:1968:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
    std::__introsort_loop(__first, __last,
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
     std::__lg(__last - __first) * 2,
     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     __comp);
     ~~~~~~~              
/usr/include/c++/8/bits/stl_algo.h:1885:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
    std::__insertion_sort(__first, __first + int(_S_threshold), __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1890:23: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
  std::__insertion_sort(__first, __last, __comp);
  ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Crypto/ec.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In member function 'bool DiscIO::VolumeVerifier::CheckPartition(const DiscIO::Partition&)':
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::VolumeVerifier::BlockToVerify*, std::vector<DiscIO::VolumeVerifier::BlockToVerify> >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
In file included from /usr/include/c++/8/vector:64,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.h:12,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeVerifier.cpp:5:
/usr/include/c++/8/bits/stl_vector.h: In member function 'std::vector<DiscIO::Partition> DiscIO::VolumeVerifier::CheckPartitions()':
/usr/include/c++/8/bits/stl_vector.h:1085:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    _M_realloc_insert(end(), __x);
    ^~~~~~~~~~~~~~~~~
[ 31%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/WbfsBlob.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WbfsBlob.h:9,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WbfsBlob.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {File::IOFile, long long unsigned int&, const long long unsigned int&}; _Tp = DiscIO::WbfsFileReader::FileEntry; _Alloc = std::allocator<DiscIO::WbfsFileReader::FileEntry>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::WbfsFileReader::FileEntry>::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::WbfsFileReader::FileEntry*, std::vector<DiscIO::WbfsFileReader::FileEntry> >'} changed in GCC 7.1
       vector<_Tp, _Alloc>::
       ^~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::WbfsFileReader::FileEntry>::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::WbfsFileReader::FileEntry*, std::vector<DiscIO::WbfsFileReader::FileEntry> >'} changed in GCC 7.1
/usr/include/c++/8/bits/vector.tcc: In function 'bool DiscIO::WbfsFileReader::AddFileToList(File::IOFile)':
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WbfsFileReader::FileEntry*, std::vector<DiscIO::WbfsFileReader::FileEntry> >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/vector.tcc: In member function 'bool DiscIO::WbfsFileReader::AddFileToList(File::IOFile)':
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WbfsFileReader::FileEntry*, std::vector<DiscIO::WbfsFileReader::FileEntry> >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
[ 31%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/RemoveTree.cpp.o
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Debug/MemoryPatches.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /usr/include/c++/8/functional:62,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {const DiscIO::Partition&}; _Tp = DiscIO::Partition; _Alloc = std::allocator<DiscIO::Partition>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::Partition>::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >'} changed in GCC 7.1
       vector<_Tp, _Alloc>::
       ^~~~~~~~~~~~~~~~~~~
In file included from /usr/include/c++/8/vector:64,
                 from /usr/include/c++/8/functional:62,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/VolumeWii.cpp:5:
/usr/include/c++/8/bits/stl_vector.h: In member function 'virtual std::vector<DiscIO::Partition> DiscIO::VolumeWii::GetPartitions() const':
/usr/include/c++/8/bits/stl_vector.h:1085:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    _M_realloc_insert(end(), __x);
    ^~~~~~~~~~~~~~~~~
[ 31%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/WIABlob.cpp.o
[ 31%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Debug/OSThread.cpp.o
[ 32%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Debug/Watches.cpp.o
[ 32%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/DynamicLibrary.cpp.o
[ 32%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/Scan.cpp.o
[ 32%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/ENetUtil.cpp.o
[ 32%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/WIACompression.cpp.o
In file included from /usr/include/c++/8/bits/stl_algo.h:61,
                 from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/MultithreadedCompressor.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:19,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/stl_heap.h: In function 'void std::__adjust_heap(_RandomAccessIterator, _Distance, _Distance, _Tp, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >; _Distance = int; _Tp = DiscIO::Partition; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = true]::<lambda(const DiscIO::Partition&, const DiscIO::Partition&)> >]':
/usr/include/c++/8/bits/stl_heap.h:214:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
     __adjust_heap(_RandomAccessIterator __first, _Distance __holeIndex,
     ^~~~~~~~~~~~~
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/MultithreadedCompressor.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:19,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__insertion_sort(_RandomAccessIterator, _RandomAccessIterator, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = true]::<lambda(const DiscIO::Partition&, const DiscIO::Partition&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
     __insertion_sort(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
In file included from /usr/include/c++/8/bits/stl_algo.h:61,
                 from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/MultithreadedCompressor.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:19,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/stl_heap.h: In function 'void std::__adjust_heap(_RandomAccessIterator, _Distance, _Distance, _Tp, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >; _Distance = int; _Tp = DiscIO::Partition; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = false]::<lambda(const DiscIO::Partition&, const DiscIO::Partition&)> >]':
/usr/include/c++/8/bits/stl_heap.h:214:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
     __adjust_heap(_RandomAccessIterator __first, _Distance __holeIndex,
     ^~~~~~~~~~~~~
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/MultithreadedCompressor.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:19,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__insertion_sort(_RandomAccessIterator, _RandomAccessIterator, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = false]::<lambda(const DiscIO::Partition&, const DiscIO::Partition&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
     __insertion_sort(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_algo.h:1840:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
[ 32%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/File.cpp.o
[ 32%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/FileSearch.cpp.o
[ 32%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/FileUtil.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/Blob.h:21,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:18,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {}; _Tp = DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry; _Alloc = std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> >::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >'} changed in GCC 7.1
       vector<_Tp, _Alloc>::
       ^~~~~~~~~~~~~~~~~~~
[ 32%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/ShaderLang.cpp.o
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {}; _Tp = DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry; _Alloc = std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> >::iterator' {aka '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >'} changed in GCC 7.1
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/MultithreadedCompressor.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:19,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__introsort_loop(_RandomAccessIterator, _RandomAccessIterator, _Size, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >; _Size = int; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = false]::<lambda(const DiscIO::Partition&, const DiscIO::Partition&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
     __introsort_loop(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_algo.h:1954:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    std::__introsort_loop(__cut, __last, __depth_limit, __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h: In static member function 'static DiscIO::ConversionResultCode DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = false]':
/usr/include/c++/8/bits/stl_algo.h:1968:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    std::__introsort_loop(__first, __last,
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
     std::__lg(__last - __first) * 2,
     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     __comp);
     ~~~~~~~              
/usr/include/c++/8/bits/stl_algo.h:1885:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    std::__insertion_sort(__first, __first + int(_S_threshold), __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1890:23: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
  std::__insertion_sort(__first, __last, __comp);
  ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
[ 32%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/FloatUtils.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/FileUtil.cpp:14:
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_realloc_insert(std::vector<_Tp, _Alloc>::iterator, _Args&& ...) [with _Args = {const File::FSTEntry&}; _Tp = File::FSTEntry; _Alloc = std::allocator<File::FSTEntry>]':
/usr/include/c++/8/bits/vector.tcc:413:7: note: parameter passing for argument of type 'std::vector<File::FSTEntry>::iterator' {aka '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >'} changed in GCC 7.1
       vector<_Tp, _Alloc>::
       ^~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h: In function 'void std::__introsort_loop(_RandomAccessIterator, _RandomAccessIterator, _Size, _Compare) [with _RandomAccessIterator = __gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >; _Size = int; _Compare = __gnu_cxx::__ops::_Iter_comp_iter<DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = true]::<lambda(const DiscIO::Partition&, const DiscIO::Partition&)> >]':
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
     __introsort_loop(_RandomAccessIterator __first,
     ^~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_algo.h:1940:5: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
/usr/include/c++/8/bits/stl_algo.h:1954:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    std::__introsort_loop(__cut, __last, __depth_limit, __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h: In static member function 'static DiscIO::ConversionResultCode DiscIO::WIARVZFileReader<RVZ>::SetUpDataEntriesForWriting(const DiscIO::VolumeDisc*, int, u64, u32*, std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::RawDataEntry>*, std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>*, std::vector<const DiscIO::FileSystem*>*) [with bool RVZ = true]':
/usr/include/c++/8/bits/stl_algo.h:1968:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    std::__introsort_loop(__first, __last,
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
     std::__lg(__last - __first) * 2,
     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     __comp);
     ~~~~~~~              
/usr/include/c++/8/bits/stl_algo.h:1885:25: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
    std::__insertion_sort(__first, __first + int(_S_threshold), __comp);
    ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:1890:23: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::Partition*, std::vector<DiscIO::Partition> >' changed in GCC 7.1
  std::__insertion_sort(__first, __last, __comp);
  ~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
[ 32%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/WiiEncryptionCache.cpp.o
In file included from /usr/include/c++/8/bits/stl_algobase.h:71,
                 from /usr/include/c++/8/bits/char_traits.h:39,
                 from /usr/include/c++/8/string:40,
                 from /usr/include/c++/8/stdexcept:39,
                 from /usr/include/c++/8/array:39,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:7,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/predefined_ops.h: In member function 'bool __gnu_cxx::__ops::_Iter_pred<_Predicate>::operator()(_Iterator) [with _Iterator = __gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >; _Predicate = DiscIO::WIARVZFileReader<RVZ>::ProcessAndCompress(DiscIO::WIARVZFileReader<RVZ>::CompressThreadState*, DiscIO::WIARVZFileReader<RVZ>::CompressParameters, const std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>&, const std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>&, const DiscIO::FileSystem*, std::map<DiscIO::WIARVZFileReader<RVZ>::ReuseID, typename std::conditional<RVZ, DiscIO::WIARVZFileReader<RVZ>::RVZGroupEntry, DiscIO::WIARVZFileReader<RVZ>::WIAGroupEntry>::type>*, std::mutex*, u64, u64, bool, bool) [with bool RVZ = false]::<lambda(const auto:1&)>]':
/usr/include/c++/8/bits/predefined_ops.h:282:2: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >' changed in GCC 7.1
  operator()(_Iterator __it)
  ^~~~~~~~
/usr/include/c++/8/bits/predefined_ops.h:282:2: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >' changed in GCC 7.1
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/Blob.h:21,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:18,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In static member function 'static DiscIO::ConversionResult<DiscIO::WIARVZFileReader<RVZ>::OutputParameters> DiscIO::WIARVZFileReader<RVZ>::ProcessAndCompress(DiscIO::WIARVZFileReader<RVZ>::CompressThreadState*, DiscIO::WIARVZFileReader<RVZ>::CompressParameters, const std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>&, const std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>&, const DiscIO::FileSystem*, std::map<DiscIO::WIARVZFileReader<RVZ>::ReuseID, typename std::conditional<RVZ, DiscIO::WIARVZFileReader<RVZ>::RVZGroupEntry, DiscIO::WIARVZFileReader<RVZ>::WIAGroupEntry>::type>*, std::mutex*, u64, u64, bool, bool) [with bool RVZ = false]':
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/MultithreadedCompressor.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:19,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h:140:14: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >' changed in GCC 7.1
    if (__pred(__first))
        ~~~~~~^~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:144:14: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >' changed in GCC 7.1
    if (__pred(__first))
        ~~~~~~^~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:148:14: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<false>::WIAOutputParametersEntry> > >' changed in GCC 7.1
    if (__pred(__first))
        ~~~~~~^~~~~~~~~
In file included from /usr/include/c++/8/bits/stl_algobase.h:71,
                 from /usr/include/c++/8/bits/char_traits.h:39,
                 from /usr/include/c++/8/string:40,
                 from /usr/include/c++/8/stdexcept:39,
                 from /usr/include/c++/8/array:39,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:7,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/predefined_ops.h: In member function 'bool __gnu_cxx::__ops::_Iter_pred<_Predicate>::operator()(_Iterator) [with _Iterator = __gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >; _Predicate = DiscIO::WIARVZFileReader<RVZ>::ProcessAndCompress(DiscIO::WIARVZFileReader<RVZ>::CompressThreadState*, DiscIO::WIARVZFileReader<RVZ>::CompressParameters, const std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>&, const std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>&, const DiscIO::FileSystem*, std::map<DiscIO::WIARVZFileReader<RVZ>::ReuseID, typename std::conditional<RVZ, DiscIO::WIARVZFileReader<RVZ>::RVZGroupEntry, DiscIO::WIARVZFileReader<RVZ>::WIAGroupEntry>::type>*, std::mutex*, u64, u64, bool, bool) [with bool RVZ = true]::<lambda(const auto:1&)>]':
/usr/include/c++/8/bits/predefined_ops.h:282:2: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >' changed in GCC 7.1
  operator()(_Iterator __it)
  ^~~~~~~~
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/Blob.h:21,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:18,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/vector.tcc: In static member function 'static DiscIO::ConversionResult<DiscIO::WIARVZFileReader<RVZ>::OutputParameters> DiscIO::WIARVZFileReader<RVZ>::ProcessAndCompress(DiscIO::WIARVZFileReader<RVZ>::CompressThreadState*, DiscIO::WIARVZFileReader<RVZ>::CompressParameters, const std::vector<DiscIO::WIARVZFileReader<RVZ>::PartitionEntry>&, const std::vector<DiscIO::WIARVZFileReader<RVZ>::DataEntry>&, const DiscIO::FileSystem*, std::map<DiscIO::WIARVZFileReader<RVZ>::ReuseID, typename std::conditional<RVZ, DiscIO::WIARVZFileReader<RVZ>::RVZGroupEntry, DiscIO::WIARVZFileReader<RVZ>::WIAGroupEntry>::type>*, std::mutex*, u64, u64, bool, bool) [with bool RVZ = true]':
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
/usr/include/c++/8/bits/vector.tcc:109:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >' changed in GCC 7.1
    _M_realloc_insert(end(), std::forward<_Args>(__args)...);
    ^~~~~~~~~~~~~~~~~
In file included from /usr/include/c++/8/functional:65,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/MultithreadedCompressor.h:8,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.h:19,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/DiscIO/WIABlob.cpp:5:
/usr/include/c++/8/bits/stl_algo.h:140:14: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >' changed in GCC 7.1
    if (__pred(__first))
        ~~~~~~^~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:144:14: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >' changed in GCC 7.1
    if (__pred(__first))
        ~~~~~~^~~~~~~~~
/usr/include/c++/8/bits/stl_algo.h:148:14: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry*, std::vector<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry, std::allocator<DiscIO::WIARVZFileReader<true>::RVZOutputParametersEntry> > >' changed in GCC 7.1
    if (__pred(__first))
        ~~~~~~^~~~~~~~~
In file included from /usr/include/c++/8/vector:64,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/FileUtil.cpp:14:
/usr/include/c++/8/bits/stl_vector.h: In function 'File::FSTEntry File::ScanDirectoryTree(const string&, bool)':
/usr/include/c++/8/bits/stl_vector.h:1085:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<File::FSTEntry*, std::vector<File::FSTEntry> >' changed in GCC 7.1
    _M_realloc_insert(end(), __x);
    ^~~~~~~~~~~~~~~~~
[ 33%] Building CXX object Source/Core/DiscIO/CMakeFiles/discio.dir/WiiSaveBanner.cpp.o
[ 33%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/GekkoDisassembler.cpp.o
[ 33%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Hash.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/Hash.cpp: In function 'u32 Common::HashEctor(const u8*, size_t)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/Hash.cpp:102:21: warning: comparison of integer expressions of different signedness: 'int' and 'size_t' {aka 'unsigned int'} [-Wsign-compare]
   for (int i = 0; i < length; i++)
                   ~~^~~~~~~~
[ 33%] Linking CXX static library libdiscio.a
[ 33%] Built target discio
[ 33%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/HttpRequest.cpp.o
Scanning dependencies of target audiocommon
[ 33%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/AudioCommon.cpp.o
[ 34%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Image.cpp.o
[ 34%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/IniFile.cpp.o
[ 35%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/AudioStretcher.cpp.o
[ 35%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/SymbolTable.cpp.o
[ 35%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/CubebStream.cpp.o
[ 35%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/CubebUtils.cpp.o
[ 35%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/JitRegister.cpp.o
[ 35%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/Mixer.cpp.o
[ 35%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Logging/LogManager.cpp.o
[ 35%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/SurroundDecoder.cpp.o
[ 35%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/MachineIndependent/Versions.cpp.o
[ 35%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/NullSoundStream.cpp.o
[ 35%] Building CXX object Source/Core/AudioCommon/CMakeFiles/audiocommon.dir/WaveFile.cpp.o
[ 35%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/MathUtil.cpp.o
[ 35%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/OGLCompilersDLL/InitializeDll.cpp.o
[ 35%] Linking CXX static library libaudiocommon.a
[ 35%] Built target audiocommon
[ 36%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/disassemble.cpp.o
[ 36%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/doc.cpp.o
[ 36%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/GlslangToSpv.cpp.o
[ 36%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Matrix.cpp.o
[ 36%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/MD5.cpp.o
[ 36%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/MemArena.cpp.o
[ 36%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/MemoryUtil.cpp.o
[ 36%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/InReadableOrder.cpp.o
[ 36%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/MsgHandler.cpp.o
[ 36%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/NandPaths.cpp.o
[ 36%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/Logger.cpp.o
[ 36%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/SpvBuilder.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/NandPaths.cpp: In function 'std::__cxx11::string Common::EscapeFileName(const string&)':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/NandPaths.cpp:114:12: warning: comparison is always true due to limited range of data type [-Wtype-limits]
     if ((c >= 0 && c <= 0x1F) || chars_to_replace.find(c) != chars_to_replace.end())
          ~~^~~~
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Network.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/PcapFile.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/PerformanceCounter.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Profiler.cpp.o
[ 37%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/SpvPostProcess.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/QoSSession.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Random.cpp.o
[ 37%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/SPIRV/SPVRemapper.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/SDCardUtil.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/SFMLHelper.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/SettingsHandler.cpp.o
[ 37%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/StringUtil.cpp.o
[ 37%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/StandAlone/ResourceLimits.cpp.o
In file included from /usr/include/c++/8/vector:69,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/glslang/SPIRV/SPVRemapper.h:40,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/glslang/SPIRV/SPVRemapper.cpp:36:
/usr/include/c++/8/bits/vector.tcc: In member function 'void std::vector<_Tp, _Alloc>::_M_fill_insert(std::vector<_Tp, _Alloc>::iterator, std::vector<_Tp, _Alloc>::size_type, const value_type&) [with _Tp = long long unsigned int; _Alloc = std::allocator<long long unsigned int>]':
/usr/include/c++/8/bits/vector.tcc:478:5: note: parameter passing for argument of type 'std::vector<long long unsigned int>::iterator' {aka '__gnu_cxx::__normal_iterator<long long unsigned int*, std::vector<long long unsigned int> >'} changed in GCC 7.1
     vector<_Tp, _Alloc>::
     ^~~~~~~~~~~~~~~~~~~
In file included from /usr/include/c++/8/vector:64,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/glslang/SPIRV/SPVRemapper.h:40,
                 from /home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Externals/glslang/SPIRV/SPVRemapper.cpp:36:
/usr/include/c++/8/bits/stl_vector.h: In member function 'spv::Id spv::spirvbin_t::localId(spv::Id, spv::Id)':
/usr/include/c++/8/bits/stl_vector.h:847:4: note: parameter passing for argument of type '__gnu_cxx::__normal_iterator<long long unsigned int*, std::vector<long long unsigned int> >' changed in GCC 7.1
    _M_fill_insert(end(), __new_size - size(), __x);
    ^~~~~~~~~~~~~~
[ 37%] Building CXX object Externals/glslang/CMakeFiles/glslang.dir/glslang/OSDependent/Unix/ossource.cpp.o
[ 38%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/SymbolDB.cpp.o
[ 39%] Linking CXX static library libglslang.a
[ 39%] Built target glslang
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Thread.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Timer.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/TraversalClient.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/UPnP.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Version.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Logging/ConsoleListenerNix.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/Arm64Emitter.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/ArmCPUDetect.cpp.o
[ 39%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/GenericFPURoundMode.cpp.o
[ 40%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/GL/GLContext.cpp.o
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp: In member function 'void CPUInfo::Detect()':
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:91:18: error: 'HWCAP_FP' was not declared in this scope
   bFP = hwcaps & HWCAP_FP;
                  ^~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:91:18: note: suggested alternative: 'HWCAP_FPA'
   bFP = hwcaps & HWCAP_FP;
                  ^~~~~~~~
                  HWCAP_FPA
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:92:21: error: 'HWCAP_ASIMD' was not declared in this scope
   bASIMD = hwcaps & HWCAP_ASIMD;
                     ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:92:21: note: suggested alternative: 'HWCAP_IDIV'
   bASIMD = hwcaps & HWCAP_ASIMD;
                     ^~~~~~~~~~~
                     HWCAP_IDIV
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:93:19: error: 'HWCAP_AES' was not declared in this scope
   bAES = hwcaps & HWCAP_AES;
                   ^~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:93:19: note: suggested alternative: 'HWCAP2_AES'
   bAES = hwcaps & HWCAP_AES;
                   ^~~~~~~~~
                   HWCAP2_AES
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:94:21: error: 'HWCAP_CRC32' was not declared in this scope
   bCRC32 = hwcaps & HWCAP_CRC32;
                     ^~~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:94:21: note: suggested alternative: 'HWCAP2_CRC32'
   bCRC32 = hwcaps & HWCAP_CRC32;
                     ^~~~~~~~~~~
                     HWCAP2_CRC32
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:95:20: error: 'HWCAP_SHA1' was not declared in this scope
   bSHA1 = hwcaps & HWCAP_SHA1;
                    ^~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:95:20: note: suggested alternative: 'HWCAP2_SHA1'
   bSHA1 = hwcaps & HWCAP_SHA1;
                    ^~~~~~~~~~
                    HWCAP2_SHA1
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:96:20: error: 'HWCAP_SHA2' was not declared in this scope
   bSHA2 = hwcaps & HWCAP_SHA2;
                    ^~~~~~~~~~
/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/Source/Core/Common/ArmCPUDetect.cpp:96:20: note: suggested alternative: 'HWCAP2_SHA2'
   bSHA2 = hwcaps & HWCAP_SHA2;
                    ^~~~~~~~~~
                    HWCAP2_SHA2
[ 40%] Building CXX object Source/Core/Common/CMakeFiles/common.dir/GL/GLUtil.cpp.o
make[2]: *** [Source/Core/Common/CMakeFiles/common.dir/build.make:726: Source/Core/Common/CMakeFiles/common.dir/ArmCPUDetect.cpp.o] Error 1
make[2]: *** Waiting for unfinished jobs....
/tmp/ccvaiOU3.s: Assembler messages:
/tmp/ccvaiOU3.s:779: Error: selected processor does not support requested special purpose register -- `mrs r8,ctr_el0'
/tmp/ccvaiOU3.s:811: Error: bad instruction `dc civac,r10'
/tmp/ccvaiOU3.s:838: Error: bad instruction `ic ivau,r8'
/tmp/ccvaiOU3.s:889: Error: selected processor does not support requested special purpose register -- `mrs r4,ctr_el0'
/tmp/ccvaiOU3.s:924: Error: bad instruction `dc civac,r4'
/tmp/ccvaiOU3.s:951: Error: bad instruction `ic ivau,r6'
make[2]: *** [Source/Core/Common/CMakeFiles/common.dir/build.make:713: Source/Core/Common/CMakeFiles/common.dir/Arm64Emitter.cpp.o] Error 1
make[1]: *** [CMakeFiles/Makefile2:1167: Source/Core/Common/CMakeFiles/common.dir/all] Error 2
make: *** [Makefile:152: all] Error 2
/home/pi
Could not successfully build lr-dolphin - Gamecube/Wii emulator - Dolphin port for libretro (/home/pi/RetroPie-Setup/tmp/build/lr-dolphin/build/dolphin_libretro.so not found).

Log ended at: Sun Dec 27 13:34:20 EST 2020
Total running time: 0 hours, 6 mins, 40 secs
```
I'm  don't know how to fix this error. I'm using the st
