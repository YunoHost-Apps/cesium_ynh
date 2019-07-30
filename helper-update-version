#!/bin/bash
# Retrieve sources, get sha256sum, parse package version and update these strings in manifest, README and /conf/app.src
 
URL=$(curl -s https://api.github.com/repos/duniter/cesium/releases/latest | grep "browser_" | grep "web" | head -1 | cut -d\" -f4)
wget -nc --quiet $URL -P ./tmp
CHECKSUM=$(sha256sum ./tmp/cesium-*-web.zip | head -c 64)
sed -i "s/SOURCE_SUM=.*/SOURCE_SUM=${CHECKSUM}/" ./conf/app.src
sed -i "s#SOURCE_URL=.*#SOURCE_URL=$URL#" ./conf/app.src

VERSION=$(echo $URL | sed "s#https://github.com/duniter/cesium/releases/download/\(.*\)/cesium.*#\1#")
sed -i "s#\*\*Shipped version:\*\*.*#\*\*Shipped version:\*\* ${VERSION}#" ./README.md
sed -i "s#    \"version\": \".*#    \"version\": \"${VERSION}\~ynh1\",#" ./manifest.json

rm -f -R ./tmp

git commit README.md manifest.json conf/app.src -m "$VERSION"
