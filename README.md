

```
r language giardia, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis giardiazis TR, echo = (language == "TR")
## giardia - giardiazis {#sec-giardia }
```


```
asis giardiasis EN, echo = (language == "EN")
## giardia - giardiasis {#sec-giardia }
```






```
r giardia screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_giardia-HE.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/giardia/HE.html",
  file = "./screenshots/thumbnail_giardia-HE.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/giardia/HE.html](https://images.patolojiatlasi.com/giardia/HE.html)





```
asis, echo = (language == "TR")

**giardiazis**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_giardia-HE.png){width="25%"}](https://images.patolojiatlasi.com/giardia/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/giardia/HE.html)
```

```
asis, echo = (language == "EN")

**giardiasis**

[![Click for Full Screen WSI](./screenshots/thumbnail_giardia-HE.png){width="25%"}](https://images.patolojiatlasi.com/giardia/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/giardia/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/giardia/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/giardia/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

giardiazis

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

giardiasis

:::

```









:::::









