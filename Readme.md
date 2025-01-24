# Template to Bruno / usebruno.com

## .env Variable usage:
#### Change the Name from the .envExample file to .env (already included in the .gitignore File) </br> Example Secret is used out of the .env File with "{{process.env.secret}}"

## Set Bearer Token out of Response Body:
#### Get Token Request has an Post Response Script to set the "bearerToken" Environment Variable out of the Response Body: "bru.setEnvVar("bearerToken",res.body.Data.Token);"

## Use Bearer Token
#### In the other Request, the "bearerToken" Environment Variable can be used in the "Auth" Tab with the setting "Bearer Token" and the "{{bearerToken}}" Environment Variable

Visit [usebruno.com Docs](https://docs.usebruno.com/get-started/bruno-basics/create-a-collection) for more information.
