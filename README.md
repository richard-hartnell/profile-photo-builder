# profile-photo-builder
an automatic festival profile photo builder.

## Directions
To just make it work, clone this project into a local folder; open with Photoshop and use File -> Export -> "Data Sets As Files..."

It should export three .PSD files, which can be exported as-is or tailored slightly and then exported (e.g. Bug).

## How it works
The very creatively-named "sheet1.csv" is referenced by Photoshop in a "Data Sets" property that corresponds its layer names to column names in a reference CSV. This is all set up and hidden in the back-end of template.psd.

## Future plans
The plan is for this program to be able to download all staff photos from a festival application, read in their stage name and title, and export a profile photo.
