<template>
  <div class="wrapper">
    <header class="header-npd">
      <div class="_container-lg">
        <div class="header-npd__inner">
          <a target="_blank" href="https://cash-it.ru/">
            <img src="../assets/images/logo.svg" alt="" />
          </a>
          <nav class="header-npd__nav">
            <ul class="header-npd__list-items">
              <li class="header-npd__item">
                <a class="header-npd__link" href="https://cash-it.ru/">
                  Возможности
                </a>
              </li>
              <li class="header-npd__item">
                <a class="header-npd__link" href="https://cash-it.ru/blog/">
                  Блог
                </a>
              </li>
            </ul>
          </nav>
          <button ref="buttonRef" class="header-npd__btn-click">
            Отраслевые решения
          </button>
        </div>
      </div>
    </header>

    <main class="main">
      <section class="person-n">
        <div class="person-n__inner">
          <img
            class="person-n__img"
            src="../assets/images/cooperation.png"
            alt="laptop"
          />
          <div class="person-n__info">
            <h2 class="person-n__title title">
              Становитесь самозанятым вместе с&nbsp;нашим сервисом
            </h2>
            <p class="person-n__text text">
              <span
                >После регистрации вам откроется доступ в&nbsp;личный
                кабинет:</span
              >
              <span>там вы&nbsp;сможете видеть расчёт собственного дохода</span>
              <span>и&nbsp;выводить деньги в&nbsp;один клик.</span>
            </p>
          </div>
        </div>
      </section>

      <section class="what-advantages">
        <div class="__container">
          <div class="what-advantages__person">
            <h2 class="what-advantages__title">Преимущества</h2>
            <ul class="what-advantages__list-items">
              <li class="what-advantages__item">
                <img
                  class="what-advantages__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages__text text-b">
                  Самозанятые платят налог по&nbsp;льготной ставке &mdash;
                  <span class="what-advantages__text-bold">4 или 6 %</span>
                </span>
              </li>
              <li class="what-advantages__item">
                <img
                  class="what-advantages__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages__text text-b">
                  Самозанятые платят налоги
                  <span class="what-advantages__text-bold"
                    >только с&nbsp;доходов от&nbsp;своей деятельности.</span
                  >
                  Если доходов не&nbsp;было, то&nbsp;платить ничего
                  не&nbsp;надо. Перевод зарплаты с&nbsp;основного места работы
                  не&nbsp;облагается налогом на&nbsp;профессиональный доход.
                </span>
              </li>
              <li class="what-advantages__item">
                <img
                  class="what-advantages__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages__text text-b">
                  <span class="what-advantages__text-bold"
                    >Простая регистрация</span
                  >
                  <p class="what-advantages__text text-c">
                    (в&nbsp;мобильном приложении, на&nbsp;сайте ФНС России,
                    через банк или портал Госуслуг)
                  </p>
                </span>
              </li>
              <li class="what-advantages__item">
                <img
                  class="what-advantages__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages__text-bold"
                  >Предоставляется налоговый вычет&nbsp;&mdash; 10
                   000&nbsp;рублей.</span
                >
              </li>
              <li class="what-advantages__item">
                <img
                  class="what-advantages__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages__text text-b">
                  <span class="what-advantages__text-bold"
                    >Нет отчетов и&nbsp;деклараций</span
                  >
                  <p class="what-advantages__text text-c">
                    (Декларацию представлять не&nbsp;нужно. Учёт доходов ведётся
                    автоматически в&nbsp;мобильном приложении.)
                  </p>
                </span>
              </li>
            </ul>
          </div>
        </div>
      </section>

      <section class="how-to-register">
        <div class="__container">
          <div class="how-to-register__manual">
            <!-- Слайдер -->
            <swiper-container ref="swiperRef">
              <swiper-slide>
                <img
                  class="how-to-register__manual-phone"
                  src="../assets/images/Nastrojki-2.png"
                  alt="phone"
                />
              </swiper-slide>
              <swiper-slide>
                <img
                  class="how-to-register__manual-phone"
                  src="../assets/images/Nastrojki-3.png"
                  alt="phone"
                />
              </swiper-slide>
              <swiper-slide>
                <img
                  class="how-to-register__manual-phone"
                  src="../assets/images/how-to-register-manual-phone.png"
                  alt="phone"
                />
              </swiper-slide>
            </swiper-container>

            <div class="how-to-register__block">
              <h2 class="how-to-register__title">Как зарегистрироваться</h2>
              <ul class="how-to-register__list-items">
                <li class="how-to-register__item">
                  <span class="how-to-register__ellipse">1</span>
                  <span class="how-to-register__text text-e">
                    Откройте раздел &laquo;Настройки&raquo; в&nbsp;приложении.
                  </span>
                </li>
                <li class="how-to-register__item">
                  <span class="how-to-register__ellipse">2</span>
                  <span class="how-to-register__text text-e">
                    Перейдите в&nbsp;раздел &laquo;Самозанятость&raquo;.
                  </span>
                </li>
                <li class="how-to-register__item">
                  <div class="how-to-register__content-text">
                    <span class="how-to-register__ellipse">3</span>
                    <div class="how-to-register__text-comfortable text-b">
                      <span class="how-to-register__text text-e">
                        Нажмите &laquo;Привязать аккаунт&raquo;.
                      </span>
                      <p class="text-b">
                        Выберите удобный способ привязки (ИНН или номер
                        телефона).
                      </p>
                      <p class="text-b">
                        Заполните поле и&nbsp;нажмите &laquo;Привязать
                        аккаунт&raquo;
                      </p>
                    </div>
                  </div>
                </li>
                <li class="how-to-register__item">
                  <div class="how-to-register__content-text">
                    <span class="how-to-register__ellipse">4</span>
                    <div class="how-to-register__text-comfortable text-b">
                      <span class="how-to-register__text text-e">
                        Подтвердите запрос.
                      </span>
                      <p class="text-b">
                        На&nbsp;сайте или в&nbsp;приложении &laquo;Мой
                        налог&raquo; вы&nbsp;получите уведомление о&nbsp;запросе
                        на&nbsp;привязку аккаунта НПД от&nbsp;сервиса
                        Cash&amp;IT. Перейдите по&nbsp;этому уведомлению
                        и&nbsp;подтвердите разрешение.
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <section class="questions-and-answers">
        <div class="__container">
          <div class="questions-and-answers__block">
            <h2 class="questions-and-answers__title">Вопросы и ответы</h2>
            <ul class="questions-and-answers__list-items">
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Закрытый заголовок (для наглядности не&nbsp;раскрытого
                    вопроса)
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-closed.svg"
                    alt="closed"
                  />
                </a>
              </li>
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Кто такие самозанятые?
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers__text text-determining">
                  Самозанятые&nbsp;&mdash; это граждане, официально
                  зарегистрированные как плательщики налога
                  на&nbsp;профессиональный доход (НПД). Самозанятыми могут быть
                  предприниматели, которые не&nbsp;имеют наёмных сотрудников,
                  и&nbsp;чей суммарных доход от&nbsp;профессиональной
                  деятельности не&nbsp;превышает 2,4 млн рублей в&nbsp;год.
                </p>
              </li>
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Какие налоги платят самозанятые?
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers__text text-determining">
                  Для самозанятых, оказывающих услуги юридическому лицу, ставка
                  налога составляет&nbsp;6%
                </p>
              </li>
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Как оплачивать налоги?
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers__text text-determining">
                  Каждый месяц до&nbsp;25&nbsp;числа. Самостоятельно вести
                  бухгалтерию не&nbsp;нужно. Квитанция для оплаты налога
                  автоматически формируется по&nbsp;итогам предыдущего месяца
                  и&nbsp;направляется вам в&nbsp;приложение &laquo;Мой
                  налог&raquo;&nbsp;&mdash; оплатить её&nbsp;можно там&nbsp;же
                  или через приложение вашего банка.
                </p>
              </li>
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Как зарегистрироваться и&nbsp;платить налог по&nbsp;НПД?
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers__text text-determining">
                  Всё просто: скачайте приложение &laquo;Мой налог&raquo;,
                  заполните в&nbsp;нём анкету и&nbsp;сфотографируйте себя
                  и&nbsp;свой паспорт. Налог на&nbsp;самозанятых оплачивается
                  дистанционно, без личного посещения ФНС, через мобильное
                  приложение &laquo;Мой налог&raquo;, личный кабинет
                  на&nbsp;сайте налоговой службы, кредитную организацию (список
                  есть на&nbsp;сайте налоговой инспекции).
                </p>
              </li>
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Можно&nbsp;ли стать самозанятым, если основной
                    доход&nbsp;&mdash; работа по&nbsp;найму?
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers__text text-determining">
                  Да, можно получать заработную плату на&nbsp;основной работе
                  и&nbsp;зарегистрироваться в&nbsp;качестве самозанятого. Сумма
                  доходов от&nbsp;работодателя не&nbsp;будет учитываться при
                  расчёте лимита для специального налогового режима. Платить
                  налог на&nbsp;профессиональный доход с&nbsp;заработной платы
                  тоже не&nbsp;придётся.
                </p>
              </li>
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Как перестать быть самозанятым?
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers__text text-determining">
                  В&nbsp;личном кабинете налогоплательщика или в&nbsp;приложении
                  &laquo;Мой налог&raquo; перейдите в&nbsp;Настройки &rarr;
                  Партнёры &rarr; Подключённые, найдите Яндекс и&nbsp;нажмите
                  &laquo;Отключиться&raquo;.
                </p>
              </li>
              <li class="questions-and-answers__item">
                <a class="questions-and-answers__closed-header" href="#">
                  <span class="questions-and-answers__closed bold-span">
                    Где узнать подробности?
                  </span>
                  <img
                    class="questions-and-answers__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers__text text-determining">
                  На&nbsp;сайте ФНС России о&nbsp;налоге
                  на&nbsp;профессиональный доход.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <section class="download-the-app">
        <div class="__container">
          <div class="download-the-app__block">
            <h2 class="download-the-app__title">Скачать приложение</h2>
            <ul class="download-the-app__list-items">
              <li class="download-the-app__item">
                <a target="_blank" href="https://cash-it.ru/">
                  <img src="../assets/images/download-the-app-img-logo.svg" />
                </a>
              </li>
              <div class="download-the-app__icon-block-link">
                <li class="download-the-app__item">
                  <a
                    class="download-the-app__link"
                    href="https://play.google.com/store/apps/details?id=ru.cashit"
                  >
                    <img src="../assets/images/download-the-app-google.svg" />
                  </a>
                </li>
                <li class="download-the-app__item">
                  <a
                    class="download-the-app__link"
                    href="https://apps.apple.com/ru/app/cash-it/id1571869091"
                  >
                    <img src="../assets/images/download-the-app-apple.svg" />
                  </a>
                </li>
                <li class="download-the-app__item">
                  <a
                    class="download-the-app__link"
                    href="https://appgallery.huawei.com/#/app/C108605507"
                  >
                    <img
                      src="../assets/images/download-the-app-AppGallery.svg"
                    />
                  </a>
                </li>
                <li class="download-the-app__item">
                  <a
                    class="download-the-app__link"
                    href="https://www.rustore.ru/catalog/app/ru.cashit"
                  >
                    <img src="../assets/images/download-the-app-RuStore.svg" />
                  </a>
                </li>
              </div>
            </ul>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";
import { useSwiper } from "swiper/vue";

const buttonRef = ref(null); // Создаём ref для кнопки

onMounted(() => {
  if (buttonRef.value) {
    buttonRef.value.addEventListener("click", () => {
      window.open("https://pay.cash-it.ru/", "_blank");
    });
  }
});

const swiperRef = ref(null);

// Используем useSwiper для управления слайдами
const swiper = useSwiper(swiperRef, {
  loop: true, // Бесконечный просмотр слайдов
  autoplay: { delay: 3000 }, // Автопрокрутка каждые 3 сек.
  slidesPerView: 1, // Показываем 1 слайд за раз
  spaceBetween: 0, // Отступ между слайдами
});
</script>
