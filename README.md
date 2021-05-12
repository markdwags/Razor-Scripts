# Razor Script Repository

![Razor Logo](https://imgur.com/jTtHLVF.png)

This repository contains scripts designed for the [Razor Community Edition](http://www.razorce.com/) and works in conjunction with the [main project](https://github.com/markdwags/Razor).

For more information about Razor's scripting abilities, review the [Razor Scripting Guide](http://www.razorce.com/guide/).

## Contributing

To contribute to this repository:

* Fork this repository and clone it locally
* Ensure your script(s) have the proper header.
* Place your script(s) in the 'Scripts' directory using the directory structure that describes the category of your script, such as 'Skills\Provocation'
* Commit your code to your local repository and create a pull request

If your pull request is accepted, after a short automated process, it will automatically appear in Razor's repository browser.

Before you contribute a script, please try to follow these guidelines:

* Scripts should be submitted with proper indentation. This makes the overall script much easier to read.
* Use [comments](http://www.razorce.com/guide/comments/) where it makes sense.
  * Remember not everyone who is going to use your script has a full understanding of what is happening. Some comments that explain what is going on at certain points of the script are very beneficial in teaching others.
* Please review other scripts in the same category as one you're submitting.
  * This repository is looking for **quality** over **quantity**. We don't need 7 scripts that do the same thing. Instead of submitting a new one, can the existing script be improved instead?
* If your script is shard specific, be sure to use the same naming scheme for that shard as you see in other scripts.
  * This makes searching and filtering for different scripts easier in Razor's repository browser

### Script Header

For the script to properly display in Razor's repository browser, it must include the following information at the start of your script so the proper metadata can be generated.

The following fields are required:

* `Name`
  * The general name of the script, try to keep it short when possible.
* `Description`
  * Give a general overview of what the script does. It doesn't need to be a novel.
* `Author`
  * This could be as simple as a single name you go buy or if you'd like to include additional info like your Discord username. Keep it consistent though whatever you decide to use.

And must include one of the following:

* `Shard`
  * If your script only works on a specific shard, define it here.
* `Era`
  * If your script only works in a specific era, define it here.

Era may be one of the following:

* `T2A`
* `UOR`
* `AOS`
* `SA`
* `HS`
* `TOL`
* `Any`

You may include any optional information in the header such as but not limited to:

* `Instructions`  
* `Notes`

For example, if you script is shard specific:

```csharp
# Name: Provo Training
# Description: Uses a drum, targets a mob, waits, targets another
# Author: Quick
# Shard: SomeShard
```

Or if it will work on any shard:

```csharp
# Name: Provo Training
# Description: Uses a drum, targets a mob, waits, targets another
# Author: Quick
# Shard: Any
```

Or if it era specific:

```csharp
# Name: Provo Training
# Description: Uses a drum, targets a mob, waits, targets another
# Author: Quick
# Era: UOR
```
