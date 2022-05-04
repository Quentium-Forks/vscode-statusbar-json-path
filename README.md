# Copy JSON Path

Shows the path to the selected JSON Property in the StatusBar.

![JSONPath](./resources/jsonpath.png)

⚠️ Only works for registered JSON files. (json, jsonc, asl, ssm-json)

If you want to alias a JSON like file, add this to your config.json

```json
"files.associations": {
    "*.myjson": "json"
}
```

#### I forked this repository because I needed a Python like syntax to access elements. As I linted all the files and did my own drastic changes, I didn't planned to create a PR to not mess with the original project. Thanks richie5um for this extension!
