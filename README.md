adblocker-detector
==================

**adblocker-detector** is a tiny javascript function for detecting whether or not your visitors are using an ad blocker.

Example usage:

```javascript
detectAdBlock(function(active){
    if (active) {
        alert('AdBlocker detected!');
    } else {
        alert('AdBlocker not detected. All clear');
    }
});
```

\* Once executed, ad blocker status is made available via ```window.__adblocker__```,
so for future runs, use:

```javascript
if (window.__adblocker__) {
    alert('AdBlocker detected!');
} else {
    alert('AdBlocker not detected. All clear');
}

```

Enjoy!