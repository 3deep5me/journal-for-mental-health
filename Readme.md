# Journal for mental health

Used for eink displays.

## How to build new PDF
```
docker run --rm -v "$(pwd)":/data pandoc/extra:latest -f markdown -t pdf --template=a5.tex -o output.pdf DE.md
```