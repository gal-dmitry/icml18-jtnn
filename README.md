TASK_1

1. Форк оригинального репозитория: https://github.com/wengong-jin/icml18-jtnn/tree/master/molvae
2. Окружение chemprop, собранное по инструкции: https://github.com/chemprop/chemprop
3. Переменные окружения: export PYTHONPATH=${PYTHONPATH}:~/icml18-jtnn/:~/icml18-jtnn/jtnn/
4. Изменения в коде (закомментированные строчки), связаны с переводом в python3 и на CPU
5. Запуск претренированной модели для 10 молекул с помощью команды: 
python sample.py --nsample 10 --vocab ../data/zinc/vocab.txt --hidden 450 --depth 3 --latent 56 --model MPNVAE-h450-L56-d3-beta0.005/model.iter-4
6. В sample.py добавлена запись smiles-результатов в файл "10_molecules.csv" в папку "molvae"
7. Ноутбук с визуализацией сгенерированных молекул: "Visualise_10_molecules.ipynb" 
8. Сохраненные картинки - в папке "images"
9. screenshot.png - скриншот запуска генерации молекул
