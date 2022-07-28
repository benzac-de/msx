# Media Station X - GitHub Pages Example
This project shows a way to host **Media Station X** JSON files via **GitHub Pages**.

For more information about the **Media Station X** project, please visit: https://msx.benzac.de/info/.

## Prepare Repository
* Create a repository named **msx** under your account (in this case: https://github.com/benzac-de/msx)
* Create a **start.json** file in this repository (for the data structure, please see: https://msx.benzac.de/wiki/index.php?title=Start_Object)
* Create a **menu.json** file in this repository (for the data structure, please see: https://msx.benzac.de/wiki/index.php?title=Menu_Root_Object)
* Setup **GitHub Pages** by following this guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
* Check if your JSON files are correctly hosted: 
  * https://{ACCOUNT}.github.io/msx/start.json (in this case: https://benzac-de.github.io/msx/start.json)
  * https://{ACCOUNT}.github.io/msx/menu.json (in this case: https://benzac-de.github.io/msx/menu.json)

## Setup Start Parameter
* Go to your corresponding application store (please see: https://msx.benzac.de/info/?tab=PlatformSupport)
* Install and launch the **Media Station X** application
* Navigate to **Settings** → **Start Parameter** → **Setup**
* Enter: **{ACCOUNT}.github.io** (in this case: **benzac-de.github.io**)
* Once you have completed the start parameter setup, your content is loaded every time you start the application.

## Direct Launch
* Use a standard web browser and open the following URL: 
  * https://msx.benzac.de?start=menu:https://{ACCOUNT}.github.io/path/to/menu (in this case: https://msx.benzac.de?start=menu:https://benzac-de.github.io/msx/menu.json)
