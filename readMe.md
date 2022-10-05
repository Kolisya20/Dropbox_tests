# Dropbox project

## Automation tests using Postman

This repository was created for functional test automation of Dropbox project.

Technologies used:
- [Postman](https://www.postman.com/)
- [Newnam](https://www.npmjs.com/package/newman)
- [Newman reporter htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)

## Setup

1. Clone this repository
2. Install newman with npm install -g newman
3. Install reporter with npm install -g newman-reporter-htmlextra

## Running test suite
1. Open terminal
2. Navigate to the path of the project that was cloned in
3. Run newman run Collection.json -e Environment.json -r htmlextra --reporter-htmlextra-title "Automated test reporting - Postman echo"

## Open report
After test completed check creared report in /newman