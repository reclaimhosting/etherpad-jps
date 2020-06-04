# Etherpad for Reclaim Cloud
Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time.

## Deploy to Reclaim Cloud
[Click here to deploy to Reclaim Cloud](https://app.my.reclaim.cloud/?app=etherpad)

## Installation Instructions

You can find Etherpad by clicking Marketplace and then Applications to show all or searching by name.

![Screen Shot 2020-06-04 at 11.29.34 AM|530x103](https://community.reclaimhosting.com/uploads/default/original/2X/6/66fffe086313e6975f16e1afe89e18c34510c6c8.png) 

![Screen Shot 2020-06-04 at 11.22.52 AM|690x337](https://community.reclaimhosting.com/uploads/default/optimized/2X/8/8ed454ca757167bd7e7c3ae1d687210e0dc40ce4_2_1380x674.png) 

Installing is as easy as setting an environment name and region for the install. SSL will be provisioned automatically for the environment and your install will be up and running in just a few minutes.

![Screen Shot 2020-06-04 at 11.31.33 AM|690x404](https://community.reclaimhosting.com/uploads/default/original/2X/7/73d23264e3cb22fe67de7d06498c33f1a43ea67b.png) 

![Screen Shot 2020-06-04 at 11.23.25 AM|470x159](https://community.reclaimhosting.com/uploads/default/original/2X/e/e1fa3c638cf81e0d83b2d89ecc3b997c100138ca.png) 

![Screen Shot 2020-06-04 at 11.33.11 AM|468x261](https://community.reclaimhosting.com/uploads/default/original/2X/4/48f614876f4b8dcea4a61d89af8bdb555eb09c54.png) 

![Screen Shot 2020-06-04 at 11.37.51 AM|690x454](https://community.reclaimhosting.com/uploads/default/optimized/2X/3/3dfc8787b2ab0962345cb354c06de781eb1f2618_2_1380x908.jpeg) 

Our implementation of Etherpad uses Docker and you can customize your install in a few different ways. The primary way of adjusting settings is with the use of environment variables. Etherpad has these options documented at [https://github.com/ether/etherpad-lite/blob/develop/doc/docker.md](https://github.com/ether/etherpad-lite/blob/develop/doc/docker.md). To add variables to your container, after install you will click the gear icon and select **Variables** where you can add your own settings in key/value format.

![Screen Shot 2020-06-04 at 11.35.48 AM|690x71](https://community.reclaimhosting.com/uploads/default/original/2X/5/5c83a50a26a88f027ee4c0dfd4e13973df38f1ed.png) 

![Screen Shot 2020-06-04 at 11.56.13 AM|690x135](https://community.reclaimhosting.com/uploads/default/original/2X/e/eb6da32bfe50809404236dcdcf07c1f754cebd33.png) 

You can also edit the file at /opt/etherpad-lite/settings.json to manually update values (though we strongly recommend using environment variables as opposed to manual file editing).

![Screen Shot 2020-06-04 at 11.39.32 AM|659x135](https://community.reclaimhosting.com/uploads/default/original/2X/d/daf85a5ea65f4321e93f5c49477a135258903573.png) 

![Screen Shot 2020-06-04 at 11.53.35 AM|690x364](https://community.reclaimhosting.com/uploads/default/original/2X/e/ea3fba40c36550def6600c8cebae4e8679f8652e.png) 

![Screen Shot 2020-06-04 at 11.47.32 AM|690x473](https://community.reclaimhosting.com/uploads/default/original/2X/a/a2ac77fa4782c4522ea514303c6300f2981316b8.png) 

With any change to variables or directly to the settings.json file you will need to restart the server for those changes to take effect.

![Screen Shot 2020-06-04 at 11.37.30 AM|572x134](https://community.reclaimhosting.com/uploads/default/original/2X/6/6f90d6649b3978d0fc0dfd464a5264c37474d5f5.png) 

Etherpad also has an admin interface at /admin that you can access (make sure you set the ADMIN_PASSWORD variable) to manage the software including plugin installation.

![Screen Shot 2020-06-04 at 12.00.39 PM|690x414](https://community.reclaimhosting.com/uploads/default/optimized/2X/1/1911fb5df7f598171dd8f432922763fe3606619d_2_1380x828.png)
