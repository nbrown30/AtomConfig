# AtomConfig
Atom with MavensMate, styled to look and feel like Sublime Text 3.

## Community Packages

Rather than store the packages in GitHub we can export their names and install all of them at once with `apm`.

```bash
    apm list --installed --bare > package-backup.txt

    apm install --package-file package-backup.txt
```

## MavensMate configuration
Ensure the Atom path in MavensMate is set correctly for your operating system. If not you will receive this error:

```
    [ERROR] result.resolve is not a function
```

This is indicative of a bad path. 
