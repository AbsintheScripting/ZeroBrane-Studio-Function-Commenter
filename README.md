### This function commenter is only for ZeroBrane Studio.

## WHAT IS DOES:
If you have a regular function like this:

```lua
function test(someParam, someOtherParam)
	return nil
end
```

you type 3x - above the function and it automatically generates a function comment like this:

```lua
--- test 
-- 
-- @param someParam
-- @param someOtherParam
-- @return 
```

The comment style is compatible to [LDoc](https://github.com/stevedonovan/LDoc), a Lua documentation tool.

## INSTALL:
Place functioncomment.lua into HOME/.zbstudio/packages or ZBS/packages/ (for more info see: [ZeroBrane Studio Plugin Installation](https://studio.zerobrane.com/doc-plugin#plugin-installation))
