# Task 3: Реализация класса `GuessTheNumber`

**Описание**: Реализовать класс `GuessTheNumber`, который будет связывать классы `GameLogic` и `GameUI` для проведения игры.

**Свойства**:
- `logic`: экземпляр класса `GameLogic`, который будет отвечать за логику игры.
- `ui`: экземпляр класса `GameUI`, который будет отвечать за взаимодействие с пользователем.

**Методы**:
- `start_game()`: главный метод игры, который будет генерировать число, принимать догадки пользователя и выводить результаты.

**Цель**: Обеспечить основной игровой процесс, связывая логику и интерфейс.

**Критерии выполнения**:
- Метод `start_game()` должен запускать игру, генерировать число, проверять догадки и выводить сообщения в зависимости от результата.
- Если пользователь угадывает число, должно быть выведено сообщение о победе. Если количество попыток исчерпано, должно быть выведено сообщение о проигрыше.
