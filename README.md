# Phishing Net - A Phishing Kit Repository

Phishing Net is a repository that contains phishing kits found in the wild, usually from servers being used for active phishing campaigns. These files may or may not contain server/user specific settings or configs that you may or may not find useful in your investigations, but the main aim of the project is to make investigation of new phishing campaigns easier.

## Directory Structure

```
project
│   README.md
└───year
│   └───month
│       ├───siteurl (filename)
│       │   ├───filename.ext
│       │   └───sha256sum
│       ├───siteurl (filename)
│       │   ├───filename.ext
│       │   └───sha256sum
│      ***
└───year
    └───month
        ├───***
        │
       ***
```

## Disclaimer

This repository exists to make phishing analysis and investigation easier for people interested in such, and under no circumstance shall these files be used for running actual phishing campaigns.

At best these files are checked to include what they should considering the sources they were obtained from, so proceed with the expectation that each package contains something malicious that can and will be dangerous.

These files are provided WITHOUT ANY WARRANTY or implications for FITNESS FOR A PARTICULAR PURPOSE. You're on your own.
