# [GithubICOAI](https://github.com/Kyiv2023/GithubICOAI)
Kickstarter/генератор посадкової сторінки для репозиторіїв на GitHub: спілкування з цим репозиторієм - запитувати його про код та діяльність людей, які в ньому беруть участь, якість коду за результатами статичних аналізаторів, ICO 


Це веб-сайт із використанням Github OAuth. Після входу користувач може вибрати репозиторій зі свого облікового запису.

Головна сторінка створюється на основі обраного репозиторію.

На головній сторінці є поле для електронної пошти та можливість придбати ERC20-токен, специфічний для обраного репозиторію. При покупці токенів вони мінтуються. 99% зібраних ETH перераховується на ETH-гаманець власника репозиторію, 1% зберігається на гаманці сервісу.

Головна сторінка також містить інтерфейс для спілкування з LLM (Language Model), яка має свідомість про проект, пов'язаний з репозиторієм GitHub. Сервіс підтримує наступні теми розмови:

- особливості, монетизація тощо - все, що згадується в документації репозиторію проекту на GitHub
- деталі реалізації - які бібліотеки та мови програмування використовуються, покриття тестами, звіти про статичний аналіз коду - все, що LLM може зібрати з вихідного коду
- активність на рівні комітів - кількість комітів, шаблони внесення внесків в репозиторій


It is a website with Github OAuth. After login in, user can select a repository from their account.


Landing page is created from this repository.

Landing page has email field and option to purchase repository-specific ERC20 token that is being minted on purchase. 99% of collected ETH is forwarded to repository owner's ETH wallet, 1% is being withhold to the wallet of the service

Landing page has an interface for chatting with project (github repo based)-aware LLM, including those topics:

 - features, monetization, etc - anything that is mentioned in the documentation in GitHub repo of the project
 - implementation details - what libraries, languages are used, test coverage, static code analysis reports - anything that LLM is able to gather from source code
 - commit level activity - number of the commiters, patterns of their contribution
