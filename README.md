# bmd-statusPage

BMD Status Page Mod.
![Action Interface](https://github.com/slothyace/bmd-statusPage/blob/main/.docs/image.png)

## Submitting A Theme

You can submit your own theme by:

1. [Forking the repo](https://github.com/slothyace/bmd-statusPage/fork).
2. Making a new folder under the `themes` directory.
3. Creating the necessary files.
4. Making a pull request.

The folder's name will be taken as the theme's name.<br>
Example: A theme named `galaxy` will be located in `themes/galaxy`.

## Documentation

The data structure documentation for this mod is [here](https://github.com/slothyace/bmd-statusPage/blob/main/.docs/dataStructure.md)<br>
The usage documentation for this mod is [here](https://github.com/slothyace/bmd-statusPage/blob/main/.docs/README.md)

## File Requirements

Your folder should include the following files:

- index.html

```
Required as it serves the /statusPage/monitor/view page.
  - This is 100% required
```

- style.css

```
Required as it serves the /statusPage/monitor/style.css page.
  - This can be left out as it is required: false
```

- bmd.ico

```
Required as it serves the tab icon.
  - If file doesn't exist, it will grab the default icon off GitHub
```
