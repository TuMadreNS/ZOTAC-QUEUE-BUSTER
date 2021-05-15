# ZOTAC-QUEUE-BUSTER
# https://discord.nerdspeak.net

Spawn multiple ZOTAC Queue browser sessions



All we are going to do with this script is spawn 20 Chrome browser profiles/session and open the Zotac queue hoping we get a low number on one of these. If someone wants to make a PR and do some fancy selenium checking for queue spots have at it.

This script assumes you have 64 bit Chrome installed.

THE ZOTAC QUEUE URL MIGHT CHANGE AT EACH DROP, IF THIS HAPPENS, OPEN zotacstore.com, pass the captcha, then find/replace the URL with the queue URL in the code. Since we are using the queue URL, you will not need to compete a captcha for each session (unless they change it).

Copy the code below and put it in an empty text file named tony.bat (the name isn't important, just needs to be a .bat file) and save it. Double click bat file to run. You can also open more or less than 20, just figured it's a good starting point. If your machine can handle it, just copy/paste additional lines but make sure you change the --profile-directory= number on your new lines.



```
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=1 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=2 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=3 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=4 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=5 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=6 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=7 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=8 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=9 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=10 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=11 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=12 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=13 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=14 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=15 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=16 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=17 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=18 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=19 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
"C:\Program Files\Google\Chrome\Application\chrome.exe" --args --profile-directory=20 "https://zotacstore.queue-it.net/?c=zotacstore&e=zotacprod2&t=https%3A%2F%2Fwww.zotacstore.com%2Fus%2Fgraphics-cards%2Fgeforce-rtx-30-series%3Flimit%3D36&cid=en-US"
```
