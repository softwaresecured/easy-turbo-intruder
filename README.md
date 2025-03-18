# easy-turbo-intruder

## Pre-requisites
- Java set up with version 21 (other versions may work, but are untested)
- A python script provided by SoftwareSecured
- One or more text files containing HTTP requests, provided by SoftwareSecured

## How to run the test
1. Go to the latest release on this repo and download `turbo-intruder.jar`
2. Ensure the provided files are in the same directory as `turbo-intruder.jar`
3. Run the command provided by SoftwareSecured, it will be in the following format:

`java -jar turbo-intruder.jar <scriptFile> <baseRequestFile> <endpoint> <baseInput>`

e.g. `java -jar turbo-intruder.jar attack.py request.txt https://example.com ''`
