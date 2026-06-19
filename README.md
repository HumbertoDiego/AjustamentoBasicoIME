# Ajustamento Básico IME

Aulas de Ajustamento Básico (Inverse Problems) ministradas para o 3ª ano do Curso de Engenharia Cartográfica do Instituto Militar de Engenharia - Rio de Janeiro/RJ

## SUMÁRIO:

- [Semana 1](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/UD_I_e_II.ipynb): Medidas, observações, incerteza, precisão, acurácia, método dos mínimos quadrados (MMQ), erros e resíduos.

- [Semana 2](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/UD_III.ipynb): Propagação de erros das observações para o(s) modelo/parâmetros ajustado(s)

- [Semana 3](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/UD_IV.ipynb): Sistemas mal condicionados e como contorná-los

- [Semana 4](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/UD_V.ipynb): MMQ com observações ponderadas

- [Semana 5](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/UD_VI_parte_1.ipynb): Aprofundamento no MMQ - modelo paramétrico

- [Semana 6](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/UD_VI_parte_2.ipynb): Aprofundamento no MMQ - modelo condicionado

- [Semana 7](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/UD_VI_parte_3.ipynb): Aprofundamento no MMQ - modelo combinado

## REQUISITOS:

- [Python 3.12](https://www.python.org/downloads/)
- [Colab]
- [VS Code](https://code.visualstudio.com/)
- [Extensão Jupyter do VS Code](https://marketplace.visualstudio.com/search?term=jupyter&target=VSCode&category=All%20categories&sortBy=Relevance)

No Windows PowerShell, macOS e Linux (Colab):

```powershell
pip install -r requirements.txt
```




<!--
git add * ; git commit -m "aula update"; git push ajustamento main
jupyter nbconvert --to slides Prospecção.ipynb --TagRemovePreprocessor.remove_input_tags="hide_input" --SlidesExporter.reveal_scroll=True --post serve
jupyter nbconvert --to slides PreProcessamento.ipynb --TagRemovePreprocessor.remove_input_tags="hide_input" --SlidesExporter.reveal_scroll=True --post serve
jupyter nbconvert --to slides Mineração.ipynb --TagRemovePreprocessor.remove_input_tags="hide_input" --SlidesExporter.reveal_scroll=True --post serve

reset
git init
git remote add ajustamento https://github.com/HumbertoDiego/AjustamentoBasicoIME
git add * ; git commit -m "aula update"; git push ajustamento main --force
-->
