# DeepSeek-V3 Technical Report (Chinese Translation)

Chinese translation of the [DeepSeek-V3 technical report](https://arxiv.org/abs/2412.19437), typeset with LaTeX.

## Build

The document requires XeLaTeX (for `xeCJK` and custom fonts) and `latexmk`.

```bash
latexmk -xelatex main.tex
```

The FangZheng CJK fonts referenced in `main.tex` (`FZShuSong-Z01`, `FZHei-B01`, `FZKai-Z03`, `FZFangSong-Z02`) and `Times New Roman` must be installed and discoverable by `fontspec`.

## Structure

- `main.tex` — document entry point and preamble
- `content/` — section source files
- `tables/` — table definitions
- `figures/`, `logo/` — image assets
- `deepseek.cls` — document class (adapted from the original DeepSeek-V3 report)
- `main.bib` — bibliography

## License

Translation of the original DeepSeek-V3 technical report; refer to the original paper for licensing of the underlying work.
