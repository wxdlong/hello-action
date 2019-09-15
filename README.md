# helloAction

This is just a copy of hello world docker action.     
Refer to [First Action to market](https://ycat.top/post/publish_action_2market/)

## Notes
1. repo name shouldn't contain capital letter, like `helloAction`. otherwise 
`##[warning]Failed to download action 'https://api.github.com/repos/wxdlong/helloAction/tarball/master'. Error Response status code does not indicate success: 404 (Not Found).`

2. you should setup [two-factor-authentication](https://help.github.com/en/articles/configuring-two-factor-authentication) before publish

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"wxdlong"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: wxdlong/hello-action@v7
with:
  who-to-greet: 'Mona the Octocat'
```

## Contact

https://ycat.top