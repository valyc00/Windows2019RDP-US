# Windows2019RDP-US
Windows Server 2019 Github with RDP Access (ngrok US) 

Repo link: https://github.com/ThuongHai/Windows2019RDP-US

YouTube Video: https://youtu.be/mpdviKL3j40

Create a free VPS with 2cpu-7gb Ram FREE with Github:8

*For Asia go to https://github.com/ThuongHai/Windows2019RDP-AP*

+ Click Fork in the right corner of the screen to save it to your Github.
+ Visit https://dashboard.ngrok.com to get NGROK_AUTH_TOKEN
+ In Github go to Settings> Secrets> New repository secret
+ In Name: enter NGROK_AUTH_TOKEN
+ In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into
+ Press Add secret
+ Go to Action> CI> Run workflow
+ Reload the page and press CI> build
+ Press the down arrow on Connect To Your RPD to get IP, User, Password.
