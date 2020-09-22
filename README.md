# whatsapp-widget 
Simple floating plugin in the footer of your website:

# Screenshot
![Screenshot](https://github.com/wribeiiro/whatsapp-widget/blob/master/screenshot.jpeg)

Simple floating plugin in the footer of your website:

See the [project page](https://wwww.wribeiiro.com/whatsapp-widget/) for a demonstration.

## Quick start

1\.  Add whatsapp-widget files:

```html
<link  href="/path/to/whatsapp-widget.css" rel="stylesheet">
<script src="/path/to/whatsapp-widget.js"></script>
```


2\.  Call function, without parameters:
```javascript
initWidget({})
```

4\. Standard parameters! But you can pass a new configuration object, see below:
```object
{
    optionsPopup: {
        background: '#095E54',
        color: '#FFFFFF'
    },
    optionsIcon: {
        background: '#24CD63',
        color: '#FFFFFF'
    },
    optionsChat: {
        buttonTarget: `https://api.whatsapp.com/send?phone=+55479999999999&text=${encodeURIComponent("Hello everyone")}`,
        text: 'Open chat'
    },
    optionsBot: {
        name: 'Bot',
        image: 'https://img.icons8.com/plasticine/2x/bot.png',
        messageDefault: 'Hi, 👋 how can I help you?',
        messageTyping: 'is typing...'
    }
}
```