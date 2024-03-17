# On English 
**Learned or practiced while doing project**
- Use the library to build dynamic graphs Plotly
- Conducted one-hot encoding via sklearn MLB
- Preprocess data in heavily polluted columns like "production_country"

**Reference**

This is my second project during my studies at Yandex Workshop, their quality will increase as I study.

**Introduction**

  Most often, the first film in history is called “The Arrival of a Train at La Ciotat Station” by the brothers Auguste and Louis Lumière. This 48-second silent black and white film was filmed in 1895 at the La Ciotat train station near Marseille. Since then, cinema has become a powerful medium of mass media, art and entertainment. But we have another film planned - data analysis and anecdote.
> Folk signs:<br />
>If birds fly low, it means they are chickens.<br />
> If the film ends unclearly, then it is an advertisement.

**Purpose of the study**

Study the Russian film distribution market and identify current trends; in addition, you need to find out whether government support somehow affects the film’s ratings

**Data**

The data set contains information on distribution certificates, box office receipts and government support for films, as well as information from the KinoPoisk website.

-mkrf_shows.csv — data on distribution in Russian cinemas.
-mkrf_movies.csv — data about rental certificates.

**Description of variables in the data**
Table shows
- `box_office` - box office receipts
- `puNumber` - rental certificate number*

Movies table
- `puNumber` - rental certificate number*
- `title` - The title of the film. This is how the film is identified and promoted to the public.
- `show_start_date` - The date the film was first shown in theaters or released to the public. This may indicate its relevance in the market.
- `type` - Film category: feature, popular science, documentary, etc. Gives an idea of the content of the film and the target audience.,
- `film_studio` - The name of the studio that made the film. This can indicate the quality of the film and its budget.
- `production_country` - Country of production of the film. May be influenced by its style, language and cultural context.
- `director` - The director of a film, a person whose vision and style of work can significantly influence the final product.
- `producer` - The producer of the film, the person responsible for the financial and administrative aspects of the production.
- `age_restriction` - The age restriction of a film may affect its audience and theme.
- `refundable_support` - The volume of refundable state support funds.
- `nonrefundable_support` - The volume of non-refundable state support funds.
- `budget` - The total budget of the film, including all production costs.
- `financing_source` - Source of government funding.
- `ratings` - Rating of the film on KinoPoisk.
- `genres` - Film genres.

*Film distribution certificate is a document giving the right to rent (demonstrate) a film on the territory of the Russian Federation, as well as to reproduce and distribute it, including via cable or broadcast channels.

(Text above created automatically. Although my English level is B1+ - B2, I use autotranslate to speed up my work.)

# На русском
**В процессе выполнения научился или попрактиковался**
- Использовать библиотеку для построения динамических графиков Plotly
- Провел one-hot encoding через sklearn MLB
- Предобрабатывать данные в сильно загрязненных столбцах вроде "production_country"

**Справка**

Это мой второй проект за время обучения в Яндекс Практикуме, по ходу обучения их качество будет расти

**Введение**

 Чаще всего первым фильмом в истории называют «Прибытие поезда на вокзал Ла-Сьота́» братьев Огюста и Луи Люмьер. Этот 48-секундный немой черно-белый фильм был снят в 1895 году на вокзале города Ла-Сьота под Марселем. С того момента кино превратилось в мощнейшее средство массовой информации, искусства и развлечения. Но у нас в планах другой фильм - анализ данных и анекдот.
> Народные приметы:<br />
>  Если птицы летают низко, значит, это куры.<br />
>  Если фильм закончился непонятно, значит, это реклама.

**Цель исследования**

Изучить рынок российского кинопроката и выявить текущие тренды, кроме того необходимо узнать, влияет ли как-то государственная поддержка на рейтинги фильма

**Данные** 

Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.

-mkrf_shows.csv — данные о прокате в российских кинотеатрах.
-mkrf_movies.csv — данные о прокатных удостоверениях.

**Описание переменных в данных**
Таблица shows
- `box_office` - кассовые сборы
- `puNumber` - номер прокатного удостоверения*

Таблица movies
- `puNumber` - номер прокатного удостоверения*
- `title` - Название фильма. Так фильм идентифицируется и продвигается среди публики.
- `show_start_date` - Дата первого показа фильма в кинотеатрах или его выпуска для публики. Это может указывать его актуальность на рынке.
- `type` - Категория фильма: художественный, научно-популярный, документальный и т.д. Дает представление о содержании фильма и целевой аудитории.,
- `film_studio` - Название студии, которая сняла фильм. Это может указывать на качество фильма и его бюджет.
- `production_country` - Страна производства фильма. Может влиять на его стиль, язык и культурный контекст.
- `director` - Режиссер фильма, человек чье видение и стиль работы могут значительно повлиять на конечный продукт.
- `producer` - Продюсер фильма, человек отвечающий за финансовую и административную стороны производства.
- `age_restriction` - Возрастное ограничение фильма, может влиять на его аудиторию и тему.
- `refundable_support` - Объём возвратных средств государственной поддержки.
- `nonrefundable_support` - Объём невозвратных средств государственной поддержки.
- `budget` - Общий бюджет фильма, включая все расходы на производство.
- `financing_source` - Источник государственного финансирования.
- `ratings` - Рейтинг фильма на КиноПоиске.
- `genres` - Жанры фильма.

*Прока́тное удостовере́ние фи́льма — документ, дающий право на прокат (демонстрацию) фильма на территории Российской Федерации, а также на его тиражирование и распространение, в том числе по кабельным или эфирным каналам.
