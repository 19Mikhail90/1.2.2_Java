# Отчёт о тестировании 

## Precision

*12.08.2020* - *12.08.2020* было проведено ручное тестирование, приложения Precision.

На тестирование затрачено: <2 часа>

В результате тестирования выявлены следующие дефекты:

[Бонус (totalBonus) рассчитывается неправильно в бонусной системе при сложении regularBonus и specialBonus](https://github.com/19Mikhail90/1.2.2_Java/issues/1#issue-966946249)
## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* <->

*Примечание\*: не указывайте артефакты "для галочки". Если вы сюда напишите **тест-план**, то мы попросим вас его показать (а если не покажете - то отправим работу на доработку). Пишите только то, что реально существует и требуется в задании.*

В качестве тестовых данных использовались данные [Нетология. Задание 1.2.2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming) 

``` javascript
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

```

##Тестирование производилось в следующем окружении:
* Windows 10 Pro  64-разрядная операционная система
* Java 11.0.12
* процессор Intel(R) Core(TM) i5-10300H

   

   