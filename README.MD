# SingleFile

This repo has been forked from the excellent [SingleFile](https://github.com/gildas-lormeau/SingleFile) to meet a specific project's needs.
Our modifications are unlikely to be useful or relevant to other users, and we direct people back to the original [SingleFile](https://github.com/gildas-lormeau/SingleFile) repo.

Modifications:
* Reduce README to our needs and license info
* Simplify build and manifest as only building for Firefox
* Change default config settings to meet our needs
* Save the webpage height and width in the inserted metadata at the top of the page
* Tweak iframe sandboxing to meet our needs

## To build and use locally

    $ npm install
    $ ./build-extension.sh

You shoudl now have a `singlefile-extension-firefox.zip`. Next:

* Ensure that you are using nightly or developer edition of FF. 
* In `about:config` set `xpinstall.signatures.required` to false.
* In `about:addons` from the dropdown menu, install from file and select created zip.

## Privacy Policy
See https://github.com/gildas-lormeau/SingleFile/blob/master/privacy.md

## Contributors
- Chinese translation done by yfdyh000 (https://github.com/yfdyh000), KrasnayaPloshchad (https://github.com/KrasnayaPloshchad), frostblazergit (https://github.com/frostblazergit)
- Traditional Chinese translation done by frostblazergit (https://github.com/frostblazergit)
- German translation done by womotroll (https://github.com/womotroll), bannmann (https://github.com/bannmann)
- Japanese translation done by Shitennouji（四天王寺) (https://github.com/Shitennouji)
- Polish translation done by xesarni (https://github.com/xesarni)
- Russian translation done by rstp14 (https://github.com/rstp14), kramola-RU (https://github.com/kramola-RU), solokot (https://github.com/solokot), TotalCaesar659 (https://github.com/TotalCaesar659)
- Ukrainian translation done by perdolka (https://github.com/perdolka)
- Spanish translation done by strel (https://github.com/strel)

## Code derived from third party projects
- csstree: https://github.com/csstree/csstree
- postcss-media-query-parser: https://github.com/dryoma/postcss-media-query-parser
- postcss-selector-parser: https://github.com/postcss/postcss-selector-parser
- UglifyCSS: https://github.com/fmarcia/UglifyCSS
- parse-srcset: https://github.com/albell/parse-srcset
- parse-css-font: https://github.com/jedmao/parse-css-font
- Readability: https://github.com/mozilla/readability

## Icons
- Icon made by [Kiranshastry](https://www.flaticon.com/authors/kiranshastry) from  [Flaticon](https://www.flaticon.com/) is licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)

## License
SingleFile is licensed under AGPL. Code derived from third-party projects is licensed under MIT. Please contact me at gildas.lormeau &lt;at&gt; gmail.com if you are interested in licensing the SingleFile code for a commercial service or product.

Suggestions are welcome :)
