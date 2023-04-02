# Welcome to the FlexAnimations
 
Программа для генерации 2д анимации, реагирующей на частоту и громкость звука, меняющей цвет и форму по установленным пользователем правилам.

Является частью оверлея: окном/контейнером, накладываемым на основной фон. Все параметры анимации и её окна/контейнера конфигурируемые:
– цвет анимации;
– фигуры, используемые в анимации;
– цвет фона окна/контейнера;
– режим анимации (параметры, по которым будет меняться цвет или форма);
– размер окна/контейнера;

Есть возможность включить/выключить анимацию. В выключенном состоянии анимация прекращает показ, останавливается на последнем кадре, который в течение определённого количества времени меняет свою прозрачность до нуля.  

Во включённом состоянии при проигрывании любого звука анимация реагирует и меняет свою форму и цвет, т.е. проигрывается. При завершении проигрывания анимация прекращает показ, останавливается на последнем кадре, который в течение определённого количества времени меняет свою прозрачность до нуля. При начале проигрывания прозрачность ставится на 100%, анимация вновь начинает работу.

### Стиль написания кода - under_score

### Подход к разработке  - Scrum -- "Select (PDD — Panic Driven Development)".

Разработка происходит в циклах по 2 недели. В начале спринта происходит планирование задач на спринт, определение приоритетных задач. В середине спринта небольшое обсуждение промежуточных итогов спринта, определение задач, которым необходимо уделить дополнительное внимание.

Таск менеджер Trello https://trello.com/b/B6NQIt8N/командный-проект.

Проект бьется на две части, gui и анимация.

Постоянных ролей нет.

## Коммуникация
Discord, Telegram

## Технологии
- Python
> GUI
- Tkinter
> Animations
- Arcade 
> Physics
- pymunk
> Sound
- scipy

![image](https://user-images.githubusercontent.com/54447582/226207957-d69ea2ea-e5d7-4a3d-80de-026f2af63b53.png)

#### Two dynamic objects 
![image](https://user-images.githubusercontent.com/54447582/229371406-58eabd46-c76b-4183-82df-75f0ceac74ed.png)

### Kinematic and dynamic
![image](https://user-images.githubusercontent.com/54447582/229371428-ed8f1a47-b2ee-4d6d-bbdd-4f261cf08641.png)
