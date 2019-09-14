# helloAction

This is just a copy of hello world docker action.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: wxdlong/helloAction@master
with:
  who-to-greet: 'Mona the Octocat'
```