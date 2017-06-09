# FusePreferences
Fuse Preferences 
This is a simple module that you can use to read and write key/values and use them as substitution for SharedPreferences / NSDefaults in Fuse

## Initialization
Download the `Preferences.js` file and put in your project.
`var Preferences = require('/Logic/Preferences.js');`

## Usage

### Write
```
//Value can be any javascript variable, number,string, object
Preferences.write("key",value);
```

### Read
```
//second parameter, is the default return if key is missing. 
return Preferences.read("key_to_read",false);
```
