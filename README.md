# TEXT MANIPULATOR README

Easily convert strings in your code with functions like camelCase, toUpper, replace, and many more.

![Demo Gif](images/demo.gif?raw=true "Demo Gif")

## Features

The following string functions (powered by lodash) are implimented in this extension:

1.  camelCase ( Example_TEXT => `exampleText` )
2.  capitalize ( Example_TEXT => `Example_text` )
3.  constantCase ( Example_TEXT => `EXAMPLE_TEXT` )
4.  deburr ( Examplé_TEXT => `Example_TEXT` )
5.  dotCase ( Example_TEXT => `example.text` )
6.  escape ( <Example&Text> => `&lt;Example&amp;text&gt;` )
7.  escapeRegExp ( [text](https://host.com/) => `\[text\]\(https://host\.com/\` ) 
8.  kebabCase ( Example_TEXT => `example-text` )
9.  lowerCase ( Example_TEXT => `example_text` )
10. lowerFirst ( EXAMPLE_Text => `eXAMPLE_Text` )
11. pad ( Example_TEXT with length 20 and character `_` => `____Example_TEXT____` )
12. padEnd
13. padStart
14. parseInt
15. pascalCase
16. pathCase
17. repeat
18. replace
19. snakeCase
20. spaceCase
21. split
22. startCase
23. toLower
24. toUpper
25. trim
26. trimEnd
27. trimStart
28. unescape
29. upperCase
30. upperFirst
31. words

## Requirements

Simply highlight the text you wish to convert, press shift + cmd + p (mac), type the name of the command you wish to use, and press enter.

## Extension Settings

This extension does not currently take any settings. Simply install it, and it works.

## Known Issues

This extension has no known issues, but please report any you find. The functions are powered by lodash which has been extensively tested.

## Release Notes

### See the CHANGELOG for notes on each release.

-----------------------------------------------------------------------------------------------------------

## Thanks

We must thank [lodash](https://lodash.com) since their code backs all of the conversions in this extension.

**Enjoy!**
