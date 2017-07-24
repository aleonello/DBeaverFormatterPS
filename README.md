# DBeaverFormatterPS
Powershell script for Dbeaver SQL Formatter

## Note:

This script works with DBeaver 4.1.0 version

## Usage:

* Save the format_sql.ps1 file on local computer
* On SQL Formatting Preferences, set External Formatter option and check the "Use temp file" option
* Paste the following code on "Command Line" field, replacing the "<Path>" with the full path where the file format_sql_.ps1 file was saved, e.g. "C:\temp\format_sql.ps1"

```
powershell -noprofile -executionpolicy bypass -File <Path>/format_sql.ps1 ${file}
```

## Important:

This is a initial script version, some SQL keys isn't included. Please give your feedback on e-mail aleonello@gmail.com
