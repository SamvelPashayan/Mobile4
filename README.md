<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ
РОССИЙСКОЙ ФЕДЕРАЦИИ
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center"> Институт естественных наук и техносферной безопасности <br> Кафедра информатики <br> Пашаян Самвел Алексанович </p>
<br><br><br>
<p align = "center">Лабораторная работа №4<br> «Отладка Android-приложений» <br> 01.03.02 Прикладная математика и информатика </p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right"> Научный руководитель <br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск <br> 2023г.</p>

***
# <p align = "center"> 1.Исследуем Layout Inspector </p>
Для диагностики проблем с файлами макетов и интерактивного анализа визуализации макета на экране можно воспользоваться инструментом Layout Inspector. Убедитесь в том, что GeoQuiz выполняется в эмуляторе, и нажмите кнопку Layout Inspector на левой панели окна Android Monitor. Далее вы сможете исследовать свойства своего макета, щелкая на элементах в представлении Layout Inspector.
***
## <p align = "center"> РЕШЕНИЕ (Получившийся результат) </p>
![](LAB4_1.png)

# <p align = "center">2.Profiler</p>
С помощью инструмента Profiler создаются подробные отчеты о том, как ваше приложение использует ресурсы Android-устройства, а именно процессор и память. Это полезно при оценке и настройке производительности вашего приложения. Для просмотра окна Profiler запустите приложение на подключенном Android устройстве или эмуляторе, в строке меню выберите команду View ⇒ Tool Windows ⇒ Profiler. В открывшемся окне Profiler отобразится временная шкала с показаниями по использованию сети, процессора, памяти и заряда аккумулятора. Щелкните по разделу, чтобы увидеть более подробную информацию об использовании этого ресурса вашим приложением. В режиме просмотра процессора нажмите кнопку Record, чтобы получить более подробную информацию об использовании процессора. После выполнения любых взаимодействий с приложением, которые вы хотите записать, нажмите кнопку Stop, чтобы остановить запись.
***
## <p align = "center"> РЕШЕНИЕ (Получившийся результат) </p>
![](LAB4_2.png)
![](LAB4_3.png)
![](LAB4_4.png)
![](LAB4_5.png)

## <p align = "center"> ВЫВОД </p>   
Итогом работы стало создание Android приложения, которое с помощью Layout Inspector исследует макет для диагностики проблем, а также воспользовались инструментов Profiler, чтобы узнать подробные отчеты о том, как приложение использует ресурсы Android-устройства, а именно процессор и память.Это позволяет сделать вывод, что цель данной лабораторной работы успешно достигнута.
***    