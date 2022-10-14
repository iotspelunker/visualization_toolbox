# Visualization Toolbox
Visualization Toolbox is an add-on for Splunk Enterprise powered by the Apache ECharts library.



## Releases:
A tar file for installation on you instance can be found here:
* Github: https://github.com/hman-78/splunk-visualization-toolbox/releases
* Splunkbase: TBA
## Usage
To-Do


## Build app by yourself
* Clone repository
* run:
```
cd appserver/static/visualizations/hman

npm install

cp -a node_modules_patch/* node_modules/

npm run build

rm -rf node_modules
rm -rf node_modules_patch  
```
* Copy app folder to your Splunk instance
