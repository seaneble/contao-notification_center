Notification Center Changelog
===========================


Version 1.3.2 (2015-10-14)
--------------------------

### Fixed
- Dependencies could not be resolved due to missing \_autoload module (#82)
- Support getInstance method handling for sendNotificationMessage hook (#79)


Version 1.3.1 (2015-10-09)
--------------------------

### Improved
- No need to replace tokens again (#75)
- Allow simple token conditions in email fields

### Fixed
- Cronjob did not work when installed via composer (#77)


Version 1.3.0 (2015-09-03)
--------------------------

### New
- Added a sendNotificationMessage hook (#72)
- Allow recipient token to contain a list of recipients. (#75)

### Fixed
- Do not add a new line if file storage mode append but existing file was empty


Version 1.3.0-rc1 (2015-07-07)
------------------------------

### New
- The Notification Center now provides a queue gateway that buffers messages and sends them based on cron job settings (#63)
- The "store to file" gateway now supports appending to an already existing file (#65)
- InsertTags as well as Simple Tokens are now allowed in sender e-mail name and sender e-mail address fields as well (#40 and #58)
- Added support for file uploads in form generator fields that can now use the upload attachment token (#39)


Versions previous to 1.3.0-rc1
------------------------------

Changelog was not maintained in previous versions.
Try to use the git history for details.
