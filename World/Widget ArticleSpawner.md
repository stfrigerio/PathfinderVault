**Template documentation** (for the above template, sometimes hidden or invisible)Template:Tocright
>  **{{#widget: ArticleSpawner}}** creates a form or button that preloads wikitext from [[preload templates]] into the edit window of a new page, and populates the preload template with custom content. This extends (and potentially replaces) the functionality of the [[InputBox]]-driven {{[[ArticleSpawner]]}} template.



## Usage

{{#widget: ArticleSpawner
| type      = 
| summary   = 
| title     = 
| showtitle = 

| param.A Key       = 
| param.Another Key = 
...

| hiddenparam = 
| hiddenparam =
...

| submit = 
}}

>  All fields are optional.

type *(optional)*
Hidden parameter that defines the preload templates to load into the edit window and content above it. Default is blank.
See {{[[ArticleSpawner/doc]]}} for details on PathfinderWiki preload templates and content.
summary *(optional)*
Hidden parameter that sets the text to preload in the editing tool's summary field. Default is blank.
title *(optional)*
Name of the article to edit or create. Default is blank.
If you enter a **title** value and **showtitle** is not passed, this parameter's value fills the ArticleSpawner form's "Article Title" field.
If you enter a **title** value and **showtitle** is no, the value is passed as a hidden parameter; there's no Article Title field, and clicking Submit creates the article using this value as the title.
showtitle *(optional)*
If no, hides the Article Title field. Set to no to create a standalone ArticleSpawner button.
param.(key name) *(optional; can declare multiple times)*
Creates a form field with the (key name) as the field's label and fills the field with the parameter's value. The value can be blank; if you don't pass a key name, it defaults to an integer.
All **param**s are declared in the order you pass them, but before any **hiddenparams** regardless of the order they appear in the template—this is important as the preload template applies values in sequential order, so $1 on the preload template is the first **param** declared in the widget, $2 is the second, etc., and then the first **hiddenparam** declared in the widget follows in the preload template's numeric sequence.
hiddenparam *(optional; can declare multiple times)*
Passes a value as a preload parameter without creating a form field.
submit *(optional)*
Changes the text that appears on the submit button. Default is submit.

## Example


### No parameters

{{#widget: ArticleSpawner}}

>  




Article title: 



>  An ArticleSpawner widget with no parameters displays an Article Title field and Submit button; filling the field and clicking submit is equivalent to clicking a link for an article with the same title.


### Basic parameters

{{#widget: ArticleSpawner
| title     = Squealy Nord
| submit    = Create an article
}}

>  




Article title: 



>  You can fill the Article Title field and Submit button with custom text. Note that the user can still edit the title.


### Button with no fields

{{#widget: ArticleSpawner
| title     = Squealy Nord
| showtitle = no
| submit    = Create the "Squealy Nord" article now!
| summary   = Finally created the Squealy Nord article
}}

>  








>  This button creates an article using [[Squealy Nord]] as the tile, and fills in the edit summary.


### Preload template

{{#widget: ArticleSpawner
| type    = Biography
| summary = New real-world person article
| submit  = New biography
}}

>  




Article title: 



>  When the user fills in a title and clicks the "New biography" button, it takes them to the article page, applies the {{[[ArticleSpawner/Biography]]}} preload template to the edit box, and displays the {{[[ArticleSpawner/Biography/doc]]}} content above the edit box.


### Parameterized preload template

{{#widget: ArticleSpawner
| type        = Biography
| summary     = New real-world freelancer article

| param.Name          = 
| param.Navbox target = freelance
| param.Role category = [[Category:Authors]]

| hiddenparam = [[Category:Freelance contributors]]
| hiddenparam = Freelancer

| submit = New biography
}}

>  




Article title: 
Name: 
Navbox target: 
Role category: 





>  For preload templates with preload parameters ($1, $2, $3, etc.), clicking the "Freelancer biography" button opens the article page, preloads the {{[[ArticleSpawner/Biography]]}} template and fills the preload parameters with the **param** and **hiddenparam** values in order (**param.Name** replaces $1, **param.Navbox target** replaces $2, **param.Role category** replaces $3, the first **hiddenparam** replaces $4, etc.), and displays the {{[[ArticleSpawner/Biography/doc]]}} content above the edit box.
>  Note that if the **hiddenparam**s were placed before the **param**s, they would ***not*** be applied before the **param**s. The widget processes all **param**s in order first, *then* all **hiddenparam**s in order.


## TODO

>  - Handle labels more semantically.
>  - Allow for dropdown options.
>  - Provide field validation options.
>  - Relax param/hiddenparam ordering.
Visit [[Widget:ArticleSpawner/doc]] to edit this text! ([[How does this work]]?)




