<template>
  <div class="wrapper">
    <header class="header">
      <div class="_container-lg">
        <div class="header__inner">
          <a target="_blank" href="https://cash-it.ru/">
            <img src="../assets/images/logo.svg" alt="" />
          </a>
        </div>
      </div>
    </header>

    <main class="main">
      <section class="payment">
        <div class="payment__inner">
          <img
            class="payment__img"
            src="../assets/images/laptop.png"
            alt="laptop"
          />
          <div class="payment__info">
            <h1 class="payment__title">
              Сервис моментальных выплат для физических лиц
            </h1>
            <div class="payment__text">
              Решение ваших ежедневных рутинных задач за считанные секунды.
            </div>
            <button @click="scrollToForm" class="payment__btn btn">
              Подробнее
            </button>
          </div>
        </div>
      </section>

      <section class="for-whom">
        <div class="__container">
          <div class="for-whom__inner">
            <h2 class="for-whom__title title">Для кого</h2>
            <div class="for-whom__text">
              Сервис имеет готовый функционал для многих отраслей бизнеса, таких
              как:
            </div>
            <div class="for-whom__cards">
              <div class="for-whom__card">
                <div class="for-whom__card-text">Курьерские услуги</div>
                <img
                  src="../assets/images/for-whom-card1.png"
                  alt=""
                  class="for-whom__card-img"
                />
              </div>
              <div class="for-whom__card">
                <div class="for-whom__card-text">Клининг</div>
                <img
                  src="../assets/images/for-whom-card2.png"
                  alt=""
                  class="for-whom__card-img"
                />
              </div>
              <div class="for-whom__card">
                <div class="for-whom__card-text">Бьюти сфера</div>
                <img
                  src="../assets/images/for-whom-card3.png"
                  alt=""
                  class="for-whom__card-img"
                />
              </div>
              <div class="for-whom__card">
                <div class="for-whom__card-text">Перевозки</div>
                <img
                  src="../assets/images/for-whom-card4.png"
                  alt=""
                  class="for-whom__card-img"
                />
              </div>
              <div class="for-whom__card">
                <div class="for-whom__card-text">Автодилеры</div>
                <img
                  src="../assets/images/for-whom-card5.png"
                  alt=""
                  class="for-whom__card-img"
                />
              </div>
              <div class="for-whom__card">
                <div class="for-whom__card-text">
                  И многие другие виды бизнеса
                </div>
                <img
                  src="../assets/images/for-whom-card6.png"
                  alt=""
                  class="for-whom__card-img"
                />
              </div>
            </div>
            <button @click="scrollToForm" class="for-whom__btn btn">
              Запросить консультацию
            </button>
            <div class="for-whom__text">
              Адаптируем сервис с учетом специфики вашего бизнеса.
            </div>
          </div>
        </div>
      </section>

      <section class="trust">
        <div class="__container">
          <div class="trust__inner">
            <h2 class="trust__title title">Нам доверяют</h2>

            <div class="trust__card-text">
              Наш сервис имеет внушительный список банков-партнеров:
            </div>
            <div class="trust__card-partners">
              <img src="../assets/images/partners/1.png" alt="" />
              <img src="../assets/images/partners/2.png" alt="" />
              <img src="../assets/images/partners/3.png" alt="" />
              <img src="../assets/images/partners/4.png" alt="" />
              <img src="../assets/images/partners/5.png" alt="" />
              <img src="../assets/images/partners/6.png" alt="" />
            </div>
            <div class="trust__integration">
              <div class="trust__integration-text">Ближайшие интеграции:</div>
              <div class="trust__integration-partners">
                <img
                  class="trust__integration-img"
                  src="../assets/images/partners/7.png"
                  alt=""
                />
                <img
                  class="trust__integration-img"
                  src="../assets/images/partners/8.png"
                  alt=""
                />
                <img
                  class="trust__integration-img"
                  src="../assets/images/partners/9.png"
                  alt=""
                />
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="accordance">
        <div class="__container">
          <div class="accordance__inner">
            <h2 class="accordance__title title">
              Соответствие законодательству
            </h2>
            <div class="accordance__text">
              Наш сервис полностью соответствует действующему законодательству и
              исключает блокировку.
            </div>
            <ul class="accordance__list">
              <li class="accordance__list-item">
                <img src="../assets/images/accordance__list-item.svg" alt="" />
                <p>Заключение договора с исполнителем</p>
              </li>
              <li class="accordance__list-item">
                <img src="../assets/images/accordance__list-item.svg" alt="" />
                <p>Подготовка и отправка отчетов агентов</p>
              </li>
              <li class="accordance__list-item">
                <img src="../assets/images/accordance__list-item.svg" alt="" />
                <p>Фискализация дохода юридического лица (кассовые чеки)</p>
              </li>
            </ul>
          </div>
        </div>
      </section>

      <section class="how-it-works">
        <div class="__container">
          <div class="how-it-works__inner">
            <h2 class="how-it-works__title title">Как это работает</h2>
            <div class="how-it-works__main">
              <img src="../assets/images/how-it-works-img.png" alt="" />
              <div class="how-it-works__cards">
                <div class="how-it-works__card">
                  <div class="how-it-works__card-text">
                    Заключаете договор с нами и банком партнером
                  </div>
                </div>
                <div class="how-it-works__card">
                  <div class="how-it-works__card-text">
                    <span>Пополняете счет в банке <br /></span>(в рамках этого
                    баланса исполнители могут выводить денежные средства)
                  </div>
                </div>
                <div class="how-it-works__card">
                  <div class="how-it-works__card-text">
                    <span>Добавляете исполнителей</span> <br />
                    (вручную, реестром, по API)
                  </div>
                </div>
                <div class="how-it-works__card">
                  <div class="how-it-works__card-text">
                    Перед первым выводом, исполнитель заключает договор с вашей
                    организацией используя простую электронную подпись.
                  </div>
                </div>
                <div class="how-it-works__card">
                  <div class="how-it-works__card-text">
                    Исполнитель пользуясь мобильным приложением выводит средства
                    исходя из настроек
                  </div>
                </div>
                <div class="how-it-works__card">
                  <div class="how-it-works__card-text">
                    Мы делаем всё остальное.
                  </div>
                  <button @click="scrollToForm" class="how-it-works__btn">
                    Связаться с нами
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="team">
        <div class="__container">
          <div class="team__inner">
            <div class="team__desc">
              <h2 class="team__text">
                Растите команду исполнителей и зарабатывайте больше — мы
                позаботимся об остальном!
              </h2>
              <button @click="scrollToForm" class="team__btn btn">
                Подключиться
              </button>
            </div>
            <img
              src="../assets/images/team.png
            "
              alt=""
              class="team__img"
            />
          </div>
        </div>
      </section>

      <section class="integrations">
        <div class="__container">
          <div class="integrations__inner">
            <div class="integrations__title title">Интеграции</div>
            <div class="integrations__text">
              Сервис интегрирован с крупнейшими агрегаторами заказов, а новые
              интеграции занимают не более 7 дней.
            </div>
            <div class="integrations__partners">
              <img src="../assets/images/integrations/1.svg" alt="" />
              <img src="../assets/images/integrations/2.svg" alt="" />
              <img src="../assets/images/integrations/3.svg" alt="" />
              <img src="../assets/images/integrations/4.svg" alt="" />
              <img src="../assets/images/integrations/5.svg" alt="" />
              <img src="../assets/images/integrations/6.svg" alt="" />
            </div>
          </div>
        </div>
      </section>

      <section class="employee">
        <div class="__container">
          <div class="employee__inner">
            <img
              class="employee__img"
              src="../assets/images/employee.png"
              alt=""
            />
            <div class="employee__desc">
              <div class="employee__title">
                Есть штатные сотрудники на фиксированном окладе или стоимости
                смены?
              </div>
              <div class="employee__text">
                У нас есть решение и для такой задачи. Гибкий расчет заработной
                платы штатным сотрудникам — сделайте моментальные выплаты своим
                конкурентным преимуществом.
              </div>
              <button @click="scrollToForm" class="employee__btn btn">
                Хочу моментальные выплаты
              </button>
            </div>
          </div>
        </div>
      </section>

      <section ref="form" class="connect">
        <div class="__container">
          <div class="connect__inner">
            <form class="connect__form" @submit.prevent="onSubmit">
              <div class="connect__title">Подключайтесь</div>
              <div class="_error" v-if="v$.name.$error">
                {{ v$.name.$errors[0].$message }}
              </div>
              <input
                placeholder="Введите ваше имя*"
                :class="{
                  _error_border: v$.name.$error,
                  '_succes-border ': !v$.name.$invalid,
                }"
                @change="v$.name.$touch"
                v-model="formData.name"
                type="text"
              />
              <div class="_error" v-if="v$.phone.$error">
                {{ v$.phone.$errors[0].$message }}
              </div>
              <input
                placeholder="Ваш номер телефона*"
                :class="{
                  _error_border: v$.phone.$error,
                  '_succes-border ': !v$.phone.$invalid,
                }"
                v-maska
                data-maska="+7 (9##) ### ## ##"
                v-model="formData.phone"
                @change="v$.phone.$touch"
                type="tel"
              />
              <div class="_error" v-if="v$.email.$error">
                {{ v$.email.$errors[0].$message }}
              </div>
              <input
                placeholder="email-адрес"
                type="email"
                :class="{
                  _error_border: v$.email.$error,
                  '_succes-border ': !v$.email.$invalid,
                }"
                @change="v$.email.$touch"
                v-model="formData.email"
              />
              <button
                :disabled="disabled"
                type="submit"
                class="connect__btn btn"
              >
                Отправить заявку
              </button>
            </form>
            <img
              class="connect__img"
              src="../assets/images/connect.png"
              alt=""
            />
          </div>
        </div>
      </section>

      <section class="apps">
        <div class="__container">
          <div class="apps__inner">
            <div class="apps__title title">Скачать приложение</div>
            <div class="apps__badjes">
              <a href=""><img src="../assets/images/apps/1.svg" alt="" /></a>
              <a href="https://play.google.com/store/apps/details?id=ru.cashit"
                ><img src="../assets/images/apps/2.svg" alt=""
              /></a>
              <a href="https://apps.apple.com/ru/app/cash-it/id1571869091"
                ><img src="../assets/images/apps/3.svg" alt=""
              /></a>
              <a href="https://appgallery.huawei.com/#/app/C108605507"
                ><img src="../assets/images/apps/4.svg" alt=""
              /></a>
              <a href="https://www.rustore.ru/catalog/app/ru.cashit"
                ><img src="../assets/images/apps/5.svg" alt=""
              /></a>
            </div>
          </div>
        </div>
      </section>
    </main>

    <Success v-if="success" />
    <Error v-if="error" />
    <PolicyBanner />
  </div>
</template>
<script setup>
import { required, helpers, minLength, email } from "@vuelidate/validators";
import { useVuelidate } from "@vuelidate/core";

const { $csrfFetch } = useNuxtApp();
const form = ref(null);
const error = ref(false);
const success = ref(false);
const disabled = ref(false);
const formData = reactive({
  name: "",
  phone: "",
  phone: "",
  email: "",
});

const rules = computed(() => {
  return {
    name: {
      required: helpers.withMessage("это поле обязательное", required),
      minLength: helpers.withMessage("минимум 3 символа", minLength(3)),
    },
    phone: {
      required: helpers.withMessage("это поле обязательное", required),
      minLength: helpers.withMessage(
        "введите номер в формате +7 999 999 99 99",
        minLength(18)
      ),
    },
    email: {
      required: helpers.withMessage("это поле обязательное", required),
      email: helpers.withMessage("e-mail некорректный", email),
      minLength: helpers.withMessage("минимум 3 символа", minLength(3)),
    },
  };
});
const v$ = useVuelidate(rules, formData);

const handleModalError = () => {
  error.value = true;
  setTimeout(() => {
    error.value = false;
  }, 4500);
};

const handleModalSuccess = () => {
  success.value = true;
  setTimeout(() => {
    success.value = false;
  }, 4500);
};

const scrollToForm = () => {
  form.value.scrollIntoView({ behavior: "smooth" });
};
const onSubmit = () => {
  v$.value.$validate();
  if (formData.phone.length >= 18 && formData.name.length >= 3) {
    disabled.value = true;
    $csrfFetch("/api/contact", {
      method: "POST",
      body: {
        from: formData.name,
        phone: formData.phone,
        email: formData.email,
      },
    })
      .then(() => {
        handleModalSuccess();
      })
      .catch((e) => {
        handleModalError();
        console.log(e);
      })
      .finally(() => {
        disabled.value = false;
      });
    formData.name = "";
    formData.phone = "";
    formData.email = "";
  }
  v$.value.$reset();
};
</script>
