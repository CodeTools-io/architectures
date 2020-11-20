# Overview

The bookmark service is responsible for storing information or references to information.
In addition to storing the information, it should be capable of easily finding and displaying the information
that has been previously stored. When trying to find this information, a user may not remember the exact name
of the information, it may just be a keyword, a general website name, or part of a path.

## Schema

### Bookmark Fields

- **title** : short name associated with a reference that is meant for personal recollection and identification
- **path** : combination of the url path and the url query string of a reference
- **description** : detailed information for describing a reference
- **source** : identity of the external source that is being referenced
- **topics** : way to organize and associate references non-hierarchically
- **notes** : personal commentaries about a reference

### Topic Fields

- **name**: short name or category of a group of bookmarks
- **description**: detailed information for describing the topic
- **bookmarks**: bookmarks that are associated with this topic
