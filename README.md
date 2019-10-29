# Presentations and Such



## And Such

### Notes on Xaringan

#### Themes

Use [xaringanthemer](https://pkg.garrickadenbuie.com/xaringanthemer/articles/xaringanthemer.html)

Add this to header:
```
output:
  xaringan::moon_reader:
    lib_dir: libs
    css: xaringan-themer.css
```
Add this to a code chunk below the knitr one:

```{r xaringan-themer, include = FALSE}
library(xaringanthemer)
# Theme info
mono_light(
  base_color = "#1c5253",
  header_font_google = google_font("Josefin Sans"),
  text_font_google   = google_font("Montserrat", "300", "300i"),
  code_font_google   = google_font("Droid Mono")
)

```

#### Running a Server
*The following allows an auto-updating server to show the presentation as it is built.*

1. Create a new rmd file from Xaringan template
2. Run ```xaringan::inf_mr()``` in the console. 
3. Follow link to the site shown.
4. Any saved changes will show up in the served presentation.
