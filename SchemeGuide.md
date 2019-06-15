## OneWallet Scheme Guide


### Basic information

Onewallet URL Scheme starts with `onewallet://`, as shown in the following URL structure.

You can specify the type of feature in actionPath, and required parameters for each feature in `parameter=value`. Refer to the description of parameters for each feature, for more information.


<br>
<br>


### Add Card
Go to the automatically added card addition screen.

##### Action path
> input  



##### Parameter
| Parameter | Type | Required | Description |
| ------ | ------ | ------ | ------ |
| number | string | Y |  CodeNumber | 
| code_type | string | N(default = CODE_128) |  CodeType [CODE_128, QR_CODE, PDF_417, AZTEC] | 
| logo_url | string | Y |  Image Url | 
| background_color | string | N(default = 666666) |  RGB or ARGB Code | 
| title | string | Y |  Title | 
| sub_title | string | N |  SubTitle | 
| memo | string | N |  Memo | 
| expired_date | string | N |  Expried mesc | 



<br>
   
##### Example

[onewallet://input?number=1234567890123456789&logo_url=https%3A%2F%2Ffirebasestorage.googleapis.com%2Fv0%2Fb%2Fmywallet-21196.appspot.com%2Fo%2Fbi%252Fonewallet.png%3Falt%3Dmedia%26token%3D080aed6b-e5de-4958-8271-bf3a577e7699&title=TextTitle
](onewallet://input?number=1234567890123456789&logo_url=https%3A%2F%2Ffirebasestorage.googleapis.com%2Fv0%2Fb%2Fmywallet-21196.appspot.com%2Fo%2Fbi%252Fonewallet.png%3Falt%3Dmedia%26token%3D080aed6b-e5de-4958-8271-bf3a577e7699&title=TextTitle)




