# Export-DatabaseObject 

Exports database objects as t-sql scripts.

## Usage

The function `Export-DatabaseObject` contained in the script `Export-DatabaseObject.ps1` must be imported prior to usage.

### Example 1:

    . .\Export-DatabaseObject.ps1
    Export-DatabaseObject -Instance '.' -DBList 'Database1, Database2' -OutputPath 'C:\temp\ScriptedDatabases'