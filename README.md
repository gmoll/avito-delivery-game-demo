# avito-delivery

Код встраивания можно увидеть в файле *avito.html*. Вот пример:

    <div id="game-avito"
         style="width:100%;height:750px;"
         data-base="some_folder/"
         data-share-url="https://tjournal.ru/avito/"
         data-share-title="Из Москвы в Калугу"
    >
    </div>
    <link rel="stylesheet" type="text/css" href="some_folder/all.min.css"></script>
    <script src="another_folder/all.min.js"></script>

Параметр *data-base* — URL папки, в которой размещены изображения. Должен заканчиваться слешем.

Параметр *data-share-url* задает начало ссылки для шера. В этом примере для игрока, набравшего 21 очко, шер будет производиться на адрес https://tjournal.ru/avito/21.

Параметр *data-share-title* — заголовок для шеров.

Эта версия не подгружает библиотеку likely.js (подразумевается, что она уже доступна на странице).