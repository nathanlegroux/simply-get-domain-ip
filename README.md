


## Get google.com domain's ip with $_GET request named "domain"


```php

<?php if (empty($_GET["domain"]))
{
    $domain = 'google.com';
}
else
{
    $domain = $_GET["domain"];
}
$x = gethostbyname($domain);

echo $x;

?>





```

## Get google.com domain's ip with $_POST request named "domain"

```php

<?php if (empty($_POST["domain"]))
{
    $domain = 'google.com';
}
else
{
    $domain = $_POST["domain"];
}
$x = gethostbyname($domain);

echo $x;

?>

```



## Live version here : https://arni.fr/web-ip/

