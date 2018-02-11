# Linux

Install Android Studio
hello:Installing Java

sudo add-apt-repository ppa:webupd8team/java

sudo apt-get update

sudo apt-get install oracle-java8-installer

After that

sudo apt-get install oracle-java8-set-default

Download Android Studio from site

sudo unzip android-studio-ide-141.2178183-linux.zip -d /opt

Create a desktop file

Create a new file androidstudio.desktop by running the command:

nano ~/.local/share/applications/androidstudio.desktop

and add the lines below

[Desktop Entry]

Version=1.0

Type=Application

Name=Android Studio

Exec="/opt/android-studio/bin/studio.sh" %f

Icon=/opt/android-studio/bin/studio.png

Categories=Development;IDE;

Terminal=false

StartupNotify=true

StartupWMClass=android-studio
