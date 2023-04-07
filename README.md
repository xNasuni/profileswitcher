# ProfileSwitcher

<img src="/assets/splash.png" width="200px"/>

**ProfileSwitcher** is a utility for the browser **Opera GX** that allows you to change between the profiles you want links to automatically open, as in when you click on a link, it opens Opera GX as the profile you choose.

> This utilizes the registry in order to change the registry key responsible for opening Opera GX and simple file reading to create a list and obtain the data of your current profiles.

>
# Download
> **[`Latest Version` `f69a0aea7229c3c541f0502c19941c76b3481fcee36fc39ef68ca577be21118c`](https://github.com/xNasuni/ProfileSwitcher/releases/tag/1.0.0)**

## Extra Information

> **ProfileSwitcher** only changes a single registry key and reads your Opera GX profile data thats neccessary to make this program work.
> The registry key and the directories it reads is mentioned below.
> ```
> Files    %LocalAppData%\Programs\Opera GX
> Files    %AppData%\Opera Software\Opera GX Stable
> Files    %AppData%\Opera Software\Opera GX Stable\_side_profiles
> Registry HKEY_CURRENT_USER\Software\Classes\Opera GXStable\shell\open\command
> ```
