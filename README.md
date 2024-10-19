# cdsh: Code Shield || Python Code Obfuscator

## Описание

Python Code Obfuscator - это инструмент для обфускации Python-кода, который искажает имена переменных, функций и строки, сохраняя при этом работоспособность оригинальной программы. Он предназначен для повышения безопасности кода, затрудняя его анализ и понимание третьими лицами.

## Функции

- **Обфускация имен**: Все имена переменных и функций заменяются на случайно сгенерированные имена.
- **Обфускация строк**: Все строки в коде кодируются с использованием Base64, что затрудняет их понимание.
- **Сохранение работоспособности**: Обфусцированный код сохраняет свою функциональность и корректно выводит необходимую информацию.

## Установка

1. Склонируйте репозиторий:

   ```bash
   git clone https://github.com/sl1dee36/cdsh-codeShield.git
   cd cdsh-codeShield
   ```

2. Убедитесь, что у вас установлен Python 3.8 или выше.

## Использование

Для обфускации Python-кода выполните следующую команду в терминале:

```bash
python obfuscator.py -o <output_file.py> -e <input_file.py>
```

### Пример:

```bash
python obfuscator.py -o obfuscated_example.py -e example.py
```

## Пример кода

Вот пример оригинального кода, который можно обфусцировать:

```python
import time

def example_function():
    for i in range(3):
        print(f'The number is: {i}')
        time.sleep(1)

example_function()
```

## Вклад

Если вы хотите внести свой вклад в проект, пожалуйста, создайте новый issue или отправьте pull request. Мы всегда рады помощи и предложениям!

## Лицензия

Этот проект лицензируется под MIT License. Подробности можно найти в файле [LICENSE](LICENSE).
