# Звіт з практичної роботи №11

****

**Виконав**  
**ПІБ**: Лук'янов Віктор Вячеславович  
**Група**: ІПЗ-2.03  

****

# Теоретична частина

Кольорова гармонія — це принцип підбору кольорів, які добре виглядають разом і створюють естетично приємне враження. Вона базується на взаємозв’язках кольорів на колірному колі, як-от контраст, подібність або баланс.

Типи кольорової гармонії:
- Analogous (аналогічна)
- Monochromatic (монохроматична)
- Triad (тріада)
- Complementary (комплементарна)
- Split Complementary (розділена комплементарна)
- Square (квадратна)
- Custom (власна побудова)

Колірні моделі RGB, HSB, LAB:
RGB - модель, що базується на суміщенні трьох світлових каналів: червоного (R), зеленого (G) і синього (B). Використовується на екранах, у веб-дизайні, цифрових зображеннях.

HSB - модель, яка представляє колір так, як його сприймає людина. Зручна для ручного підбору кольорів у дизайні та UI.

LAB - модель, створена для відображення кольору так, як його бачить людське око. Використовується в друці, фотографії, науковій обробці кольору.

Перевірка доступності через контрастність:
Контрастне співвідношення — це відношення яскравості (світлоти) між текстом і фоном, на якому він розміщений. Вимірюється як число від 1:1 (немає контрасту, наприклад білий на білому) до 21:1 (максимальний контраст — чорний на білому).

WCAG — це міжнародні рекомендації з веб-доступності. Вони визначають мінімальні допустимі рівні контрасту, щоб інформація була доступною для всіх користувачів.

Рівень AA:
Звичайний текст: мінімум 4.5:1
Великий текст: мінімум 3:1

Рівень AAA:
Звичайний текст: мінімум 7:1
Великий текст: мінімум 4.5:1

****

# Практична частина

## 1. Робота з колірним колесом (Color Wheel)

Базовий колір однаковий у всіх схем: #EACEC8

Analogous 

![](https://github.com/MarryBye/workshop_11/blob/main/images/Analogous.png?raw=true) 

Використовуються кольори, розташовані поруч на колірному колесі. Усі відтінки теплі: варіації рожевого, кремового та пісочного. Створює м’яке, гармонійне, спокійне враження. Така палітра часто використовується в косметиці, інтер'єрах для релаксації, сайтах з теплим настроєм.

Complementary

![](https://github.com/MarryBye/workshop_11/blob/main/images/Complementary.png?raw=true) 

Поєднуються кольори, що знаходяться навпроти один одного на колірному колесі. Протиставлення теплого рожевого #EACEC8 і холодного зеленого (#5C9681, #6B3B30 тощо). Яскравий контраст, динамічність, акцент на емоціях. Добре підходить для виділення елементів.

Monochromatic

![](https://github.com/MarryBye/workshop_11/blob/main/images/Monochromatic.png?raw=true) 

Варіації одного кольору з різною яскравістю і насиченістю. Усі кольори — похідні рожевого-бежевого. Витонченість, стриманість, професіоналізм. Часто використовується в елегантному дизайні та брендингу преміум-класу.

Split Complementary

![](https://github.com/MarryBye/workshop_11/blob/main/images/Split%20Complementary.png?raw=true) 

Обираються два кольори, сусідні до комплементарного. У даному випадку — зеленувато-блакитні та коричнево-червоні тони. Більш збалансована альтернатива до контрастної комплементарної схеми. Енергійна, але м’якіша — створює відчуття динаміки без візуального перевантаження.

Square

![](https://github.com/MarryBye/workshop_11/blob/main/images/Square.png?raw=true) 

Чотири кольори, рівномірно розподілені по колірному колу. Включає лавандовий, зелений, бежевий та коричневий. Гармонія різноманіття. Палітра виглядає яскраво та життєрадісно. Підходить для творчих, креативних рішень.

Triad 

![](https://github.com/MarryBye/workshop_11/blob/main/images/Triad.png?raw=true) 

Три кольори, що утворюють рівносторонній трикутник на колі. У нас — рожевий, синьо-фіолетовий та зелений. Баланс між контрастом і гармонією. Живий, енергійний, але не надто агресивний. Добре підходить для брендингу або UI-дизайну з виразними акцентами.

Custom

![](https://github.com/MarryBye/workshop_11/blob/main/images/Custom.png?raw=true) 

Вибрані кольори довільно, але з домінантою теплоти — червонувато-рожеві, фіолетові та рожеві відтінки. Індивідуальність і стиль. Емоційно насичена палітра.

## 2. Створення палітри зображенням (Extract Theme)

Базове зображення

![](https://github.com/MarryBye/workshop_11/blob/main/images/image_default.jpg?raw=true) 

Colorful палітра

![](https://github.com/MarryBye/workshop_11/blob/main/images/image_colorful.png?raw=true) 

Muted палітра

![](https://github.com/MarryBye/workshop_11/blob/main/images/image_muted.png?raw=true) 

Якщо це робочий або універсальний додаток - Muted краще, тому що: 
- приглушені кольори менш агресивні для очей;
- вони створюють спокійну, професійну атмосферу, що важливо для UI, особливо при тривалому використанні;
- висока читабельність і контраст між елементами, без візуального перевантаження;
- легко комбінуються з білим фоном, сірими елементами, іконками та текстом.

Якщо це гейміфікований чи дитячий застосунок — Colorful може використовуватись.

## 3. Створення градієнту на основі зображення (Extract Gradient)

![](https://github.com/MarryBye/workshop_11/blob/main/images/image_gradient.png?raw=true) 

Цей градієнт є нейтральним, з природним переходом кольорів. Спокій, безпека, надійність, тепло. Ідеальний фон для інтерфейсів, де контент повинен «дихати», а не змагатися з кольорами. 

## 4. Аналіз контрасту (Accessibility Tools)

Початкове зображення
![](https://github.com/MarryBye/workshop_11/blob/main/images/failed_accessibility.png?raw=true) 

З корекцією для рівня АА
![](https://github.com/MarryBye/workshop_11/blob/main/images/corrected_AA_accessibility.png?raw=true) 

З корекцією для рівня ААА
![](https://github.com/MarryBye/workshop_11/blob/main/images/corrected_AAA_accessibility.png?raw=true) 

Для перевірки Accessibility були обрані кольори Monochromatic схеми: #EACEC8 та #C09E96. Через те, що вони не підходили для маленького, великого тексту, а також іконок, була використана корекція на #64514D та #EACEC8. Коефіцієнт контрастності сильно збільшився, але коефіцієнт був лише 5.01:1, через що ці кольори підходили лише для рівню АА. Було виправлено на #413431 та #EACEC8 й коефіцієнт став 8.04:1 й повністю підходить для рівню ААА.

****

# Висновки

Muted, Analogous, Monochromatic + нейтральні градієнти — це ідеальні інструменти для створення зручного, естетичного і функціонального інтерфейсу. Вони дають змогу зберігати концентрацію, не втомлюють очі та не відволікають від контенту.