# Отчёт о тестировании приложения бонусной системы для клиентов Precision

## Краткое описание

08.11.2020 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 30 минут.

В результате тестирования выявлен следующий дефект:
1. [Неправильно начисляется дополнительный бонус новым клиентам](https://github.com/Tatiana43/hw-2.2/issues/1)

В качестве тестовых данных использовался следующий код:
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

Тестирование производилось в следующем окружении:
* ОС Windows 10 x64
* OpenJDK 11.0.9
* IntelliJ IDEA Version 2020.2.3
