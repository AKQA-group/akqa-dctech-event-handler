# Event Handler

## Usage

```javascript
var obj = {};
EventHandler.createTarget(obj);

// listen to the "wee" event
obj.addEventListener('wee', function () {
    // wee was trigger!
});

// trigger the event
obj.dispatchEvent('wee');

EventHandler.destroyTarget(obj);

```