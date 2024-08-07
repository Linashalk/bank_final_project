# Анализ оттока клиентов банка "Метанпром"
Выпускной проект в Яндекс Практикум.

В нашем распоряжении датасет, который содержит данные о клиентах банка «Метанпром». Банк располагается в Ярославле и областных городах: Ростов Великий и Рыбинск.

**Цель исследования** - проанализировать клиентов регионального банка и выделить сегменты клиентов, которые склонны уходить из банка.

**Стек:**
Pandas, numpy, seaborn, matplotlib, scipy

**Итоги исследования:**

Мной был проведен обзор и предобработка данных, исследовательский анализ данных, созданы вспомогательные таблицы, графики и визуализации, созданы фоновые картограммы (хороплет) и карты с кластерами, проведена проверка статистических гипотез, сегментация пользователей, сделаны выводы, подготовлена презентация.

В ходе исследовательского анализа данных я нашла признаки, влияющие на отток клиентов, и получила портреты отточного клиента действующего клиента. В результате проверки гипотез я пришла к выводу, что средние балансы отточных и действующих клиентов не являюся равными. Также клиенты, попавшие в отток, имеют достаточно высокие суммы на счете, не владеют кредитными картами, являются достаточно активными клиентами и пользуются более, чем двумя продуктами банка. То есть, это достаточно обеспеченные и состоятельные люди.

Мной были выделены 3 сегмента отточных клиентов:
- Сегмент 3 с активными клиентами в возрасте 25-61 год, у которых 2 и более продуктов банка и нет кредитных карт. Уровень оттока - 45.4%.
- Сегмент 1 с активными клиентами, у которых 3 и более объектов в собственности. Уровень оттока - 36.5%.
- Сегмент 2 с клиентами, обслуживающимися в Ярославле, у которых 2 и более продуктов банка. Уровень оттока - 25.6%.

Также были даны рекомендации для уменьшения оттока клиентов.
