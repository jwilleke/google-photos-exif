# Readme

## Do you lose Metadata exporting in Takeout?

There are a lot of complaints about this.

Some metadata may be removed from files when uploading not at "Original Quality"; but you find the most-important metadata in the JSON sidecar.

If Google Photos edits or infers the GPS or Date, that information isn't overwritten in the EXIF, but it is in the JSON sidecar.

All the data I see in the Google Photos UI is in Takeout.

## 

yarn



yarn start --inputDir ~/takeout --outputDir ~/output --errorDir ~/error


## this seems to work

[Run from](/Volumes/ESSD1/git-temp/google-photos-exif)

No blanks in lines seem to work. Blanks cause issues

yarn start --inputDir /Volumes/docs/jim/data/Takeout/gphotos/Takeout/Google-Photos/1905 --outputDir /Volumes/hd3/photo-temp --errorDir /Volumes/ESSD1/git-temp/google-photos-exif/error

## What's missing

Appears ot only copy creation date to EXIF.

## <https://github.com/pwatk/google-photos-takeout>

Looks better.

## <https://www.markhansen.co.nz/google-photos-backup/>

Discusses the issues.

## <https://github.com/TheLastGimbus/GooglePhotosTakeoutHelper?tab=readme-ov-file>

This one is well reccomended.

This script it organizes and cleans up your Takeout for you. 
It will take all of those folders, find all photos in them, set their and file last modified correctly, and put it in one big folder (or folders divided by a month)


## A how To Backing up Google Photos

<https://www.markhansen.co.nz/google-photos-backup/>

## Google Keep Converter

Convert your Google Keep notes into a standard markdown + YAML header format.

## google-photos-takeout

<https://github.com/pwatk/google-photos-takeout/blob/main/README.md>

Script Uses exiftool and is editiable to make changes.
A script that uses exiftool to sort and organise photos and videos exported from Google Photos using Google Takeout.

