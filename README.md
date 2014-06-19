# jQuery Range

http://jcemer.com/jquery-range

Input range implementation to works with touch using jQuery

``` html
<input type="range" min="0" max="4" value="0">
<input type="range" class="inside" min="-5" max="5" value="0">
```

``` javascript
$('input[type="range"]').range();
$('input[type="range"]').range('worst', 'best');
```

## Modes

* `normal`
* `inside`

## Events

* `init`
* `move`
* `change`