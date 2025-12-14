## Add Android and sqlite 

```bash
cordova platform add android   
cordova plugin add cordova-sqlite-storage   
cordova plugin add cordova-plugin-media-capture
```

## Check Requirements

```bash
cordova requirements   
```

## EXPORT PATHS

```bash
export ANDROID_HOME=$HOME/Android/sdk   
export PATH=$PATH:/home/danielp/myapps/gradle-8.10/bin   
export PATH=${PATH}:$ANDROID_HOME/cmdline-tools/bin   
```


## BUILD

```bash
cordova build android
```

## Check Android Platfroms Installed

```bash
cd $ANDROID_HOME/platforms
ls
```

##  Android Install TOOLS & API 35

```bash
sdkmanager --sdk_root=$HOME/Android/sdk "platforms;android-35"   
sdkmanager --sdk_root=$HOME/Android/sdk "build-tools;35.0.0"
```

##  JAVA 17 SELECT AND EXPORT
```bash
sudo update-alternatives --config java
export JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
```

