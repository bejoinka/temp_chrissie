# temp_chrissie

.vscode/launch.json file should look like this
```
{
"configurations": [
{
    "name": "Python: Django",
    "type": "python",
    "request": "launch",
    "program": "${workspaceFolder}/manage.py",
    "args": [
        "runserver",
        "{{do you put something in here so it watches files and reloads?}}"
    ],
    "django": true
}
]
```
