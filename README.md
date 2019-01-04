# freedom
- This repository should replace the sites folder of a drupal 8 site
- It will enable theme debugging for theme development
- This repo also includes files such as images to be used by the Saint theme

## Instructions
1. Navigate inside the web directory (docroot) of a drupalvm drupal 8 site
2. Backup the sites directory ``mv sites sites-old``
3. Remove the sites directory ``rm -fr sites``
4. Clone this repo to the docroot, or download it as a .zip file
5. Unzip.
6. Delete the .zip file.
7. Rename the 'freedom' directory to 'sites' ``mv freedom sites``

## Notes
This will create a base for developing the Saint theme

If you have uploaded any files/ folders already to your drupal 8 site they will be overwritten.

You can preserve those by backing up your files directory and copying into the new files directory


