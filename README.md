# Практическое занятие
1. Установить [sbt](https://www.scala-sbt.org/download.html)
2. Создать проект командой `sbt new scala/scala-seed.g8`
3. В файле `build.sbt` добавить зависимость [better-files](https://github.com/pathikrit/better-files)
4. Добавить зависимость [scopt](https://github.com/scopt/scopt)
4. Написать программу которая принимает на вход один аргумент - путь до файла. Читает содержимое файла в котором есть числа и складывает их между собой
5. Результат вычисления записывает в файл `output.txt` в директории рядом с файлом
