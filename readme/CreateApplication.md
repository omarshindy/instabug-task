# Create Application


**URL** : `/api/application/`

**Method** : `POST`

**Request Body**
```json
{
	"Name": "Omar"
}
```

## Success Response

**Code** : `200 OK`

**Content examples**

The Expected output shoud be like this 

```json
{
    "Token": "c787a831-b41f-494f-9288-322c0abfe51e"
}
```

## Error Response 

if we tried to send wrong data type like follows 

```json
{
	"Name": 1
}
```

The Expected output shoud be like this 

```json
{
    "ErrorMessage": "Invalid Application Name"
}
```
