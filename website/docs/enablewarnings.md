Enables specific compiler warnings.

```lua
enablewarnings { "warnings" }
```

### Parameters ###

`warnings` is a list of warnings to enable.

For Visual Studio, the MSC warning number should be used to specify the warning. On other compilers, the warning should be identified by name.

### Applies To ###

Project configurations.

### Availability ###

Premake 5.0 or later.

### See Also ###

* [disablewarnings](disablewarnings.md)
* [fatalwarnings](fatalwarnings.md)
