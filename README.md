Fixed a couple install problems of psemu's original, nothing special https://github.com/psemu/forgelight-chunk

soe-chunk
============

SOE Terrain Chunk Extracter

Installing
============

`npm install`

Usage
============

`node cnktool.js <mode> <inPath> [<outPath>]`

| Mode              | Description
|-------------------|-------------------
|`info`             | Display basic info about the chunk 
|`json`             | Dump the chunk data to a readable .json format
|`textures`         | Extract the embedded color_nx .dds textures from the chunk
|`normalmaps`       | Extract the embedded spec_ny .dds textures from the chunk
|`geometry`         | Save the terrain geometry in .obj format

