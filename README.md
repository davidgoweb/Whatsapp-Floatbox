# Whatsapp Floatbox

A lightweight responsive whatsapp api chatbox for your website. Easy to use.
Put a whatsapp floating chat box on your website.

This project is my own base template that can easily customized. .

## Usege

### Links and Scripts
```
<link rel='stylesheet' type='text/css' media='screen' href='css/wafloatbox-0.2.min.css'>
<script src='js/jquery-3.4.1.min.js'></script>
<script src='js/wafloatbox-0.2.js'></script>
```
### HTML Markup
 
```
    <div class="myk-wa">
        <div class="myk-item" data-wanumber="62xxxxxxxx" data-waname="Jonny" data-wadivision="Technician" data-waava="images/user.png"></div>
        <div class="myk-item" data-wanumber="92xxxxxxx" data-waname="Rachel" data-wadivision="Sales" data-waava="images/user.png"></div>
        <!-- few more -->
    </div>
```
### Initializing
```
<script>
    $(document).ready(function(){
        $(".myk-wa").WAFloatBox();
    });
</script>
```

## License

This project is under MIT License
That's it.
