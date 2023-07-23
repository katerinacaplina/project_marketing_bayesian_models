# project_marketing_bayesian_models
Estimation the impact of marketing activities on sales.

Media mix models (MMMs) are statistical models used to measure the effectiveness of advertising spend. 

MMMs use aggregate historical time series data to model sales outcomes over time, as a function of advertising variables, other marketing variables, and control variables like weather, seasonality, and market competition. 

MMMs attempt to answer causal questions for the advertiser. For example: 

1) What was my ROAS on TV last year?

2) What would my sales be if more or less money were spent next year?

3) How should my media budgets be allocated to maximize sales? 

Typically though, MMMs are regression models based on a limited amount of aggregated observational data and such models produce correlational, not causal results. It is only under certain narrow conditions that these estimates can be considered causal.

Multi-Touch Attribution vs. Marketing Mix Model (What's the Difference)
Marketing Mix Model (MMM) tells you what percentage of your marketing budget to allot into each specific channel, while Multi-Touch Attribution tells you how to allocate within those particular channels at the granular level.

<b>Simple regression vs Bayesian Methods for Media Mix Modeling</b>

A common approach is to have the media variables enter in the model additively. 

The data quantity is often limited. A typical MMM dataset, consisting of three years of weekly data is only 156 data points. 

A rule-of-thumb for a minimum number of data points for a stable linear regression are 7-10 data points per parameter, of which typical MMMs fall short.

When fitting a linear regression model, highly correlated input variables can lead to coefficient estimates with high variance. This in turn, can lead to bad attribution of sales to the ad channel.

Benefits of the Bayesian approach include:
• Ability to use informative priors for the parameters, where the informative priors can come
from a variety of sources
• Ability to handle complicated models 
• Ability to report on both parameter and model uncertainty
• Ability to propagate uncertainty to optimization statements






# RUS

Оценка влияния маркетинговых мероприятий на продажи.

Модели медиа-микса (МММ) — это статистические модели, используемые для измерения эффективности рекламных расходов.

МММ используют совокупные исторические данные временных рядов для моделирования результатов продаж с течением времени в зависимости от рекламных переменных, других маркетинговых переменных и контрольных переменных как погода, сезонность и рыночная конкуренция.

МММ пытаются ответить на причинно-следственные вопросы для рекламодателя. Например:

1) Каков был мой ROAS на ТВ в прошлом году?
2) Какими были бы мои продажи, если бы в следующем году было потрачено больше или меньше денег?
3) Как должны быть распределены мои медиа-бюджеты, чтобы максимизировать продажи?

Однако, как правило, МММ модели регрессии, основанные на ограниченном количестве агрегированных данных наблюдений, и такие модели дают корреляционные, а не причинно-следственные результаты. Только при определенных узких условиях эти оценки можно считать причинными.

Мультитач-атрибуция в сравнении с моделью маркетинг-микс (в чем разница)

Модель комплекса маркетинга (MMM) сообщает вам, какой процент вашего маркетингового бюджета следует выделить на каждый конкретный канал, в то время как атрибуция с несколькими касаниями показывает вам, как распределять ресурсы внутри этих конкретных каналов на детальном уровне.

<b>Simple regression vs Bayesian Methods for Media Mix Modeling</b>

Обычный подход заключается в том, чтобы ввести медиа-переменные в модель аддитивно.

Количество данных часто ограничено. Типичный набор данных MMM, состоящий из еженедельных данные за три года, составляют всего 156 точек данных.

Эмпирическое правило для минимальное количество точек данных для стабильной линейной регрессии составляет 7-10 точек данных на параметр, из которых типичные МММ не дотягивают.

При подборе модели линейной регрессии сильно коррелированные входные переменные могут привести к коэффициенту оценки с высокой дисперсией. Это, в свою очередь, может привести к неправильной атрибуции продаж рекламному каналу.

Преимущества байесовского подхода включают в себя:
• Возможность использовать информативные априорные значения для параметров, где информативные априорные значения могут поступать
из различных источников.
• Способность работать со сложными моделями
• Возможность сообщать как о параметрах, так и о неопределенности модели
• Возможность распространения неопределенности на оптимизационные утверждения

