# Покаратели гор

Есть список чемпионов champions в виде массива, где первый элемент это имя, а следующие это достижения.

```
let champions = [  
    ["Vasya", "Everest", "Mont Blanc", "Pillar Rock"],  
    ["Kolya", "South Pole", "New Hebrides"],  
    ["Masha", "Everest", "South Pole"],
    ["Alex", "New Hebrides", "Mont Blanc", "Pillar Rock"],  
];
```

Нужно создать новый массив наоборот, где каждый индекс это достажения, а элементы в нем это имя чемпионов.

```
Everest:  ["Vasya", "Masha"]
Mont Blanc:  ["Vasya", "Alex",
New Hebrides: (2) ["Kolya", "Alex"]
Pillar Rock: (2) ["Vasya", "Alex"]
South Pole: (2) ["Kolya", "Masha"]
```
