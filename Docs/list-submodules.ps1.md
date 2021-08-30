# PowerShell Script list-submodules.ps1

## Synopsis & Description
```powershell
list-submodules.ps1 [<repo-dir>]
```

Lists the submodules of the current/given Git repository.

## Syntax & Parameters
```powershell
/home/mf/PowerShell/Scripts/list-submodules.ps1 [[-RepoDir] <String>] [<CommonParameters>]
```

```
-RepoDir <String>
    
    Required?                    false
    Position?                    1
    Default value                "$PWD"
    Accept pipeline input?       false
    Accept wildcard characters?  false
```

```
[<CommonParameters>]
    This cmdlet supports the common parameters: Verbose, Debug, ErrorAction, ErrorVariable, WarningAction, 
    WarningVariable, OutBuffer, PipelineVariable, and OutVariable.
```

## Example
```powershell
PS>.\list-submodules.ps1 C:\MyRepo
```


## Notes
Author: Markus Fleschutz · License: CC0

## Related Links
https://github.com/fleschutz/PowerShell

*Generated by convert-ps2md.ps1*