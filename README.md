# Ajustamento Básico IME

Aulas de Ajustamento Básico (Inverse Problems) ministradas para o 3º ano do Curso de Engenharia Cartográfica do Instituto Militar de Engenharia - Rio de Janeiro/RJ

<img src="media/imgs/AjustBasico.png">

## SUMÁRIO:

- [Aula 1](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/01_ajustamento_observacoes.ipynb): Visão geral sobre ajustamento, medidas, observações

- [Aula 2](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/02_minimos_quadrados.ipynb): O Método dos Mínimos Quadrados (MMQ)

- [Aula 3](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/03_classificacao_erros.ipynb): Incerteza, precisão, acurácia, erros e resíduos

- [Aula 4](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/04_erro_prop.ipynb): Propagação de erros das observações para o(s) modelo/parâmetros ajustado(s)

- [Aula 5](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/05_mmq_weighted.ipynb): MMQ com observações ponderadas

- [Aula 6](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/06_cond_sistemas.ipynb): Sistemas mal condicionados e como contorná-los

- [Aula 7](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/07_metodos.ipynb): Revisão MMQ - modelo paramétrico

- [Aula 8](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/08_metodo_condicionado.ipynb): Apresentação modelo condicionado

- [Aula 9](https://github.com/HumbertoDiego/AjustamentoBasicoIME/blob/main/09_metodo_combinado.ipynb): Apresentação modelo combinado

## REQUISITOS:

- [Python 3.12](https://www.python.org/downloads/)
- [Colab]
- [VS Code](https://code.visualstudio.com/) e [Extensão Jupyter do VS Code](https://marketplace.visualstudio.com/search?term=jupyter&target=VSCode&category=All%20categories&sortBy=Relevance)

No Windows PowerShell, macOS e Linux (Colab):

```powershell
pip install -r requirements.txt
```

<!--
git pull ajustamento main
git add * ; git commit -m "aula update"; git push ajustamento main
jupyter nbconvert --to slides 05_cond_sistemas.ipynb --TagRemovePreprocessor.remove_input_tags="hide_input" --SlidesExporter.reveal_scroll=True --post serve

reset
git init
git remote add ajustamento https://github.com/HumbertoDiego/AjustamentoBasicoIME
git add * ; git commit -m "aula update"; git push ajustamento main --force
-->
