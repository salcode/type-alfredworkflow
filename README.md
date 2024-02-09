# Example Alfred Workflow to Type

This is an Alfred Workflow to go with my blog post [Alfred Paste Without Clipboard](https://salferrarello.com/alfred-paste-without-clipboard).

This workflow types into the current application.

## How to Install this Alfred Workflow

1. Open the Alfred Preferences and go to the [Alfred Workflows](https://www.alfredapp.com/workflows/) page
2. Drag and drop the `alfredworkflow` file from this repo into the Alfred Workflows page
3. Click the `Install` button

## How to Use

1. Open an application and put the cursor in a field where you can type (e.g. a code editor or a web browser URL bar)
2. Launch Alfred
3. Type
    ```
    typequery This is the text I'm typing
    ```
4. Press the `Enter` key

At this point, "This is the text I'm typing" should be typed into the field where your cursor was located.

### Alternate Keyword

Alternatively, you could type

```
typevariable
```

which will type the hardcoded string "This is the string stored in myvar!" into the field where your cursor was located.


