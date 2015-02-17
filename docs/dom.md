# HTML5 Protractor Tools Documentation - DOM

## Functions

### `waitForDisplayed(element)`

Makes the test execution wait for the specified element to be displayed. Use this instead of resorting to `sleep()`.

```
html5.dom.waitForDisplayed(element(by.css('div[...]')));
```

### `waitForNotDisplayed(element)`

Makes the test execution wait for the specified element to be no longer displayed.

```
html5.dom.waitForNotDisplayed(element(by.css('div[...]')));
```