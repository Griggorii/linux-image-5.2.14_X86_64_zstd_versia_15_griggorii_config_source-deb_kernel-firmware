# linux-image-5.2.14_X86_64_zstd_versia_15_griggorii_config_source-deb_kernel
linux-image-5.2.14_X86_64_zstd_versia_15_griggorii_config_source+deb_kernel

Download deb https://drive.google.com/open?id=1MfDTG0Y68CZ67Wp8sbNM32qZ0XBTgNx5 для тех кому не нужен лишний вес 40Mb 

Download sorurce linux-kernel + deb easy inpack https://drive.google.com/open?id=1-qokxif7VRcS8SUE7qsB3mrFW9U24x-F

$ sudo apt update && apt install -y libelf-dev flex bison build-essential libc-dev libc6-dev gcc g++ dpkg-dev bc fakeroot libncurses5-dev libssl-dev git make

$ make -j16 bindeb-pkg

В будущем планируется встроить андроид в убунту и пользовать apk как приложения сам андроид и пути к binder,hwbinder,vndbinder находятся в system/lib


CONFIG_ANDROID_BINDER_DEVICES="binder,hwbinder,vndbinder"
