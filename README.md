# Разведочный анализ данных
Репозиторий предназначен для изучения курса «Разведочный анализ данных» 
## Описание задачи
Исходный датасет: [Abalone](https://github.com/aiedu-courses/stepik_eda_and_dev_tools/blob/main/datasets/abalone.csv)  
По параметрам размеров и массы, а также пола моллюска абалона требуется предсказывать количество колец (или же возраст особи).  
## Структура проекта
- EDA.ipynb — разведочный анализ
- data — каталог для датасетов
## Запуск
### venv
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 -m jupyterlab
```
### pipenv
```bash
pip install pipenv
pipenv install
pipenv shell
python3 -m jupyterlab
```