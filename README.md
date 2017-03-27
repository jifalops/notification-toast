[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/notification-toast)

# notification-toast
An app-toast (paper-toast) wrapper for simulating web notifications.

## Installation
```
bower install --save notification-toast
```

## Usage
* Drop `notification-toast` in and call the `show()` method.

## Demo
<!--
```
<custom-element-demo height="300">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="notification-toast.html">
    <next-code-block></next-code-block>  
    <script>
      var toast = document.getElementById('toast');
      var title = document.getElementById('title');
      var body = document.getElementById('body');
      var icon = document.getElementById('icon');
      toast.addEventListener('toast-tap', function() { feedback.innerText = 'on-toast-tap'; });
      toast.addEventListener('toast-cancel', function() { feedback.innerText = 'on-toast-cancel'; });
      function show() {
        toast.show({
          notificationTitle: title.value,
          body: body.value,
          icon: icon.value
        });
      }
    </script>
  </template>
</custom-element-demo>
```
-->

```html
<notification-toast id="toast"></notification-toast>
<input id="title" placeholder="title" value="Title"/><br/>
<input id="body" placeholder="body" value="body"/><br/>
<input id="icon" placeholder="icon" value="demo/monkey.jpg"/><br/>
<button onclick="show()">Show</button>&nbsp;
<button onclick="toast.close()">Close</button><br/>
Last Event: <span id="feedback"></span>
```

Full demo:
[webcomponents.org](https://www.webcomponents.org/element/jifalops/notification-toast/demo/demo/index.html)
| [github](https://jifalops.github.io/notification-toast/components/notification-toast/demo/).

API: [webcomponents.org](https://www.webcomponents.org/element/jifalops/notification-toast/notification-toast)
| [github](https://jifalops.github.io/notification-toast).

## Contributing

1. Fork it on Github.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT](https://opensource.org/licenses/MIT)
