## Auth Service - Create Token

URL: https://securetoken.googleapis.com/v1/token?key=AIzaSyD_rrjNxH9LfmKB0Y0uy7nSfz0zHvvM_Iw \
Method: POST \
Content-Type: ```application/x-www-form-urlencoded``` 

## Body
```x-www-form-urlencoded
grant_type=refresh_token&refresh_token=APZUo0RHUER_uC5027I7MoTsWiBb4YKwub3weqwbDkCWJYYm4n3zMuhOa4PUgWV9AIic1_2smnMtEUWtTcHuoGB9TSQdI3vLKqMsMHkor1j7DGRcqiL-WeKUop9-_8UVFOUXlDBo4lGTgeMxs853p_QTBsAqxvBVRTUUYqipXIIIyPtAtZ89uNY
```

## Example Response

```json
{
    "access_token": "{access_token}", //  Bearer token
    "expires_in": "3600",
    "token_type": "Bearer",
    "refresh_token": "{refresh_token}",
    "id_token": "{id_token}",
    "user_id": "n4OZ8aBtmcMa44Z0bI1pdo22jbo2",
    "project_id": "742299120802"
}
```
## Note

**This is technically making a account as you just create a token and make a [quiz](https://github.com/TwigXx1/bestiefy-api/blob/main/quizzes/create.md) ,so have fun with it** 🤷‍♂️
