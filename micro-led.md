# Micro LED

## Toglle an LED

 Drag the code to toggle an LED.

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```

## Randomize x
Drag the code to pick a randon ``x`` index between ``0`` and ``4``.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 10), 0)
})

```
## Randomize y
Drag the code to pick a randon ``y`` index between ``0`` and ``4``.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 10), randint(0, 10))
})
```


## All the code
```blocks
basic.forever(function () {
    led.toggle(randint(0, 10), randint(0, 10))
})
```