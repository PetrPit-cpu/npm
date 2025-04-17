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
                <a class="header-npd__link" href="https://cash-it.ru/"> Возможности </a>
              </li>
              <li class="header-npd__item">
                <a class="header-npd__link" href="https://cash-it.ru/blog/"> Блог </a>
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
      <section class="organization">
        <div class="organization__inner _container-lg">
          <img
            class="organization__img"
            src="../assets/images/cooperation.png"
            alt="laptop"
          />
          <div class="organization__info">
            <h2 class="organization__title title">
              Становитесь добросовестным налогоплательщиком и&nbsp;используйте
              Cash&amp;IT максимально эффективно.
            </h2>
            <p class="organization__text text">
              Интеграция Cash&IT с ФНС позволяет настроить сервис таким образом,
              что выплаты будут доступны только физическим лицам, имеющим статус
              плательщика налога на профессиональный доход.
            </p>
          </div>
        </div>
      </section>

      <section class="what-advantages-o">
        <div class="__container">
          <div class="what-advantages-o__person">
            <h2 class="what-advantages-o__title">Преимущества</h2>
            <ul class="what-advantages-o__list-items">
              <li class="what-advantages-o__item">
                <img
                  class="what-advantages-o__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages-o__text-bold"
                  >Вся отчетность для бухгалтерии.</span
                >
              </li>
              <li class="what-advantages-o__item">
                <img
                  class="what-advantages-o__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages-o__text text-b">
                  <span class="what-advantages-o__text-bold"
                    >Электронный документооборот.</span
                  >
                  <p class="what-advantages-o__text text-c">
                    (договоры, акты, чеки.)
                  </p>
                </span>
              </li>
              <li class="what-advantages-o__item">
                <img
                  class="what-advantages-o__jackdaw-svg"
                  src="../assets/images/what-advantages-jackdaw.svg"
                  alt="jackdaw"
                />
                <span class="what-advantages-o__text text-b">
                  <span class="what-advantages-o__text-bold"
                    >Автоматическая фискализация.</span
                  >
                  <p class="what-advantages-o__text text-c">
                    Сервис автоматически фискализирует доход по каждому заказу,
                    выполненному исполнителем. Если исполнитель прекратил
                    регистрацию в качестве самозанятого — сервис заблокирует ему
                    выплаты, а вам придет уведомление.
                  </p>
                </span>
              </li>
            </ul>
          </div>
        </div>
      </section>

      <!-- <section class="questions-and-answers-o">
        <div class="__container">
          <div class="questions-and-answers-o__block">
            <h2 class="questions-and-answers-o__title">Вопросы и ответы</h2>
            <ul class="questions-and-answers-o__list-items">
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="#">
                  <span class="questions-and-answers-o__closed bold-span">
                    Закрытый заголовок (для наглядности не&nbsp;раскрытого
                    вопроса)
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-closed.svg"
                    alt="closed"
                  />
                </a>
              </li>
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="#">
                  <span class="questions-and-answers-o__closed bold-span">
                    Кто такие самозанятые?
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers-o__text text-determining">
                  Самозанятые&nbsp;&mdash; это граждане, официально
                  зарегистрированные как плательщики налога
                  на&nbsp;профессиональный доход (НПД). Самозанятыми могут быть
                  предприниматели, которые не&nbsp;имеют наёмных сотрудников,
                  и&nbsp;чей суммарных доход от&nbsp;профессиональной
                  деятельности не&nbsp;превышает 2,4 млн рублей в&nbsp;год.
                </p>
              </li>
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="#">
                  <span class="questions-and-answers-o__closed bold-span">
                    Какие налоги платят самозанятые?
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers-o__text text-determining">
                  Для самозанятых, оказывающих услуги юридическому лицу, ставка
                  налога составляет&nbsp;6%
                </p>
              </li>
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="#">
                  <span class="questions-and-answers-o__closed bold-span">
                    Как оплачивать налоги?
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers-o__text text-determining">
                  Каждый месяц до&nbsp;25&nbsp;числа. Самостоятельно вести
                  бухгалтерию не&nbsp;нужно. Квитанция для оплаты налога
                  автоматически формируется по&nbsp;итогам предыдущего месяца
                  и&nbsp;направляется вам в&nbsp;приложение &laquo;Мой
                  налог&raquo;&nbsp;&mdash; оплатить её&nbsp;можно там&nbsp;же
                  или через приложение вашего банка.
                </p>
              </li>
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="">
                  <span class="questions-and-answers-o__closed bold-span">
                    Как зарегистрироваться и&nbsp;платить налог по&nbsp;НПД?
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers-o__text text-determining">
                  Всё просто: скачайте приложение &laquo;Мой налог&raquo;,
                  заполните в&nbsp;нём анкету и&nbsp;сфотографируйте себя
                  и&nbsp;свой паспорт. Налог на&nbsp;самозанятых оплачивается
                  дистанционно, без личного посещения ФНС, через мобильное
                  приложение &laquo;Мой налог&raquo;, личный кабинет
                  на&nbsp;сайте налоговой службы, кредитную организацию (список
                  есть на&nbsp;сайте налоговой инспекции).
                </p>
              </li>
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="">
                  <span class="questions-and-answers-o__closed bold-span">
                    Можно&nbsp;ли стать самозанятым, если основной
                    доход&nbsp;&mdash; работа по&nbsp;найму?
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers-o__text text-determining">
                  Да, можно получать заработную плату на&nbsp;основной работе
                  и&nbsp;зарегистрироваться в&nbsp;качестве самозанятого. Сумма
                  доходов от&nbsp;работодателя не&nbsp;будет учитываться при
                  расчёте лимита для специального налогового режима. Платить
                  налог на&nbsp;профессиональный доход с&nbsp;заработной платы
                  тоже не&nbsp;придётся.
                </p>
              </li>
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="">
                  <span class="questions-and-answers-o__closed bold-span">
                    Как перестать быть самозанятым?
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers-o__text text-determining">
                  В&nbsp;личном кабинете налогоплательщика или в&nbsp;приложении
                  &laquo;Мой налог&raquo; перейдите в&nbsp;Настройки &rarr;
                  Партнёры &rarr; Подключённые, найдите Яндекс и&nbsp;нажмите
                  &laquo;Отключиться&raquo;.
                </p>
              </li>
              <li class="questions-and-answers-o__item">
                <a class="questions-and-answers-o__closed-header" href="">
                  <span class="questions-and-answers-o__closed bold-span">
                    Где узнать подробности?
                  </span>
                  <img
                    class="questions-and-answers-o__icon-closed"
                    src="../assets/images/questions-and-answers-icon-ellipse.svg"
                    alt="closed"
                  />
                </a>
                <p class="questions-and-answers-o__text text-determining">
                  На&nbsp;сайте ФНС России о&nbsp;налоге
                  на&nbsp;профессиональный доход.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </section> -->
      <QuestionsAccordion />

      <section class="connect-o">
        <div class="connect-o__manual">
          <div class="connect-o__content">
            <h2 class="connect-o__title title-done">Подключиться</h2>
            <div class="connect-o__block-content-form">
              <form class="connect-o__form">
                <label class="connect-o__label">
                  <input
                    type="text"
                    class="connect-o__input"
                    placeholder="Введите ваше имя*"
                    required
                  />
                </label>
                <label class="connect-o__label">
                  <input
                    type="tel"
                    class="connect-o__input"
                    placeholder="Ваш номер телефона*"
                    required
                  />
                </label>
                <label class="connect-o__label label-mb">
                  <input
                    type="email"
                    class="connect-o__input"
                    placeholder="email-адрес"
                    required
                  />
                </label>
                <button type="submit" class="connect-o__button">
                  Отправить
                </button>
              </form>
            </div>
          </div>

          <div class="connect-o__block">
            <h2 class="connect-o__title">Скачать приложение</h2>
            <ul class="connect-o__list-items">
              <div class="connect-o__icon-block-link">
                <li class="connect-o__item">
                  <a
                    class="connect-o__link"
                    href="https://play.google.com/store/apps/details?id=ru.cashit"
                  >
                    <img src="../assets/images/download-the-app-google.svg" />
                  </a>
                </li>
                <li class="connect-o__item">
                  <a
                    class="connect-o__link"
                    href="https://apps.apple.com/ru/app/cash-it/id1571869091"
                  >
                    <img src="../assets/images/download-the-app-apple.svg" />
                  </a>
                </li>
                <li class="connect-o__item">
                  <a
                    class="connect-o__link"
                    href="https://appgallery.huawei.com/#/app/C108605507"
                  >
                    <img
                      src="../assets/images/download-the-app-AppGallery.svg"
                    />
                  </a>
                </li>
                <li class="connect-o__item">
                  <a
                    class="connect-o__link"
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

const buttonRef = ref(null); // Создаём ref для кнопки

onMounted(() => {
  if (buttonRef.value) {
    buttonRef.value.addEventListener("click", () => {
      window.open("https://pay.cash-it.ru/", "_blank");
    });
  }
});
</script>
