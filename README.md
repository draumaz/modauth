# modauth

## usage
- create a service.sh file with the script you want to run
```
cat > service.sh << EOF
/system/bin/sh echo "Hello, world!"
EOF
```
- either supply variables or go through the prompts
```
name="package-name" \
version="1" \
versionCode="1" \
author="author-name" \
description="A short description of your package!" \
  sh modauth.sh
``` 
