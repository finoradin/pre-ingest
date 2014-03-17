MoMA bagger
====================

A utility for copying bagging files and enforcing the DRMC naming convention via the TMS API. Requires the bagit python module.

[bagit-python]: https://github.com/edsu/bagit

Command Line Usage
------------------

    python bagger.py -i /Volumes/source-drive/source-directory -id 152406

With access to the MoMA TMS API, this would result in the transfer of the files, and a bag named "Will_Wright---SimCity_2000---930.2012---152406"
  
Arguments
------------------
  - `-id, --accessionid` (required) object/acession number of the artwork.
  - `-i, --input` (required) Full path of the source directory or file
  - `-t, --title` (optional) Title of the transfer.
  - `-n, --name` (optional) Name of the person operating the script. This winds up in the Bag's metadata
