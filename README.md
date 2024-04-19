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
       pandoc/extra test.md -o test.pdf --template agi --listings --pdf-engine=xelatex
```