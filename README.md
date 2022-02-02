# VisualRegression

A fork of BackstopJS that works well within a folder along side Sitefinity

## Instructions  

Copy the `VisualRegression` folder into your Sitefinity application and upload the folder with your site after running the [BackstopJS](https://garris.github.io/BackstopJS/) tool.

You can ignore uploading the `node modules` folder and it is used for development not hosting but you need to include the `bitmaps_test` and `bitmaps_reference`.

You can then let your users view the BackstopJS output via `{your site}/VisualRegression/index.html`

### Using the tool

Install backstopjs globally with `npm install -g backstopjs`

Add your urls to the `backstop.json` that you want to test.

Run `backstop reference` to grab screens from the reference URLs

Run `backstop test` to test

Run `backstop approve` to approve the results and create a new baseline of reference bitmaps.
