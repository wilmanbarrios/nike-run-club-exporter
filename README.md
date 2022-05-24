# Nike Run Club exporter

Free your data from Nike servers 😎

## Usage

- Clone this repo and install dependencies

- Use the command below to open the Nike login page or [click here](https://unite.nike.com/s3/unite/mobile.html?androidSDKVersion=3.1.0&corsoverride=https://unite.nike.com&uxid=com.nike.sport.running.droid.3.8&locale=en_US&backendEnvironment=identity&view=login&clientId=WLr1eIG5JSNNcBJM3npVa6L76MK8OBTt&facebookAppId=84697719333&wechatAppId=wxde7d0246cfaf32f7#%7B%22user_id%22:%22b797ad7b-508d-4215-a7e1-964428bd6e20%22,%22access_token%22:%22eyJhbGciOiJSUzI1NiIsImtpZCI6ImVkZmY4YTAyLWIyZGEtNDhkZC1iOGVjLThhMmM1MGE2YTM0MnNpZyJ9.eyJ0cnVzdCI6MTAwLCJpYXQiOjE2NTMzMjE2NjAsImV4cCI6MTY1MzMyNTI2MCwiaXNzIjoib2F1dGgyYWNjIiwianRpIjoiMmU5YjAyNGMtMGIyNi00NGFiLWI2MzQtM2M0Y2Q2Zjk2OWE4IiwibGF0IjoxNjUzMzIxNjYwLCJhdWQiOiJjb20ubmlrZS5kaWdpdGFsIiwic3ViIjoiY29tLm5pa2Uuc3BvcnQucnVubmluZy5kcm9pZCIsInNidCI6Im5pa2U6YXBwIiwic2NwIjpbIm5pa2UuZGlnaXRhbCJdLCJwcm4iOiJiNzk3YWQ3Yi01MDhkLTQyMTUtYTdlMS05NjQ0MjhiZDZlMjAiLCJwcnQiOiJuaWtlOnBsdXMifQ.NpBsunJN9JNojm3TeFemnaT3v5R7qlX0BsSNSosIAXqELQXFcoVlrI0oWIWHhTiR_zBT3ddRXxu_eSuJvAGrCArjPCdsRSDdRg2R32J4dAjR-wO9sKfXydU9f2bIqXSId3aG8SasDjfSJCWsdQDiAjDDMWiOlmet80wEj6dzCLRj4egj8aKcLyZgfKDdEq6GO4lsI9REEIDHdlKWsISW3yuBXCoK8FEwWsx_TeLLgA07VpJWt797HndGIlYuEJCDs0P-j_7SvzgyEC407Z10MoBwXGLsBdxI31hotDbHIrFEpHq1rfJ1-1g4cJc8jS_fF0zuCWmk3HgUMmWeqXKwtA%22,%22refresh_token%22:%22eyJhbGciOiJSUzI1NiIsImtpZCI6ImU2YTIzYjUxLTIwNDEtNDBkNS05MjEyLTU5NGQxOTM3NzA2ZnNpZyJ9.eyJ0cnVzdCI6MTAwLCJpYXQiOjE2NTMzMjE2NjAsImV4cCI6MTY4NDg1NzY2MCwiaXNzIjoib2F1dGgyaWR0IiwianRpIjoiZDc3NThhNmItNDUxOC00ZDU2LTk0MGYtZGNlMWEwM2ZjMjlkIiwibGF0IjoxNjUzMzIxNjYwLCJhdWQiOiJvYXV0aDJpZHQiLCJjbGkiOiJXTHIxZUlHNUpTTk5jQkpNM25wVmE2TDc2TUs4T0JUdCIsInN1YiI6ImI3OTdhZDdiLTUwOGQtNDIxNS1hN2UxLTk2NDQyOGJkNmUyMCIsInNidCI6Im5pa2U6cGx1cyJ9.g9CKwwmwRgrCYhKc--ufmZfc6NO3mDzCgVxQEjKTg3yieREC-iTYY3N4DewsTXaYv5407W92B3t96IxRp3QbaV8IkqaF0uvUaaT7w8kmUQ4Tf3obVZ8qVNBZz3lwGqJx6QZKRR4X01jqwyjUK5A4rxMeFzl7y3xghQ4xB2reFPLitypX3EjML3m50Aiik-90kFzccBxSO4Snj6n59dJE2ZSNDvqhi516IdgpzBOJZu48KDDpUP0XBkfKaOCKHQhqjuPFoV3ZxcX9pRgLWCibLSjLjPHke0uwl_764XYTvy8Dp8BaFZLx3FwIHdf9eQaBBG7s8czcJ9iXc-CP8DFe_A%22,%22expires_in%22:%223600%22,%22token_type%22:%22bearer%22,%22user%22:%7B%22account%22:%7B%22registration%22:%7B%22date%22:1618019899356,%22siteId%22:%22nikedotcom%22,%22wasScreenNameAutoGenerated%22:%22true%22%7D%7D,%22dob%22:%7B%22date%22:561340800000,%22day%22:16,%22month%22:10,%22year%22:1987%7D,%22emails%22:%7B%22primary%22:%7B%22email%22:%22geidelguerra@protonmail.com%22,%22label%22:%22primary%22%7D%7D,%22gender%22:%22M%22,%22language%22:%22en%22,%22locale%22:%22en_US%22,%22location%22:%7B%22country%22:%22US%22,%22visibility%22:%22PRIVATE%22%7D,%22marketing%22:%7B%22datashare%22:%7B%2200001%22:%7B%22id%22:%2200001%22,%22active%22:false%7D%7D,%22email%22:false%7D,%22measurements%22:%7B%22height%22:178,%22weight%22:81%7D,%22name%22:%7B%22latin%22:%7B%22family%22:%22Guerra%22,%22given%22:%22Geidel%22%7D%7D,%22nuId%22:%22b0562088e759453683d8d7b76c78941e%22,%22preferences%22:%7B%22heightUnit%22:%22M/CM%22,%22weightUnit%22:%22KILOGRAMS%22,%22distanceUnit%22:%22KILOMETERS%22%7D,%22screenname%22:%22GeidelG58520900%22,%22social%22:%7B%22allowtagging%22:false,%22visibility%22:%22SOCIAL%22%7D,%22upmId%22:%22b797ad7b-508d-4215-a7e1-964428bd6e20%22,%22userType%22:%22MEMBER%22,%22username%22:%22geidelguerra@protonmail.com%22%7D,%22timestamp%22:%221653321661%22,%22clientId%22:%22WLr1eIG5JSNNcBJM3npVa6L76MK8OBTt%22,%22uxId%22:%22com.nike.sport.running.droid.3.8%22,%22lastLoginTime%22:%221653321661099%22,%22uuid%22:%22b797ad7b-508d-4215-a7e1-964428bd6e20%22,%22meta%22:%7B%22keepMeLoggedIn%22:true,%22language%22:%22en%22,%22country%22:%22US%22,%22experienceId%22:%22com.nike.sport.running.droid.3.8%22,%22mobile%22:false,%22host%22:%22unite.nike.com%22,%22pathname%22:%22/s3/unite/mobile.html%22%7D,%22event%22:%22success%22,%22view%22:%22login%22,%22ts%22:1653321661101%7D)

```
node ./src/index.js open-login-page
```

- Open the network tab of the browser DevTool before login

- Do the login

- Select the request with the URL starting with `https://unite.nike.com/login`

![Screenshot](/screenshot_1.png)

- Copy the `access_token` value seen in the picture above

- Store the token using the following command

```
node ./src/index.js set-token`
```

- Export your activities. A file named `activities.json` will be created in the current directory
```
node ./src/index.js export-activities
```

**Note**

The token expires fast (1 hour)

## Features

- Export activities

## Roadmap

- Unassisted login
- Configurable export file path
