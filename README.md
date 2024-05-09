Trivial project that is broken with vscode cpptools v1.20.5, but works with 1.19.9.

Note my .vscode/settings.json file currently has the following:
```
{
    "C_Cpp.default.compilerPath": "f:\\Program Files\\Microsoft Visual Studio\\2022\\Community\\VC\\Tools\\MSVC\\14.39.33519\\bin\\Hostx64\\x64\\cl.exe",
    "files.associations": {
        "iostream": "cpp"
    }
}
```

But it should work the same without that file.

## Behavior
This will compile and run fine in both versions of the extension.

However, v.1.20.5 shows the following ![error image](https://github.com/shimaowo/broken_cpp_vsix/blob/master/error.png?raw=true)

In v1.20.5, neither intellisense nor browse functionality will work for any system header.
