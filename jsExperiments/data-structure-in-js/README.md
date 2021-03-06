# Data structures

**Структура данных** - процесс организации вещей. Используются для упрощения жизни.

## Стек

Последовательный порядок стека обычно описывается как стопка тарелок в кафетерии. Когда тарелка добавляется - стопка сохраняет порядок, который существовал до этого. Каждый раз, когда мы добавляем новую тарелку, она подвигает нижнюю часть стопки и одновременно становится верхней тарелкой.

Этот процесс складывания тарелок сохраняет последовательный порядок, когда каждая тарелка добавляется в стопку. Снятие тарелки из стопки также не нарушит последовательность всех тарелок. Если тарелка снимается сверху стека, каждая тарелка в стопке по-прежнему будет сохранять тот же порядок в стопке.

В качестве более технологичного примера стека можно привести операцию "Отменить" (Undo) в текстовом редакторе. Каждый раз, когда текст вводится в текстовый редактор, он помещается в стек. Самое первое изменение текста представляет собой дно стека; самое последнее - вершину. Если пользователь хочет отменить самое последнее изменение, удаляется верх стека. Этот процесс может повторяться до тех пор, пока не останется ни одного изменения.

### Операции стека

Так как теперь у нас есть концептуальная модель стека, давайте определим две операции стека:

*push(data)* - добавляет данные;
*pop()* - удаляет последние добавленные данные.