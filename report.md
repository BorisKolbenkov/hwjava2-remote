# Отчёт о тестировании 
## Краткое описание
16.06.2021 было проведено тестирование Precision

В результате тестирования выявлены следующие дефекты:
 * [При выполнении кода появляется значение 0.899999999999999](https://user-images.githubusercontent.com/85697923/122271189-d61e2880-cee7-11eb-9d79-3feea160f6ef.png)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [Входные данные в Задаче №2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#задача-2---precision)

В качестве тестовых данных использовался код программы: 
```
 public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

* Тестирование работы кода программы:

  * Запустить установленную программу IntelliJ IDEA
  * В Project нажать Alt+Insert и выбрать Java Class
  * В поле окна New Java Class ввести Main
  * Скопировать код из тестовых данных
  * Нажать Ctrl+Shift+F10
  * Ожидаемый результат: значение 0,9


Тестирование производилось в следующем окружении:
* Windows 10 x64
* Java 11
* Git Bash 
* IntelliJ IDEA  