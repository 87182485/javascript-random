# Event Propogations

Three phrases,

1. Event capture, pass event window downstream
2. Event target, reach target dom where trigger the event,
3. Event bubbling, from target dom bubbling up to reach all the way to window

```
e.stopPropogation();
```

Halt event bubbling right after it reaches target.

```
e.preventDefault();
```

Prevent executing dom default event triggerring, i.e, enter -> form submission.
