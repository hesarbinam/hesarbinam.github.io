<h2 dir="rtl"> مثال اعتبار سنجی فرم ها با جاوا اسکریپت :</h2>
<br>

```html
<!doctype html>
<html dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>اعتبار نجی فرم ها با جاوا اسکریپت</title>
</head>
<body>

<center style="margin-top: 100px">

    <div style="border: 2px solid red; padding: 20px">   نام : <input  style="height: 30px" type="text"  id="in_name"> فامیل : <input style="height: 30px" type="text" id="in_family"> </div>
    <br>
    <div style="border: 2px solid red; padding: 20px"> پسورد : <input style="height: 30px" type="text" id="in_password"><br> تکرار پسورد : <input id="in_password_d" style="height: 30px;margin-top: 20px; margin-left: 38px" type="text"> </div>


</center>

</body>

    <script>
        
        
        function check(){
            
            var name = document.getElementById('in_name').value;
            var family = document.getElementById('in_family').value;
            var password = document.getElementById('in_password').value;
            var password_d = document.getElementById('in_password_d').value;
            
            
            
            
        }
        
    </script>    

</html>
```
