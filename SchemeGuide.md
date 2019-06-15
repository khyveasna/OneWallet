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
| code_type | string | N(default = CODE_128) |  CodeType, [CODE_128, QR_CODE, PDF_417, AZTEC] | 
| logo_url | string | Y |  Image Url | 
| background_color | string | Y |  RGB or ARGB Code | 
| title | string | Y |  Title | 
| sub_title | string | N |  SubTitle | 
| memo | string | N |  Memo | 
| expired_date | string | N |  Expried mesc | 



<br>
   
##### Example

[onewallet://input/number=1234567890123456789&logo_url=https://firebasestorage.googleapis.com/v0/b/mywallet-21196.appspot.com/o/bi%2Fonewallet.png?alt=media&token=080aed6b-e5de-4958-8271-bf3a577e7699&background_color=EEEEEE&title=TextTitle
](onewallet://input/number=1234567890123456789&logo_url=https://firebasestorage.googleapis.com/v0/b/mywallet-21196.appspot.com/o/bi%2Fonewallet.png?alt=media&token=080aed6b-e5de-4958-8271-bf3a577e7699&background_color=EEEEEE&title=TextTitle)




