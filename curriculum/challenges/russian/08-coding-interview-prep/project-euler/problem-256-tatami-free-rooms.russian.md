---
id: 5900f46c1000cf542c50ff7e
challengeType: 5
title: 'Problem 256: Tatami-Free Rooms'
videoUrl: ''
localeTitle: 'Задача 256: Номера, свободные от татами'
---

## Description
<section id="description"> Татами - прямоугольные маты, используемые для полного покрытия пола комнаты, без перекрытия. <p> Предполагая, что единственный тип доступных татами имеет размеры 1 × 2, очевидно, что существуют некоторые ограничения для формы и размера комнат, которые могут быть покрыты. </p><p> Для этой проблемы мы рассматриваем только прямоугольные комнаты с целыми размерами a, b и даже размером s = a · b. Мы используем термин «размер», чтобы обозначить площадь поверхности пола комнаты, и - без потери общности - добавим условие a ≤ b. </p><p> При кладке татами необходимо соблюдать одно правило: не должно быть точек, где встречаются углы четырех разных матов. Например, рассмотрите два соглашения ниже для 4 × 4 комнаты: </p><p> Расположение слева приемлемо, тогда как справа нет: красный «X» посередине, отметит точку, в которой встречаются четыре татами. </p><p> Из-за этого правила некоторые комнаты с определенным размером не могут быть покрыты татами: мы называем их комнатами без татами. Далее, мы определяем T (s) как количество комнат без татами размером s. </p><p> Самая маленькая комната без татами имеет размер s = 70 и размеры 7 × 10. Все остальные комнаты размером s = 70 могут быть покрыты татами; они: 1 × 70, 2 × 35 и 5 × 14. Следовательно, T (70) = 1. </p><p> Аналогично, мы можем проверить, что T (1320) = 5, потому что имеется ровно 5 комнат без татами размером s = 1320: 20 × 66, 22 × 60, 24 × 55, 30 × 44 и 33 × 40. Действительно, s = 1320 - наименьший размер комнаты s, для которого T (s) = 5. </p><p> Найдите наименьший размер комнаты s, для которого T (s) = 200. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler256()</code> должен вернуть 85765680.
    testString: 'assert.strictEqual(euler256(), 85765680, "<code>euler256()</code> should return 85765680.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler256() {
  // Good luck!
  return true;
}

euler256();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
