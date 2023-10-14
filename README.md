# I-have-bug-whith-error--1-in-pojav-launcher-Help-me-decide-
When starting Forge 1.16.5 it throws error -1 and asks you to look at the log


--------- beginning with launcher debug
Info: Launcher version: edelweiss-20230928-9484d0c-v3_openjdk
Info: Architecture: arm64
Info: Device model: Xiaomi M2103K19PG
Info: API version: 33
Info: Selected Minecraft version: 1.16.5-forge-36.2.34
Info: Custom Java arguments: ""
Added custom env: TMPDIR=/data/user/0/net.kdt.pojavlaunch/cache
Added custom env: AWTSTUB_WIDTH=2400
Added custom env: FORCE_VSYNC=false
Added custom env: POJAV_NATIVEDIR=/data/app/~~Q09GxqqFIqivJBX1DC1dbQ==/net.kdt.pojavlaunch-rwWh23b5rBnB2SUwnPHc3g==/lib/arm64
Added custom env: REGAL_GL_VERSION=4.5
Added custom env: REGAL_GL_VENDOR=Android
Added custom env: LIBGL_MIPMAP=3
Added custom env: allow_higher_compat_version=true
Added custom env: MESA_GLSL_CACHE_DIR=/data/user/0/net.kdt.pojavlaunch/cache
Added custom env: HOME=/storage/emulated/0/Android/data/net.kdt.pojavlaunch/files
Added custom env: PATH=/data/user/0/net.kdt.pojavlaunch/runtimes/Internal/bin:/product/bin:/apex/com.android.runtime/bin:/apex/com.android.art/bin:/system_ext/bin:/system/bin:/system/xbin:/odm/bin:/vendor/bin:/vendor/xbin
Added custom env: LIBGL_NOINTOVLHACK=1
Added custom env: force_glsl_extensions_warn=true
Added custom env: LIBGL_NORMALIZE=1
Added custom env: LD_LIBRARY_PATH=/data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/jli:/data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64:/system/lib64:/vendor/lib64:/vendor/lib64/hw:/data/app/~~Q09GxqqFIqivJBX1DC1dbQ==/net.kdt.pojavlaunch-rwWh23b5rBnB2SUwnPHc3g==/lib/arm64
Added custom env: LIBGL_NOERROR=1
Added custom env: POJAV_RENDERER=opengles2
Added custom env: LIBGL_ES=2
Added custom env: VTEST_SOCKET_NAME=/data/user/0/net.kdt.pojavlaunch/cache/.virgl_test
Added custom env: MESA_LOADER_DRIVER_OVERRIDE=zink
Added custom env: MESA_GLSL_VERSION_OVERRIDE=460
Added custom env: JAVA_HOME=/data/user/0/net.kdt.pojavlaunch/runtimes/Internal
Added custom env: MESA_GL_VERSION_OVERRIDE=4.6
Added custom env: allow_glsl_extension_directive_midshader=true
Added custom env: REGAL_GL_RENDERER=Regal
Added custom env: AWTSTUB_HEIGHT=1080
Initialising gl4es
v1.1.5 built on Sep 27 2023 17:42:09
Using GLES 2.0 backend
loaded: libGLESv2.so
loaded: libEGL.so
Using GLES 2.0 backend
Hardware Full NPOT detected and used
Extension GL_EXT_blend_minmax  detected and used
FBO are in core, and so used
PointSprite are in core, and so used
CubeMap are in core, and so used
BlendColor is in core, and so used
Blend Subtract is in core, and so used
Blend Function and Equation Separation is in core, and so used
Texture Mirrored Repeat is in core, and so used
Extension GL_OES_mapbuffer  detected
Extension GL_OES_element_index_uint  detected and used
Extension GL_OES_packed_depth_stencil  detected and used
Extension GL_OES_depth24  detected and used
Extension GL_OES_rgb8_rgba8  detected and used
Extension GL_EXT_texture_format_BGRA8888  detected and used
Extension GL_OES_depth_texture  detected and used
Extension GL_OES_texture_stencil8  detected and used
Extension GL_EXT_texture_rg  detected and used
Extension GL_EXT_color_buffer_float  detected and used
Extension GL_EXT_color_buffer_half_float  detected and used
high precision float in fragment shader available and used
Max vertex attrib: 32
Extension GL_OES_standard_derivatives  detected and used
Extension GL_ARM_shader_framebuffer_fetch detected and used
Extension GL_OES_get_program_binary  detected and used
Number of supported Program Binary Format: 1
Max texture size: 16383
Max Varying Vector: 31
Texture Units: 16/16 (hardware: 64), Max lights: 8, Max planes: 6
Extension GL_EXT_texture_filter_anisotropic  detected and used
Max Anisotropic filtering: 16
Hardware vendor is ARM
GLSL 300 es supported
GLSL 310 es supported and used
GLSL 320 es supported
Max Color Attachments: 8 / Draw buffers: 8
sRGB surface supported
EGLImage to Texture2D supported
EGLImage to RenderBuffer supported
ignore MipMap
glGetError() always return GL_NOERROR
Targeting OpenGL 2.1
No hack in shader converter to define overloaded function with int
Not trying to batch small subsequent glDrawXXXX
try to use VBO
glXMakeCurrent FBO workaround enabled
FBO workaround for using binded texture enabled
Force texture for Attachment color0 on FBO
Hack to trigger a SwapBuffers when a Full Framebuffer Blit on default FBO is done
Force normals to be normalized on FPE shaders
glX Will try to recycle EGL Surface
Current folder is:/
--------- beginning of main
I/jrelog  ( 5867): dlopen libgl4es_114.so success
I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/jli/libjli.so success

I/jrelog  ( 5867): dlopen libjvm.so failed: dlopen failed: library "libjvm.so" not found

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/server/libjvm.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libverify.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjava.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libnet.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libnio.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libawt.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libawt_headless.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libfreetype.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libfontmanager.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libinstrument.so failed: dlopen failed: library "libtinyiconv.so" not found: needed by /data/data/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libinstrument.so in namespace clns-4

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libnet.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libtinyiconv.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjsound.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/liblcms.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libverify.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/server/libjvm.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libnio.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libnpt.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjsig.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libfontmanager.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjsdt.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libunpack.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjpeg.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libj2gss.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libawt_headless.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libsctp.so success
I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libzip.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libfreetype.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libj2pcsc.so success
I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libawt_xawt.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjava_crw_demo.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libmlib_image.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjaas_unix.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libhprof.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjava.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libdt_socket.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjawt.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libmanagement.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libjdwp.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/jli/libjli.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libawt.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libj2pkcs11.so success

I/jrelog  ( 5867): dlopen /data/user/0/net.kdt.pojavlaunch/runtimes/Internal/lib/aarch64/libsunec.so success

I/jrelog  ( 5867): dlopen /data/app/~~Q09GxqqFIqivJBX1DC1dbQ==/net.kdt.pojavlaunch-rwWh23b5rBnB2SUwnPHc3g==/lib/arm64/libopenal.so success

I/jrelog  ( 5867): Done processing args

I/jrelog  ( 5867): Found JLI lib
I/jrelog  ( 5867): Calling JLI_Launch

OpenJDK 64-Bit Server VM warning: No monotonic clock was available - timed services may be adversely affected if the time-of-day clock changes
2023-10-14 19:19:22,699 main ERROR appender Console has no parameter that matches element Policies
[19:19:23] [main/INFO]: ModLauncher running: args [--username, MonkiDKosta, --version, 1.16.5, --gameDir, /storage/emulated/0/Android/data/net.kdt.pojavlaunch/files/.minecraft, --assetsDir, /storage/emulated/0/Android/data/net.kdt.pojavlaunch/files/.minecraft/assets, --assetIndex, 1.16, --uuid, 00000000000000000000000000000000, --accessToken, ❄❄❄❄❄❄❄❄, --userType, mojang, --versionType, release, --launchTarget, fmlclient, --fml.forgeVersion, 36.2.34, --fml.mcVersion, 1.16.5, --fml.forgeGroup, net.minecraftforge, --fml.mcpVersion, 20210115.111550]
[19:19:23] [main/INFO]: ModLauncher 8.1.3+8.1.3+main-8.1.x.c94d18ec starting: java version 1.8.0_392-internal by Oracle Corporation
[19:19:24] [main/INFO]: Added Lets Encrypt root certificates as additional trust
[19:19:24] [main/INFO]: SpongePowered MIXIN Subsystem Version=0.8.4 Source=file:/storage/emulated/0/Android/data/net.kdt.pojavlaunch/files/.minecraft/libraries/org/spongepowered/mixin/0.8.4/mixin-0.8.4.jar Service=ModLauncher Env=CLIENT
[19:19:29] [main/INFO]: Launching target 'fmlclient' with arguments [--version, 1.16.5, --gameDir, /storage/emulated/0/Android/data/net.kdt.pojavlaunch/files/.minecraft, --assetsDir, /storage/emulated/0/Android/data/net.kdt.pojavlaunch/files/.minecraft/assets, --uuid, 00000000000000000000000000000000, --username, MonkiDKosta, --assetIndex, 1.16, --accessToken, ❄❄❄❄❄❄❄❄, --userType, mojang, --versionType, release]
[19:20:05] [main/INFO]: Environment: authHost='https://authserver.mojang.com', accountsHost='https://api.mojang.com', sessionHost='https://sessionserver.mojang.com', servicesHost='https://api.minecraftservices.com', name='PROD'
[19:20:07] [main/INFO]: Setting user: MonkiDKosta
Registered forkAndExec
[19:20:09] [main/INFO]: [org.lwjgl.system.Library:printError:555]: [LWJGL] Failed to load a library. Possible solutions:
	a) Add the directory that contains the shared library to -Djava.library.path or -Dorg.lwjgl.librarypath.
	b) Add the JAR that contains the shared library to the classpath.
[19:20:09] [main/INFO]: [org.lwjgl.system.Library:printError:557]: [LWJGL] Enable debug mode with -Dorg.lwjgl.util.Debug=true for better diagnost
