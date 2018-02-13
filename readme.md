
# Semantic UI Alerts (V.1.0)

A simple, beautiful, essay, semantic ui alerts library powered by
[Semantic-UI](semantic-ui.com)

## Demo

https://jeevan15498.github.io/Semantic-UI-Alerts/

## Get Started

### HTML

```html
<html>
    <head>
    <title></title>
    <link rel="stylesheet" type="text/css" href="css/semantic.min.css">
    <script type="text/javascript" src="js/jquery-3.0.0.min.js"></script>
    <script type="text/javascript" src="js/semantic.min.js"></script>
    
    <link rel="stylesheet" type="text/css" href="dist/semantic-ui-alerts.css">
    <script type="text/javascript" src="dist/semantic-ui-alerts.js"></script>
    </head>
    <body>

    </body>
</html>
```


### Javascript

```javascript
$.suiAlert({
    title: 'Semantic UI Alerts',
    description: 'A message displays information that explains nearby content',
    type: 'warning',
    time: '3',
    position: 'bottom-left',
});
```