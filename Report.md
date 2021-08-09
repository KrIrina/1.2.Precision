# Отчёт о тестировании Precision

## Краткое описание

09.08.2021 - 09.08.2021 было проведено тестирование функциональности приложения Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [В переменную totalBonus записывается неверное значение](https://github.com/KrIrina/1.2.Precision/issues/1#issue-964325189)


## Описание процесса тестирования

В качестве тестовых данных использовались следующие данные:
* Код программы:


    public class Main {
      public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
      }
    }

Ожидаемый результат
* 0.9

Тестирование производилось в следующем окружении:
* OC Window 7 x64
* Java 11.0.12.