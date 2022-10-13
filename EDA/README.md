# Домашнее задание по EDA

Вам предлагается на выбор 2 датасета.
1. Police shootings
2. Autism_Data

С каким именно из них вы предпочтете работать, мне не принципиально. 
Ваша задача построить максимально адекватный разведочный анализ данных. 
Стройте графики, работайте с категориальными признаками, распределяйте значения по бинам, смотрите распределения чисел и признаков, стройте корреляции, генерите фичи, удаляйте те, которые не заслуживают внимания и тп.
После каждого из описанных вами наблюдей или преобразований, я хочу видеть отчет, осваивайте Markdown. В конце работы должны быть описаны выводы касаемо всего набора данных.
Списанные работы зачтены не будут.
Пишите аккуратно и понятно, представьте, что я ваш заказчик и не понимаю вообще о чем идет речь в ДС.

Краткое описание которое поможет вам начать работу с данными:


## 1. Police shootings
Контекст
В убийствах совершенных в США возникла горячая тема «Расизм».

Содержание
Датасет содержит основные данные о людях, такие как их имя, возраст, пол и раса. Наряду с этим, есть ли информация о стрельбе/убийстве, например, дата события и где это произошло, при каких обстоятельствах? Было ли нападение? Выявили ли какое-либо психическое заболевание? Была ли у полицейского камера/происшествие было записано? Подозреваемый скрылся? Кроме того, в столбце категории указан тип оружия, которым пользовался подозреваемый.


## 2. Autism_Data
Расстройство аутистического спектра (РАС) — это нарушение развития нервной системы, связанное со значительными затратами на здравоохранение, и ранняя диагностика может значительно сократить их. К сожалению, время ожидания диагноза РАС длительное, а процедуры неэффективны с точки зрения затрат. Экономические последствия аутизма и рост числа случаев РАС во всем мире указывают на острую необходимость в разработке легко реализуемых и эффективных методов скрининга. Таким образом, быстрый и доступный скрининг РАС неизбежен, чтобы помочь медицинским работникам и информировать людей о том, следует ли им проводить формальный клинический диагноз. Быстрый рост числа случаев РАС во всем мире требует наличия наборов данных, связанных с чертами поведения. Однако такие наборы данных встречаются редко, что затрудняет проведение тщательного анализа для повышения эффективности, чувствительности, специфичности и прогностической точности процесса скрининга РАС. В настоящее время доступны очень ограниченные наборы данных об аутизме, связанные с клиническими исследованиями или скринингом, и большинство из них имеют генетическую природу. Следовательно, мы предлагаем новый набор данных, связанный со скринингом взрослых на аутизм, который содержит 20 признаков, которые можно использовать для дальнейшего анализа, особенно для определения влиятельных аутичных черт и улучшения классификации случаев РАС. В этом наборе данных мы записываем десять поведенческих характеристик (AQ-10-Adult) плюс десять индивидуальных характеристик, которые доказали свою эффективность в выявлении случаев РАС среди контрольной группы в науке о поведении.
Age Number Age in years

Gender String Male or Female

Ethnicity String List of common ethnicities in text format

Born with jaundice Boolean (yes or no) Whether the case was born with jaundice

Family member with PDD Boolean (yes or no) Whether any immediate family member has a PDD

Who is completing the test String Parent, self, caregiver, medical staff, clinician ,etc.

Country of residence String List of countries in text format

Used the screening app before Boolean (yes or no) Whether the user has used a screening app

Screening Method Type Integer (0,1,2,3) The type of screening methods chosen based on age category (0=toddler, 1=child, 2= adolescent, 3= adult)

Question 1 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 2 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 3 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 4 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 5 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 6 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 7 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 8 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 9 Answer Binary (0, 1) The answer code of the question based on the screening method used

Question 10 Answer Binary (0, 1) The answer code of the question based on the screening method used

Screening Score Integer The final score obtained based on the scoring algorithm of the screening method used. This was computed in an automated manner.
