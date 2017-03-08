# atomConfigs

How to import atom's configs:

- replace the repo files with the ones that already exist in the local .atom folder;
- execute the importation command:
```
apm install `cat packages.list`
```



## Committing instructions:
- Everytime a new package is added/removed, you need to export the new version of the packages list file and upload it on the repo:
`apm list --installed --bare > packages.list`
