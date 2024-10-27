# Project13
Простая графическая библиотека на C++ для Windows

<h1>class Window</h1>
v0.001<br>

Конструктор класса:
```cpp
Window(bool& isRun, int width = 500, int height = 700, int x_pos = 0, int y_pos = 0, const wchar_t* name = L"Project13")
```
Пример создания окна размером 700 на 500 пикселей и названием "app":
```cpp
Window wnd(IsRun, 700, 500, 20 ,20 , L"app");
```
Обязательные параметры:
- <code>bool& isRun</code> - принимает переменную и изменяет ее на <code>false</code>, если окно закрывается

Необязательные параметры:
- <code>int width</code> - ширина окна, по умолчанию 500 px
- <code>int height</code> - высота окна по умолчанию 700 px
- <code>int x_pos</code> - положение по x, по умолчанию 0 px
- <code>int y_pos</code> - положение по y, по умолчанию 0 px
- <code>const wchar_t* name</code> - название окна, по умолчанию "Project13"
