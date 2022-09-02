# Media Station X - GitHub Pages Example
This project shows a way to host **Media Station X** JSON files via **GitHub Pages**.

For more information about the **Media Station X** project, please visit: https://msx.benzac.de/info/.

## Create Repository (From Scratch)
* Create a repository named **msx** under your account (in this case: https://github.com/benzac-de/msx)
* Create a **start.json** file in this repository (for the data structure, please see: https://msx.benzac.de/wiki/index.php?title=Start_Object)
* Create a **data** folder (or choose another name) in this repository
* Create a **menu.json** file (or choose another name) in the **data** folder (for the data structure, please see: https://msx.benzac.de/wiki/index.php?title=Menu_Root_Object)
* Create additional content files in the **data** folder (for the data structure, please see: https://msx.benzac.de/wiki/index.php?title=Content_Root_Object)
* Reference the **menu.json** in the **start.json** file (in this case: `menu:https://benzac-de.github.io/msx/data/menu.json`)
* Reference the additional content files in the **menu.json** file
* Setup **GitHub Pages** by following this guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
* Check if the **start.json** file is correctly hosted: 
  * <span>https:</span>//{ACCOUNT}.github.io/msx/start.json (in this case: https://benzac-de.github.io/msx/start.json)

## Setup Start Parameter
* Go to your corresponding application store (please see: https://msx.benzac.de/info/?tab=PlatformSupport)
* Install and launch the **Media Station X** application
* Navigate to **Settings** → **Start Parameter** → **Setup**
* Set the security lock (for HTTPS mode) and enter: `{ACCOUNT}.github.io` (in this case: `benzac-de.github.io`)
* Once you have completed the start parameter setup, your content is loaded every time you start the application

## Test In Browser
* Use a standard web browser and open the following URL: 
  * <span>https:</span>//msx.benzac.de?start=menu:<span>https:</span>//{ACCOUNT}.github.io/path/to/menu (in this case: https://msx.benzac.de?start=menu:https://benzac-de.github.io/msx/data/menu.json)

## Example Screenshots
![GitHub Pages Example](https://msx.benzac.de/info/img/github2.png)

## Example Video
[![GitHub Pages Example](https://img.youtube.com/vi/d9gff20WY4M/maxresdefault.jpg)](https://www.youtube.com/watch?v=d9gff20WY4M)
