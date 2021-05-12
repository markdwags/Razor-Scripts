# Razor Script Repository

This repository contains scripts for the [Razor Community Edition](http://www.razorce.com/).  For more information about, review the [Razor Scripting Guide](http://www.razorce.com/guide/).

## Contributing

To contribute to this repository, send a pull request with your script placed in the 'Scripts' directory with a directory structure that describes the category of your script, such as 'Skills\Animal Taming'

### File Header

For the script to properly display in Razor's repository browser, it must include the following information at the start of your script so the proper metadata can be generated. For example:

If you script is shard specific:

```
# Name: Provo Training
# Description: Uses a drum, targets a mob, waits, targets another
# Author: Quick
# Shard: Any
```

Or if it era specific:

```
# Name: Provo Training
# Description: Uses a drum, targets a mob, waits, targets another
# Author: Quick
# Era: UOR
```

The following fields are required:

* Name
* Description
* Author

And must include one of the following:

* Shard
* Era

Era may be one of the following:

* T2A
* UOR
* AOS
* SA
* HS
* TOL
* Any
