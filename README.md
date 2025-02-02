# Senka's RetroArch Setup
My collection of dynamic wallpapers for the RetroArch XMB menu option and icons.

> [!NOTE]
> All titles, characters, and logos belong to their respective owners. I strive to provide proper [credit](#-Credit) in the [section below](#-Credit). If you would like something removed, please open an issue.

![---](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/line.png?raw=true)

## 📥 Installation

### Wallpapers
All wallpapers are designed to work with the XMB menu option only!

- [Download](https://github.com/SenkaWolf/Senkas-Retroarch-Setup/archive/refs/heads/main.zip) this repo.
- Navigate into your root directory of your RetroArch install location and go to 📂 `[RetroArch Root]/assets/wallpapers/`.
- In another window open the downloaded repo and go to 📂 `RetroArch/wallpapers/` then select which dynamic wallpaper pack you wish to use.
  - shakabello Preview [^shakabello]
- Copy the pack folder you selected into 📂 `[RetroArch Root]/assets/wallpapers/` folder.
- Launch RetroArch go to `Settings > User Interface > Appearance`.
- Scroll down and make sure the setting `Dynamic Wallpaper` setting is enabled.
- Then go back to `Settings > Directory > Dynamic Backgrounds`.
- Change the directory to 📂 `/assets/wallpapers/pack-name`.

> [!WARNING]
> The image names must match the playlist names. To verify this in RetroArch, navigate to `Main Menu > Show Desktop Menu` to view the playlist names. By default, they will match if you scanned your ROMs, unless you have manually created or renamed a playlist.

[^shakabello]: shakabello Preview ![shakabello image](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/screenshots/shakabello.jpg?raw=true) ![shakabello image 2](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/screenshots/shakabello2.jpg?raw=true) ![shakabello image 3](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/screenshots/shakabello3.jpg?raw=true) ![shakabello image 4](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/screenshots/shakabello4.jpg?raw=true)

### Icon Themes
- [Download](https://github.com/SenkaWolf/Senkas-Retroarch-Setup/archive/refs/heads/main.zip) this repo.
- Navigate into your root directory of your RetroArch install location and check 📂 `[RetroArch Root]/assets/xmb/custom` if the custom folder already has images within it please backup this folder else where then delete the contents. If the folder is empty then skip this step.
- In another window open the downloaded repo and go to 📂 `RetroArch/icon themes/` then select which icon pack you wish to use.
  - sysdaite Preview [^sysdaite]
- Copy the images from the icon theme you selected into 📂 `[RetroArch Root]/assets/xmb/custom` folder.
- Launch RetroArch go to `Settings > User Interface > Appearance`.
- Scroll down further to `Icon Theme` and select the `custom` option.

[^sysdaite]: sysdaite Preview ![sysdaite image](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/screenshots/sysdaite.png?raw=true)

![---](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/line.png?raw=true)

## ⚙️ Configuration

Change the following settings to get the cleanest look to suit the icon and wallpaper packs.

**Key: ${\color{lightgreen}On/Change}$ / ${\color{yellow}Optional}$ / ${\color{red}Off}$**

1. `Settings > User Interface > Appearance > Show Scale Factor` ${\color{lightgreen}1.00x}$
1. `Settings > User Interface > Appearance > Background Apacity` ${\color{lightgreen}1.000}$
1. `Settings > User Interface > Appearance > Dynamic Background` ${\color{lightgreen}On}$
1. `Settings > User Interface > Appearance > Icon Theme` ${\color{lightgreen}custom}$
1. `Settings > User Interface > Appearance > Primary Thumbnail` ${\color{red}Off}$
1. `Settings > User Interface > Appearance > Secondary Thumbnail` ${\color{lightgreen}Boxart}$
1. `Settings > User Interface > Appearance > Show Title Header` ${\color{red}Off}$
1. `Settings > User Interface > Appearance > Title Margin` ${\color{lightgreen}0}$
1. `Settings > User Interface > Menu Item Visibility > Show History` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Show Images` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Show Music` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Show Videos` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Show Netplay` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Show Contentless Cores` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Show Explore` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Style of Date and Time` ${\color{yellow}DD/MM/YYYY HH:MM}$
1. `Settings > User Interface > Menu Item Visibility > Date Separator` ${\color{lightgreen}/}$
1. `Settings > User Interface > Menu Item Visibility > Show Core Name` ${\color{red}Off}$
1. `Settings > User Interface > Menu Item Visibility > Show Menu Sub-labels` ${\color{red}Off}$
1. `Settings > User Interface > Show Advanced Settings` ${\color{lightgreen}On}$
1. `Settings > User Interface > Menu` ${\color{lightgreen}XMB}$
1. `Settings > Playlists > Manage Playlists`
   - Go through every playlist and change `Label Display Mode` to ${\color{lightgreen}Remove\space ()\space and\space [] }$

![---](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/line.png?raw=true)

## 📋 Playlist Organisation
RetroArch playlists are ordered alphanumerically by default. To change them you just need to rename the playlists found in 📂 `[RetroArch Root]/playlists/`. Below are some examples of how you could organise your playlists.

> [!WARNING]
> If you rename playlists and use dynamic wallpapers, you need to update the image names to match the new playlist names.

#### Year of Release Method
Renaming your playlist to have the year of release at the begining will organise it by the date.

> [!NOTE]
> Japan, North America, Europe and Australasia have some variation for when a device was released. My release years are based on Europe.

E.g.
- `1990 - Nintendo - Game Boy.lpl`
- `1995 - Sony - PlayStation.lpl`
- `1998 - Nintendo - Game Boy Color.lpl`
- `2001 - Nintendo - Game Boy Advance.lpl`
- `2002 - Nintendo - GameCube.lpl`
- `2005 - Sony - PlayStation Portable.lpl`

#### Type (Console/Handheld) - Manufacturer - Release Year Method
You could go a step further and organise by the type of device followed by the manufacturer and year. Using the table below to abbreviate you can end up with some of the examples.

|         Abbreviation       |                         Description                         |
|:--------------------------:|:-----------------------------------------------------------:|
| H                          | Handheld                                                    |
| C                          | Console                                                     |
| SEG                        | Sega                                                        |
| NIN                        | Nintendo                                                    |
| SON                        | Sony                                                        |
| MIC                        | Microsoft                                                        |

E.g.
- `CNIN2002 - Nintendo - GameCube.lpl`
- `CSON1995 - Sony - PlayStation.lpl`
- `HNIN1990 - Nintendo - Game Boy.lpl`
- `HNIN1998 - Nintendo - Game Boy Color.lpl`
- `HNIN2001 - Nintendo - Game Boy Advance.lpl`
- `HSON2005 - Sony - PlayStation Portable.lpl`

![---](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/line.png?raw=true)

## 💜 Credit
- sysdaite icon pack - This is a combination of the default systematic and daite icons packs.
- shakabello wallpaper pack - A combincation of [lipebello](https://github.com/lipebello/Retroarch-XMB-Retrorama-Theme) and [Shakalakka's](https://archive.org/details/shakalakka-dynamic-wallpapers) wallpaper packs.

![---](https://github.com/senkawolf/Senkas-Retroarch-Setup/blob/main/media/line.png?raw=true)