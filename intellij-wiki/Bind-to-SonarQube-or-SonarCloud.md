# Overview
You can connect SonarLint to SonarQube >= 7.9 or SonarCloud to aim at having consistent issues reported on both sides.

Features when using Connected Mode:
* use the same quality profile (same rules activation, parameters, severity, ...)
* reuse some settings defined on the server (rule exclusions, analyzer parameters, ...)
* automatically suppress issues that are marked as _Won’t Fix_ or _False Positive_ on the server
* review a Security Hotspot by clicking on the 'Open in IDE' button on SonarQube
* display taint vulnerabilities that have been found on the server (there is currently no local detection of those advanced issues)
* use the same analyzers as the server, assuming they are supported in SonarLint (exception for C# and C/C++ analyzers where SonarLint keep using its embedded version)

Note: Connected Mode does not push issues to the server. Rather, its purpose is to configure the IDE so that it uses the same settings as the server.

# Configure a connection

MOVED TO: WORKINGIN-A-TEAM > CONNECTED-MODE > INTELLIJ (TAB)

# Configure project binding

MOVED TO: WORKINGIN-A-TEAM > CONNECTED-MODE > INTELLIJ (TAB)

# Connect to HTTPS server

NOT MOVED 

# Troubleshooting

## I use Connected Mode but I observe different analysis results between SonarQube/SonarCloud and SonarLint

MOVED TO: WORKINGIN-A-TEAM > CONNECTED-MODE > INTELLIJ (TAB) > TROUBLESHOOTING CONNECTED MODE (HEADER)

## Proxy issues

NOT MOVED 