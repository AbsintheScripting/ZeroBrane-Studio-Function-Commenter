This function commenter is only for ZeroBrane Studio.

WHAT IS DOES:
If you have a function like:

function test(someParam, someOtherParam)
	return nil
end

you type 3 '-' and it automatically generates a function comment like this:
--- test 
-- 
-- @param someParam
-- @param someOtherParam
-- @return 

INSTALL:
Place functioncomment.lua into HOME/.zbstudio/packages or ZBS/packages/
