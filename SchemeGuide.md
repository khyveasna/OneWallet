# OneWallet Scheme Guide



### Add Card
Go to the automatically added card addition screen.

#### Action path
> input  


#### Parameter
| Parameter | Type | Required | Description |
| ------ | ------ | ------ | ------ |
| number | string | Y |  CodeNumber | 
| code_type | string | N(default = CODE_128) |  CodeType | 
| logo_url | string | Y |  Image Url | 
| background_color | string | Y |  RGB or ARGB Code | 
| title | string | Y |  Title | 
| sub_title | string | N |  SubTitle | 
| memo | string | N |  Memo | 
| expired_date | string | N |  Expried mesc | 


#### example

[onewallet://input/number=1234567890123456789&logo_url=https://firebasestorage.googleapis.com/v0/b/mywallet-21196.appspot.com/o/bi%2Fonewallet.png?alt=media&token=080aed6b-e5de-4958-8271-bf3a577e7699&background_color=EEEEEE&title=TextTitle
](onewallet://input/number=1234567890123456789&logo_url=https://firebasestorage.googleapis.com/v0/b/mywallet-21196.appspot.com/o/bi%2Fonewallet.png?alt=media&token=080aed6b-e5de-4958-8271-bf3a577e7699&background_color=EEEEEE&title=TextTitle)

