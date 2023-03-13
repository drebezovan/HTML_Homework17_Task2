<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Запись на курсы_post</title>
</head>

<body>
<h3>Запись на курсы</h3>
<hr>
<form action="/my-handling-form-page" method="post">
    <p>
        <label for="name">Имя:</label><br>
        <input type="text" size="13" id="name" name="user_name">
    </p>

    <p>
        Язык программирования:<br>
        <input type="radio" name="language" id="lang_1" value="cpp">
        <label for="lang_1">C++</label><br>
        <input type="radio" name="language" id="lang_2" value="php">
        <label for="lang_2">PHP</label><br>
        <input type="radio" name="language" id="lang_3" value="python">
        <label for="lang_3">Python</label>
    </p>

    <p>
        <label for="msg">Дополнительная информация:</label><br>
        <textarea rows="4" cols="35" style="font-family: serif " id="msg" name="user_message"></textarea>
    </p>

    <p>
        <label for="secret">Секретное слово:</label><br>
        <input type="password" size="14" style="font-family: serif" id="secret" name="user_secret">
    </p>

    <p class="button">
        <button type="submit">Отправить</button>
        <button type="reset">Очистить</button>
    </p>

</form>
<hr>
</body>
</html>
