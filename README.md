# pandoc-test

```
docker run --rm \
       --volume "$(pwd):/data" \
       --user $(id -u):$(id -g) \
       pandoc/extra test.md -o test.pdf
```

```
docker run --rm \
       --volume "$(pwd):/data" \
       --user $(id -u):$(id -g) \
       pandoc/extra test.md -o test.pdf --template eisvogel --listings --pdf-engine=xelatex 
```

```
docker run --rm \
       --volume "$(pwd):/data" \
       --volume "$(pwd):/.pandoc" \
       --user $(id -u):$(id -g) \
       pandoc/extra test.md -o test.pdf --template agi --filter pandoc-xnos --listings --pdf-engine=xelatex
```

```
docker run --rm \
       --volume "$(pwd):/data" \
       --volume "$(pwd):/.pandoc" \
       --user $(id -u):$(id -g) \
       pandoc/extra test.md -o test.tex --write=latex --template agi --listings
```



Fehlende Pakete:
- textpos
- datetime2
- pandoc-tablenos -> https://tex.stackexchange.com/questions/139106/referencing-tables-in-pandoc -> https://github.com/jradek/pandoc-docker/blob/master/latex_with_filters/Dockerfile


```
docker run --rm \
       --volume "$(pwd):/data" \
       --volume "$(pwd):/.pandoc" \
       --user $(id -u):$(id -g) \
       pandoc/extra letter.md -o letter.tex --write=latex --template template-letter --listings
```

```
docker run --rm \
       --volume "$(pwd):/data" \
       --volume "$(pwd):/.pandoc" \
       --user $(id -u):$(id -g) \
       pandoc/extra letter.md -o letter.pdf --template template-letter --listings --pdf-engine=xelatex 
```


```
docker run --rm \
       --volume "$(pwd):/data" \
       --volume "$(pwd):/.pandoc" \
       --user $(id -u):$(id -g) \
       --entrypoint xelatex pandoc/extra myletter.tex
```