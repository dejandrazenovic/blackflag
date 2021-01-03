# blackflag
An AppleScript-based Google Search automata for obfuscating your search profile (for MacOS).
## Concept
**blackflag** is an attempt to create a (vaguely human-like) program using AppleScript in order to feed Google your own "query list" of searches in order to manipulate your search interests and protect your future privacy after abandoning your account.
What **blackflag** *isnt* is a background/headless process nor a privacy tool for you to continue using Google. It is meant to run for a few minutes each day when you are away from the computer to slowly change your personal profile over the course of a few months.

Because this is an open source script, you may alter it to suit your needs and hopefully even contribute your improvements; 
*however you may not impersonate me and/or distribute this project yourself with malicious intent.*

## Instructions
**blackflag** is currently a simple AppleScript file, so it can be executed only using AppleScript on MacOS.

1. Ensure that JS browser automation is enabled in Safari, located at `Develop > Allow JavaScript from Apple Events`. JavaScript automation is unfortunately not supported in Firefox and using Chrome is not reccommended.
2. Create a `txt` file(s) with UTF-8 encoding containing the queries you want to use on separate lines. On launch, **blackflag** will ask how many entries (lines) are in your file. The more queries you think of, the more effective the script will be and the more frequently/longer you can run it. You want a narrow but diverse scope of interests, potentially different topics in different lists.
3. Open the file in AppleScript and click the `run` button. You may be asked to enable extra permissions for AppleScript in System Preferences.

When you launch **blackflag**, you will be asked to choose your desired querylist, # of queries in the list, and repetitions you want to run. I do not reccomend running more than a dozen queries at a time, as you will eventually be asked to submit captchas due to strange activity; without adding a long delay between each new search.

## TODO:
- Look into generating human-like mouse movement.
- Find a way to control the mouse to randomly click on links rather than using a JavaScript request.
- Implement the options for longer delays between each search to make it seem more organic and to prevent being flagged for suspicious activity.
