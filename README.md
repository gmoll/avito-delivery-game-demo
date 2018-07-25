# avito-delivery

Код встраивания можно увидеть в файле *avito.html*. Вот пример:

    <div id="game-avito"
         style="width:100%;height:750px;"
         data-base="some_folder/"
    >
    </div>
    <link rel="stylesheet" type="text/css" href="some_folder/all.min.css"></script>
    <script src="another_folder/all.min.js"></script>

Параметр *data-base* — URL папки, в которой размещены изображения. Должен заканчиваться слешем.

Эта версия не подгружает библиотеку likely.js (подразумевается, что она уже доступна на странице).