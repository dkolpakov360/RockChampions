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

Нужно создать новый массив наоборот, где имя свойства это достижение, а элементы в нем это имя чемпионов.

```
Everest: ["Vasya", "Masha"]
Mont Blanc: ["Vasya", "Alex",
New Hebrides: ["Kolya", "Alex"]
Pillar Rock: ["Vasya", "Alex"]
South Pole: ["Kolya", "Masha"]
```
