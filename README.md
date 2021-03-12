# Build a Basic Website with VS Code

- VS Code IDE - https://code.visualstudio.com/
- Browser - Chrome https://www.google.com/chrome/

Part 1
- Create a folder (directory)
- create an HTML file: index.html 
- populate file with HTML code
- open the index.html file with a browser

Part 2
- Style that HTML document CSS - cascading style sheets

Part 3
- Load up Javascript - alert('hello world')



# Deploying to Cloud Run!

- Setup GCP with google account
- connecting a billing account to it
- build a docker file based on https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)
- opened cloud run from GCP console https://console.cloud.google.com/run/
- created new service, name it
	- selected region (central)
	- configure step: selected continue deploy for source repo
	- click setup with cloud build
	- authed github from the link
	- click manage connect repos (lets you select where to give permission)
	- select repo on github
	- selected build type Docker File
	- Allow all traffic
	- Allow unauthenticated traffix
- Built out docker file and pushed (https://github.com/planethacktv/basic-website)
- Updated docker file to reference the env.port
- tested splitting
- distribute the live url
- pipe a domain to it