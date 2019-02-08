# wikicontent

In this repository, all of the wiki content for the [YamlToBot website](https://yamltobot.com)
is stored. This includes images and pages. The reason the wiki content is stored here is to
prevent the website repo from having two copies of the wiki content, one in the `docs` folder
and one in the development workspace. Having this as its separate repository also makes it easier
for others to contribute to the wiki because it is in a central location.

## Structure

All of the wiki content is stored in the `wikicontent` folder. Images and other assets that are
used in the wiki are stored in `wikicontent/_images`. Pages for specific modules are stored in
a folder of the same name as the module (e.g. `wikicontent/discord`).

## Things to note

- When referencing a wiki page or a page on the main YamlToBot website, use a relative URL, e.g. `wiki/...`

- When referencing an image on the wiki, use the full url, e.g. `https://wikicontent.yamltobot.com/wikicontent/--images/...`
