# E-commerce Sales Analysis (SQL, Python, Tableau)

This is a complete analytical portfolio project that covers the entire data workflow: from extraction (SQL) and analysis (Python) to creating an interactive dashboard (Tableau).

##  Interactive Dashboard

The main result of the project is an interactive dashboard published on Tableau Public.

### [➡️ Click here to view the dashboard](https://public.tableau.com/views/PortfolioProjectsalesAnalysis/SalesAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

##  Project Goal
To demonstrate skills in extracting data from a database (Google BigQuery), conducting exploratory and statistical analysis in Python, and visualizing the results in Tableau.

##  Tools
* **SQL** (in Google BigQuery) for data extraction and joining.
* **Python** for in-depth analysis, statistics, and visualization.
* **Python Libraries:** `pandas` (data manipulation), `matplotlib` / `seaborn` (visualization), `scipy.stats` (statistical tests).
* **Tableau Public** for creating the final interactive dashboard.

---

##  Key Conclusions and Insights

Based on a comprehensive data analysis (SQL, Python) and statistical tests (Pearson, Mann-Whitney, ANOVA), we can build a clear business profile and identify key insights.

### 1. Sales are Entirely Dependent on Seasonality

This is the **most important conclusion** of the entire analysis. Sales dynamics are not stable but are completely determined by two events:

* **Peak 1:** **"Black Friday" / "Cyber Monday"** (late November).
* **Peak 2:** **Christmas Sale** (late December).

Our correlation analysis confirmed this: sales across **all** continents, **all** device types, and through **all** traffic channels show a **very strong positive correlation** (most **r > 0.75-0.98**). This means they do not move independently; they all move **in sync**, reacting to the same global holiday events.

---

### 2. A Clear "Golden Segment" Exists

We can precisely describe the most valuable customer:

* **Where? (Geography):** **USA**. This market dominates so much that it generates more revenue than India and Canada combined. Buying preferences in the US (Top 10 categories) **dictate** global trends.
* **From where? (Channel):** **Search Engines**. **'Organic Search'** (35.76%) and **'Paid Search'** (26.62%) together bring in over **62%** of all revenue.
* **How? (Platform):** **Desktop**. It accounts for **59%** of all revenue, making it the most important platform.

---

### 3. What Are They Buying? (Products)

* **The "Big Three"**: Most of the revenue comes from three categories: **"Sofas & armchairs"** (8.3M), **"Chairs"** (6.1M), and **"Beds"** (4.9M).

---

### 4. Key Statistical Insights

* **The "Most Efficient" Channel Isn't the Biggest:** Although 'Organic Search' brings in the most *money*, our conversion rate (CR) analysis showed that **'Social Search'** is the **most effective** channel at converting sessions into purchases (**CR 9.73%**). All other channels show an almost identical CR (≈9.58%).

* **Registration Does Not Affect Average Order Value:** Using the **Mann-Whitney U test**, we proved that there is **no statistically significant difference** (P-value = 0.27) in the *individual purchase amount* (check) between registered (1) and unregistered (0) users. Although registered users buy *more often*, their average check is the same.

* **Platform Does Not Affect Average Order Value:** We refuted the hypothesis that Apple users spend more. The average check is practically **identical** across all operating systems (Android, Windows, iOS, Mac) and fluctuates within a narrow range of 930-980.

---

###  Final Recommendation

Marketing efforts should be maximally concentrated on the **US market** during **seasonal peaks** (November-December), with a special emphasis on promoting the **"Big Three" products** (sofas, chairs, beds) through **Desktop Search** channels (Organic and Paid).

---
---


# Аналіз продажів E-commerce (SQL, Python, Tableau)

Це повний аналітичний проект для портфоліо, який охоплює весь цикл роботи з даними: від вивантаження (SQL) та аналізу (Python) до створення інтерактивного дашборду (Tableau).

##  Інтерактивний Дашборд

Найголовніший результат проекту — інтерактивний дашборд, опублікований на Tableau Public.

### [➡️ Натисніть тут, щоб переглянути дашборд](https://public.tableau.com/views/PortfolioProjectsalesAnalysis/SalesAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

##  Мета проекту
Продемонструвати навички вивантаження даних з бази даних (Google BigQuery), проведення розвідувального та статистичного аналізу в Python та візуалізації результатів у Tableau.

##  Інструменти
* **SQL** (в Google BigQuery) для вивантаження та об'єднання даних.
* **Python** для глибокого аналізу, статистики та візуалізації.
* **Бібліотеки Python:** `pandas` (маніпуляція даними), `matplotlib` / `seaborn` (візуалізація), `scipy.stats` (статистичні тести).
* **Tableau Public** для створення фінального інтерактивного дашборду.

---

##  Ключові Висновки та Інсайти

На основі комплексного аналізу даних (SQL, Python) та статистичних тестів (Pearson, Mann-Whitney, ANOVA) ми можемо скласти чіткий портрет бізнесу та виявити ключові інсайти.

### 1. Продажі повністю залежать від Сезонності

Це **найголовніший висновок** усього аналізу. Динаміка продажів не є стабільною, а повністю визначається двома подіями:

* **Пік 1:** **"Чорна п'ятниця" / "Кіберпонеділок"** (кінець листопада).
* **Пік 2:** **Різдвяний розпродаж** (кінець грудня).

Наш кореляційний аналіз підтвердив це: продажі на **всіх** континентах, **всіх** типах девайсів та через **всі** канали трафіку мають **дуже сильну позитивну кореляцію** (більшість **r > 0.75-0.98**). Це означає, що вони не рухаються незалежно; вони всі рухаються **синхронно**, реагуючи на ті самі глобальні святкові події.

---

### 2. Існує чіткий "Золотий сегмент"

Ми можемо точно описати найціннішого клієнта:

* **Де? (Географія):** **США**. Цей ринок домінує настільки, що генерує більше доходу, ніж Індія та Канада разом узяті. Купівельні переваги в США (Топ-10 категорій) **диктують** загальносвітові тренди.
* **Звідки? (Канал):** **Пошукові системи**. **'Organic Search'** (35.76%) та **'Paid Search'** (26.62%) разом приносять понад **62%** усього доходу.
* **Як? (Платформа):** **Desktop**. На нього припадає **59%** усього доходу, що робить його найважливішою платформою.

---

### 3. Що купують? (Продукти)

* **"Велика трійка"**: Більшість доходу приносять три категорії: **"Sofas & armchairs"** (8.3 млн), **"Chairs"** (6.1 млн) та **"Beds"** (4.9 млн).

---

### 4. Ключові статистичні інсайти

* **"Найефективніший" канал – не найбільший:** Хоча 'Organic Search' приносить найбільше *грошей*, наш аналіз конверсії (CR) показав, що **'Social Search'** є **найефективнішим** каналом у перетворенні сесій на покупки (**CR 9.73%**). Усі інші канали демонструють практично однаковий CR (≈9.58%).

* **Реєстрація не впливає на середній чек:** За допомогою **тесту Манна-Вітні** ми довели, що **немає статистично значущої різниці** (P-value = 0.27) у *сумі індивідуальної покупки* (чеку) між зареєстрованими (1) та незареєстрованими (0) користувачами. Хоча зареєстровані купують *частіше*, їхній середній чек такий самий.

* **Платформа не впливає на середній чек:** Ми спростували гіпотезу, що користувачі Apple витрачають більше. Середній чек є практично **однаковим** для всіх операційних систем (Android, Windows, iOS, Mac) і коливається в вузькому діапазоні 930-980.

---

###  Підсумкова рекомендація

Маркетингові зусилля мають бути максимально сконцентровані на **ринку США** під час **сезонних піків** (листопад-грудень), з особливим акцентом на просуванні **"великої трійки" товарів** (дивани, крісла, ліжка) через канали **Desktop Search** (Organic та Paid).
