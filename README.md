# AtomConfig
Personal Atom configuration

## Make it work like Sublime with MavensMate
This config is customized to mimic a Monokai Sublime Text 3 editor as much as possible.

## Community Packages

Rather than store the packages in GitHub we can export their names and install all of them at once with `apm`.

```bash
    apm list --installed --bare > package-backup.txt

    apm install --package-file package-backup.txt
```
