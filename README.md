# Пример Байесовского анализа
В этом репозитории содержится пример использования библиотеки PyMC3 для определения свободных парамметров модели при анализе данных с использованием Байесовского подхода.
Файл [bayes_tutorial.def](bayes_tutorial.def) содержит рецепт для создания контейнера [Singularity](https://sylabs.io/singularity/) со всеми библиотеками, необходимыми для запуска примера.

Чтобы собрать обораз нужно выполнить в терминале
```bash
singularity build -f bayes.sif bayes_tutorial.def
```
А затем запустить Jupyter lab командой
```bash
./bayes.sif
```
