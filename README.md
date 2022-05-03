*How to invoke*

```
aws lambda invoke --function-name lambda-yt-example --cli-binary-format raw-in-base64-out --payload '{"what is your name?": "Jim", "How old are you?": 33}' output.txt
```