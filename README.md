# 389-console
DesigNET has performed multilingualization and Japanese localization for the 389DirectoryServer plugin in Cockpit.


## Setup Installation

### Prerequisites

- cockpit
- 389 Directory Server
- git
- make
- nodejs

### Installation

1. ☁ Clone this into your `/opt` directory
```
    # cd /opt
    # git https://github.com/designet-inc-oss/389-console/389-console.git
```
2. 🏗 Then run `./buildAndRun.sh` to build.
```
    # cd 389-console/
    # ./buildAndRun.sh
    :
    Building and watching ...
    webpack compiled successfully
    (Ctrl + c)
```
 3. ✅ Place the dist directory in the cockpit directory.
```   
    # cp -rp dist /usr/share/cockpit/389-console
```

4. 🎉 The Directory Server menu will be added in Japanese to the 389 cockpit!

## Attention
