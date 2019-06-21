# Utilities for research

I'll be uploading utilities I use for my research here. Please feel free to use them as you see fit.

## reigns.json
This json file contains reign information for of the emperors from Imperial China, derived from this Wikipedia list:
https://en.wikipedia.org/wiki/List_of_Chinese_monarchs
It is not complete and all the cavaets that apply to any information from Wikipedia apply here!

This json object contains two sub-objects, a "reigns" object that contains an object with the following structure:
Dynasty
  Personal Name
    Reign Dates
    Era Names
    Posthumous Names
    Temple Names
    
The second sub-object is a lookup table that will return the Dynasty and Personal name of your person of interest (so you can easily look up them in the reigns object).
You can look up by personal name, era name, postumous name, and temple name. You can also specify the dynasty by adding that.
For example， 崇禎 and 明崇禎 will both bring up [['明', '朱由檢']]. If multiple people share the lookup, you will see all of them.
