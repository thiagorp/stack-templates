# Stack Templates

Custom templates for [Stack] used by thoughtbot.

[Stack]: http://haskellstack.org

## api

Usage:

    stack new my-project https://raw.githubusercontent.com/thiagorp/stack-templates/master/api.hsfiles

Initializes a new Yesod web API with Persistent, Esqueleto, raw authentication and some utilities.

## Editing

Three scripts are included to make it easier to edit these templates:

* `bin/split`, which will split an hsfiles template into directories and files for easy editing
* `bin/join`, which will merge a directory back into hsfiles format
* `bin/verify`, which will attempt to build a project from the template using Stack

