# Test 1

```as3
L10NE.addDictionary(dictionary:L10NEDictionary);
```

# Test 2

```actionscript3
L10NE.addDictionary(new L10NEDictionary(<dictionary id="eng"><string lionid="test1">Hello, World</string></dictionary>));
```

# Test 3

```actionscript3
L10NE.addDictionary(new L10NEDictionary(<dictionary id="eng"><string lionid="test1">Hello, World</string></dictionary>));
```

# Test 4

```as3
[Test(async, ui)]
public function defaultColor():void
{
	var component:Square = new Square();
	Async.proceedOnEvent(this, component, Event.ADDED);
    UIImpersonator.addChild(component);
	
	// this is the line!
	assertTrue(Screenshot.compare("SquareTest.defaultColor", component));
}
```
