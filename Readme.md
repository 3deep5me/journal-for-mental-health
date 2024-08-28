# Journal for mental health

Used for eink displays.

## How to build new PDF
```
docker run --rm -v "$(pwd)":/data pandoc/extra:latest -f markdown -t pdf -o output.pdf DE.md -V geometry:top=1cm,left=1cm,right=1cm,bottom=1cm
```