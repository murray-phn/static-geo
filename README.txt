Use geojsplit module to split up JSON files into separate files.

You may need to edit the geojsplit bin file to change the way it names files.
Also, replace require('fs') with require('graceful-fs') to get around the file count limit.

npm install --save graceful-fs



Github URL: SamWhillance/geojsplit

EXAMPLE USE

geojsplit -k SSC_CODE16 SSC_2016_AUST_1PC.json