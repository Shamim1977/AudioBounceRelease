<img src="assets/appicon.png" alt="AudioBounce" width="72">

## AudioBounce

<br>



### Dependencies - Windows

```
Sox: Download latest, extract and put in system environment variables:
https://sourceforge.net/projects/sox/files/sox/

espeak-ng: Download to install
https://github.com/Shamim1977/Binaries/releases/download/v1.0.0/espeak-ng.msi

ffmpeg & ffprobe: Download. Rename to ffmpeg and ffprobe respectively. Add the directory path to environment variables.
https://github.com/Shamim1977/Binaries/releases/download/v1.0.0/ffmpeg_win32.exe
https://github.com/Shamim1977/Binaries/releases/download/v1.0.0/ffprobe_win32.exe
```

### Dependencies - Linux

```
sudo update
sudo apt install sox libsox-fmt-mp3 espeak-ng portaudio19-dev

ffmpeg & ffprobe: Download to install
https://github.com/Shamim1977/Binaries/releases/download/v1.0.0/ffmpeg_linux
https://github.com/Shamim1977/Binaries/releases/download/v1.0.0/ffprobe_linux


sudo mv /download/path/to/ffmpeg_linux /usr/local/bin/ffmpeg
sudo mv /download/path/to/ffprobe_linux /usr/local/bin/ffprobe
sudo chmod +x /usr/local/bin/ffmpeg
sudo chmod +x /usr/local/bin/ffprobe
```

### Dependencies - MacOS

```
brew install sox espeak-ng portaudio

ffmpeg & ffprobe: Download to install
https://github.com/Shamim1977/Binaries/releases/download/v1.0.0/ffmpeg_darwin
https://github.com/Shamim1977/Binaries/releases/download/v1.0.0/ffprobe_darwin
On macOS 10.15 (Catalina) the binaries have to be removed from quarantine:

sudo mv /download/path/to/ffmpeg_darwin /usr/local/bin/ffmpeg
sudo mv /download/path/to/ffprobe_darwin /usr/local/bin/ffprobe
sudo chmod +x /usr/local/bin/ffmpeg
sudo chmod +x /usr/local/bin/ffprobe

export PATH="/usr/local/bin:$PATH"

xattr -dr com.apple.quarantine /usr/local/bin/ffmpeg
xattr -dr com.apple.quarantine /usr/local/bin/ffprobe
```


### Download to Install AudioBounce

```
Windows:
https://github.com/Shamim1977/AudioBounceRelease/releases/download/v1.0.0/AudioBounce.1.0.0.msi

Linux:
https://github.com/Shamim1977/AudioBounceRelease/releases/download/v1.0.0/audiobounce_1.0.0_amd64.deb

MacOS:
https://github.com/Shamim1977/AudioBounceRelease/releases/download/v1.0.0/AudioBounce-1.0.0.dmg

```



### Install - Windows

```
Use Installer Interface
```

### Install - MacOS

```
Use Installer Inteface
```


### Install - Ubuntu

```
sudo dpkg -i AudioBounce_1.0.0_amd64.deb
```

### Uninstall - Windows

```
Run appwiz.cpl
Select
Uninstall
```

### Uninstall - MacOS

```
Go to Applications
Drag AudioBounce and drop on Trash
```

### Uninstall - Ubuntu

```
sudo apt remove AudioBounce
```




<br>
<br>


### Owner

<strong>Nnaemeka Ngwu</strong>

<preciousngwu2@gmail.com>

<br>
<br>

### Developer

<strong>Shamim Hossain</strong>

<sparrowmtm@gmail.com>

<https://mrittica.com>

<https://www.upwork.com/freelancers/~019f659b0849b9115b>