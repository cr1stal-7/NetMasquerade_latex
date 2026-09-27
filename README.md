# NetMasquerade — доклад в LaTeX

## Сборка
Нужен **XeLaTeX** (или LuaLaTeX)
    latexmk main.tex          # или: xelatex main.tex  (дважды)

## Структура
- `main.tex` — преамбула и подключение слайдов
- `slides/` — по файлу на слайд
- `beamerthemeNetMasq.sty` — тема: цвета, шрифты, карточки, иконки
- `figs/` — рисунки статьи; `figs/icons/` — иконки
- `fonts/` — Carlito и PT Serif, лицензия OFL