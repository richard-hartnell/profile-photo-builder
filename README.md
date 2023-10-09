# profile-photo-builder
an automatic festival profile photo builder.

## Directions
To just make it work, clone this project into a local folder; open with Photoshop and use File -> Export -> "Data Sets As Files..."

It should export three .PSD files, which can be exported to JPG/PNG/WEBP as-is or tailored slightly and then exported (e.g. Bug).

## How it works
The very creatively-named "sheet1.csv" is referenced by Photoshop in a "Data Sets" property that corresponds its layer names to column names in a reference CSV. This is all set up and hidden in the back-end of template.psd.

In the future, this will be populated with data from the back-end of a festival application form, which will also be scraped for all its file uploads so that this can all happen in one swell foop.

## Future plans
Just have to dovetail this with next year's festival apps and the [workshop-scheduler](https://github.com/richard-hartnell/workshop-scheduler) repo.
