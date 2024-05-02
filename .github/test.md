# [System]{.ul}

## Sytem info

```{r eval=FALSE}
Sys.info()
#Sys.info()["nodename"]=="sce-ide-001"

Sys.getenv()
```

## Global options

```{r eval=FALSE}
#Disabling scientific notation in R
options(scipen = 999)
# Resseting default option
options(scipen=0, digits=7)
```
