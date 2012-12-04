Pandoc command used to render pdf:

pandoc -f markdown -N --toc --template=./pandoc-preamble.tex -o P31U-7.0-change-note.pdf --variable=ref:GS-CN-P31U70 --include-after-body=lastpage.tex --variable=gitref:`git describe` --variable=frontimage:./img/board.png P31u-7.0-changenote.md

pandoc -f markdown -N --toc --template=./pandoc-preamble.tex --variable=ref:GS-DS-NM712D-1.0 --include-after-body=lastpage.tex --variable=gitref:`git describe` --variable=frontimage:./img/board.png --variable=subtitle:subtitle.tex -o datasheet.tex datasheet.md


pandoc -f markdown -N --toc --template=./pandoc-preamble.tex -o P31U-7.0-change-note.tex --variable=ref:GS-CN-P31U70 --include-after-body=lastpage.tex --variable=subtitle:subtitle.tex --variable=gitref:NA --variable=frontimage:./img/board.png P31u-7.0-changenote.md