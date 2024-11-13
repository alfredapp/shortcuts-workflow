# Frequently Asked Questions (FAQ)

### How do I fix `Error: Can't get object. (-1728)`?

If you don’t see any result with the workflow and the [debugger](https://www.alfredapp.com/help/workflows/advanced/debugger/) shows a variant of:

```console
/Users/yourname/Library/Caches/com.runningwithcrayons.Alfred/Workflow Scripts/E8485762-E031-5F89-A6EA-948BA2B50FF4: execution error: Error: Error: Can't get object. (-1728)
```

You bumped into a known bug with the Shortcuts app. Look at your list of Shortcuts and you’re likely to find two or more shortcuts with the same name (usually `New Shortcut 1` or similar). Delete the duplicates and try again. Rebooting your Mac is sometimes necessary.

### How do I report a different issue?

Accurate and thorough information is crucial for a proper diagnosis. When reporting issues, please include your *exact* installed versions of:

* The Workflow.
* Alfred.
* macOS.

In addition to:

* The [debugger](https://www.alfredapp.com/help/workflows/advanced/debugger/) output. Perform the failing action and click *Copy* on the top right.
* Details on what you did, what happened, and what you expected to happen. A [short video](https://support.apple.com/en-us/HT208721) of the steps with the debugger open may help to find the problem faster.
