# raiff_credit_scoring_project
Проект по кредитному скорингу Райф 2023

Кредитный скоринг

Ваша задача состоит в том, чтобы по различным характеристикам клиентов спрогнозировать целевую переменную - имел клиент просрочку 90 и более дней или нет (и если имел, то банк не будет выдавать кредит этому клиенту, а иначе будет). 

Ниже находится описание признаков клиентов.

Целевая переменная
SeriousDlqin2yrs: Клиент имел просрочку 90 и более дней
RevolvingUtilizationOfUnsecuredLines: Общий баланс средств (total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits).
age: Возраст заемщика
NumberOfTime30-59DaysPastDueNotWorse: Сколько раз за последние 2 года наблюдалась просрочка 30-59 дней.
DebtRatio: Ежемесячные расходы (платеж по долгам, алиментам, расходы на проживания) деленные на месячный доход.
MonthlyIncome: Ежемесячный доход.
NumberOfOpenCreditLinesAndLoans: Количество открытых кредитов (напрмер, автокредит или ипотека) и кредитных карт.
NumberOfTimes90DaysLate: Сколько раз наблюдалась просрочка (90 и более дней).
NumberRealEstateLoansOrLines: Количество кредиов (в том числе под залог жилья)
NumberOfTime60-89DaysPastDueNotWorse: Сколько раз за последние 2 года заемщик задержал платеж на 60-89 дней.
NumberOfDependents: Количество иждивенцев на попечении (супруги, дети и др).

Таблица находится в схеме public под названием credit_scoring. 
