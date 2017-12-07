# Name

lua-resty-objectid - lua mongodb objectid implement for the ngx_lua, see:[https://docs.mongodb.com/manual/reference/method/ObjectId/](https://docs.mongodb.com/manual/reference/method/ObjectId/ "https://docs.mongodb.com/manual/reference/method/ObjectId/")
# Status

This library is considered production ready.
# Description

This Lua library is a mongodb objectid implement for the ngx_lua nginx module:
# Synopsis

```
local objectid = require "resty.objectid"

local machine_id = 100

local str = objectid.generate_id(machine_id)

ngx.print(str)
```
# Requires

# TODO

# See Also

