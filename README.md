## Getting Started with the MFE-POC

Each folder is a separate create-react-app micro frontend project.

**Useful commands

Install all packages - this will run post install to add the webpack config lines from the patch script
# `npm install`

This command is used to patch the webpack config if you made an update to ../node_modules/react-scripts/webpack.config file -- only run this if you have made a new update to webpack config
# `npm run custom-package-config`

Run the project
# `npm run start`


**Note that you will need the station api running to view data on the charger management page, you will need to run the station api project on port 3006
