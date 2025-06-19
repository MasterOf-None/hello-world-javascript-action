# Hello world Javascript action

This action prints "Hello World" or "Help" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

```yaml
uses: actions/hello-world-javascript-actions@v1
with:
  who-to-greet: Mona the Octocat
```
