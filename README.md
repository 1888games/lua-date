#LuaDate v2.1

Lua Date and Time module for Lua 5.x.

##Features:

* Date and Time string parsing.
* Time addition and subtraction.
* Time span calculation.
* Support ISO 8601 Dates.
* Local time support.
* Lua module (not binary).
* Formats Date and Time like strftime.
  
##Changes:

- v2.1 NPM support
- v2.1 Lua 5.2 support. Global 'date' will no longer be set.
- v2.0 original by Jas Latrix

## Usage

### 1. Install

Use either [LuaRocks](http://www.luarocks.org/) or [NPM](http://npmjs.org) to install

#### LuaRocks

Setup [LuaRocks](http://www.luarocks.org/en/Download) and then just `luarocks install date`

#### NPM

Setup [lua-loader](https://github.com/wscherphof/lua-loader) and then just `npm install lua-date`

### 2. Require

```lua
local date = require("lua-date")
```

### 3. Have fun

```lua
print(date("2013-06-20T10:32:00+02:00"))
```
See [API doc](http://tieske.github.io/date/) (which is a browseable version of [doc/index.html](doc/index.html))
