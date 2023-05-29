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

1. ☁ Clone this into your directory
```
    $ git clone https://github.com/designet-inc-oss/389-console.git
```
2. 🏗 Then run `./buildAndRun.sh` to build.
```
    $ cd 389-console/
    $ ./buildAndRun.sh
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

When utilizing the standard package of 389 Directory Server, there may be errors encountered during the following operations due to version discrepancies.
- Security settings in the Server tab
- Global policies in the Database tab

This 389ds-console has been verified to operate with version 2.4.1 of 389 Directory Server as of May 31, 2023. 
For 389 Directory Server version 2.4.1, please download it from the official website.
