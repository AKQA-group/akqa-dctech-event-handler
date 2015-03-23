# Event Handler

## Usage

```javascript
var obj = {};
EventHandler.createTarget(obj);

// listen to events
obj.addEventListener('wee', function () {
    // wee was trigger!
});

obj.dispatchEvent('wee');

EventHandler.destroyTarget(obj);

```