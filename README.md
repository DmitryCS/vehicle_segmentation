Перейдя по ссылке и нажав "File" -> "Save a copy in Drive", вы сохраните Jupyter-блокнот к себе на Google-диск.<br>
После сохранения у вас появится кнопка "Open in new tab", нажав на которую вы перейдете на свою копию этого блокнота.<br>
Теперь возможен запуск приложения, посредством нажатия "Runtrime" -> "Run All", запустится выполнение всего кода, который создан с целью возможности запуска приложения любым пользователем без необходимости какой-либо настройки или скачивания репозитория.<br>
**Код использует выбранную модель нейронной сети и заранее обученные на ней веса для сегментации и классификации автотранспорта на выбранном пользователем видео**
https://colab.research.google.com/drive/12LGHDU1YTecfCQabOBYRYDA_uomW2EBh?usp=sharing
<br> Ниже представлен результат работы блокнота, а именно отображение сжатого (необходиость, Colab не может отобразить файлы большого размера) видео в клетке блокнота. Раскомментировав 2 последние строчки вы сможете скачать несжатый видеофайл себе на компьютер.
![Снимок](https://user-images.githubusercontent.com/46371199/84032891-74acab00-a9b1-11ea-80d9-f7c7a7dce1db.PNG)
<br> В файле "Краткое обучение.ipynb" представлено дообучение модели на собственном наборе данных (982 изображения с перекрестка).
