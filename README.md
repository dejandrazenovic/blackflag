# blackflag
An AppleScript-based Google Search automata for obfuscating your search profile (for MacOS).
## Concept
In a world where digital privacy is becoming scarce, more people are deciding to walk away from tech giants that harvest their data for marketing and potentially more nefarious purposes.

**blackflag** is an attempt to create a (vaguely human-like) program using AppleScript in order to feed Google your own "query list" of searches in order to manipulate your search interests and protect your future privacy.

Because this is an open source script, you may alter it to suit your needs and hopefully even contribute your improvements; 
*however you may not impersonate me and/or distribute this project yourself with malicious intent.*

## Instructions
**blackflag** is currently a simple AppleScript file, so it can be executed using AppleScript on MacOS.
1. Ensure that JS browser automation is enabled in Safari, located at `Develop > Allow JavaScript from Apple Events`. JavaScript automation is unfortunately not supported in Firefox and using Chrome is not reccommended due to it being borderline spyware.
2. Create a `txt` file with UTF-8 encoding containing the queries you want to use on separate lines. On launch, **blackflag** will ask how many entries (lines) are in your file. The more queries you think of, the more effective the script will be and the more frequently you can run it.

When you launch **blackflag**, you will be asked to choose your querylist, # of queries, and repetitions you want to run.

## TODO:
- Look into controlling the mouse to create mouse movements (Google tracks mouse movement). 
- Find a way to control the mouse to randomly click on links rather than using a JavaScript request.
- Implement the options of longer delays between each search to make it seem more organic.
