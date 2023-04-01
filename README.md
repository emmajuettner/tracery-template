# Tracery Template Project

This is a template for creating static webpages that generate text using a Tracery grammar.
It includes a copy of the [minified Tracery grammar](https://github.com/galaxykate/tracery/blob/master/js/tracery.min.js),
as well as jquery,
plus some js code that hooks up tracery to the 'Generate' button, a basic HTML layout, and some minimal CSS styles.
Each time you click the 'Generate' button, it will generate a new output from the Tracery grammar.

You can see the template page live [here](https://emmajuettner.com/tracery-template/). 
And here's [a real example](https://emmajuettner.com/an-expanded-meditation/) where I've customized the template
to display my Moby Dick NaNoGenMo tracery grammar.

I put this project together because I wanted to have a quick, hassle-free way to stick a Tracery grammar on a webpage
where people can interact with it. It's mainly intended for my own use, but I figured others might find it useful as well,
so that's why I'm putting it up on Github. Feel free to copy and modify the template to show off your own Tracery projects!

## Customizing this template

This template can generate text from multiple tracery grammars. Currently there's one grammar that generates the title (title-grammar.json), 
and another that generates the main content (main-grammar.json). You can modify them, add more, or remove one of them and just use one grammar, whatever you prefer.
The file 'generate.js' does the work of loading the JSON from these files, turning them into tracery grammars, and creating
text from the grammars whenever the "Generate!" button is pressed.

You can change the structure of the page and remove/modify the explanatory text box in index.html, or change the styles in styles.css.

This is a static site that can be hosted on Github Pages or any other tool that can host static webpages.

## License

This project inherits Tracery's Apache License 2.0.

```
Copyright 2023 Emma Juettner
Based on code by Kate Compton

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
