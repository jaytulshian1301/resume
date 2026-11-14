# resume
My personal resume: [`jay_tulshian.tex`](jay_tulshian.tex) / [`jay_tulshian.pdf`](jay_tulshian.pdf)

Build with Docker:

```sh
docker run --rm -v "$PWD":/data -w /data texlive/texlive:latest pdflatex jay_tulshian.tex
```

Template: `resume.tex` is Jake Gutierrez's original LaTeX template.

Based off of [sb2nov/resume](https://github.com/sb2nov/resume/)

Use it on overleaf: [Jake's Resume](https://www.overleaf.com/latex/templates/jakes-resume/syzfjbzwjncs) (Not updated)

![Resume Preview](resume.png)
