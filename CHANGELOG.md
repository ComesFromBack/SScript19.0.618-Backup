# 19.0.618
- Added a new improved field system (Check [README.md](https://github.com/TahirKarabekiroglu/SuperlativeScript?tab=readme-ov-file))
- Fixed `as` in imports

# 18.6.618
- Removed 3LLua 
- Added presetter (CHECK README.md)
- Removed variable initialization order to fix a bug

# 17.2.618
- Fix compiling error

# 17.1.618
- Custom origins are no longer unique
- Added default funcs (Check `SScript.defaultFun`)

# 17.0.618
- 3LLua (Check [README.md](https://github.com/TahirKarabekiroglu/SuperlativeScript?tab=readme-ov-file#3LLua))

# 11.0.618
- Added Enum Abstract support (Check README.md)
- Completely reworked import system to be faster and more stable
- Completely reworked function arguments
- Added multiline error messages
- The classes of a script now gets destroyed when it gets destroyed
- Custom origins are now unique and cannot be used twice

# 10.1.618
- Fixed variable initialization order
- Fixed function arguments
- Moved `lastReportedCallTime` to call sugars, now accessible with `lastReportedTime`
- Fixed typos 

# 10.0.618
- Added class support
- Added string interpolation
- Added `public` as a shortcut to set global variables in scripts
- Removed StringTools support
- Reworked functions
- Reworked finals
- Reworked variable initialization
- Added better check to if, for and while expressions
- Reworked global variables
- Added `setAsFinal` option to `set`
- Removed useless checks