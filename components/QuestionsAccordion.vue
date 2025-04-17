<template>
  <section class="questions-and-answers-o">
    <div class="__container">
      <div class="questions-and-answers-o__block">
        <h2 class="questions-and-answers-o__title">Вопросы и ответы</h2>
        <ul class="questions-and-answers-o__list-items">
          <li class="questions-and-answers-o__item">
            <a
              class="questions-and-answers-o__closed-header"
              href="#"
              @click.prevent="toggleAll"
            >
              <span class="questions-and-answers-o__closed bold-span">
                Закрытый заголовок (для наглядности не&nbsp;раскрытого вопроса)
              </span>
              <img
                class="questions-and-answers-o__icon-closed"
                src="/images/questions-and-answers-icon-closed.svg"
                :class="{ rotated: isAllOpen }"
                alt="closed"
              />
            </a>
          </li>
          <transition  name="fade-expand">
              <div v-show="isAllOpen">
                <li
                  v-for="(item, index) in questions"
                  :key="index"
                  class="questions-and-answers-o__item"
                >
                  <a
                    class="questions-and-answers-o__closed-header"
                    href="#"
                    @click.prevent="toggle(index)"
                  >
                    <span class="questions-and-answers-o__closed bold-span">
                      {{ item.title }}
                    </span>
                    <img
                      class="questions-and-answers-o__icon-closed"
                      src="/images/questions-and-answers-icon-ellipse.svg"
                      :class="{ rotated: isOpen(index) }"
                      alt="arrow"
                    />
                  </a>
                  <transition name="fade-expand">
                  <p
                    v-show="isOpen(index)"
                    class="questions-and-answers-o__text text-determining"
                  >
                    {{ item.text }}
                  </p>
                </transition>
                </li>
              </div>
          </transition>
        </ul>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue';

const questions = [
  {
    title: 'Кто такие самозанятые?',
    text: 'Самозанятые — это граждане, официально зарегистрированные как плательщики налога на профессиональный доход (НПД). Самозанятыми могут быть предприниматели, которые не имеют наёмных сотрудников, и чей суммарных доход от профессиональной деятельности не превышает 2,4 млн рублей в год.',
  },
  {
    title: 'Какие налоги платят самозанятые?',
    text: 'Для самозанятых, оказывающих услуги юридическому лицу, ставка налога составляет 6%.',
  },
  {
    title: 'Как оплачивать налоги?',
    text: 'Каждый месяц до 25 числа. Самостоятельно вести бухгалтерию не нужно. Квитанция для оплаты налога автоматически формируется по итогам предыдущего месяца и направляется вам в приложение «Мой налог» — оплатить её можно там же или через приложение вашего банка.',
  },

  {
    title: 'Как зарегистрироваться и платить налог по НПД?',
    text: 'Всё просто: скачайте приложение «Мой налог», заполните в нём анкету и сфотографируйте себя и свой паспорт. Налог на самозанятых оплачивается дистанционно, без личного посещения ФНС, через мобильное приложение «Мой налог», личный кабинет на сайте налоговой службы, кредитную организацию (список есть на сайте налоговой инспекции).',
  },
  {
    title: 'Можно ли стать самозанятым, если основной доход — работа по найму?',
    text: 'Да, можно получать заработную плату на основной работе и зарегистрироваться в качестве самозанятого. Сумма доходов от работодателя не будет учитываться при расчёте лимита для специального налогового режима. Платить налог на профессиональный доход с заработной платы тоже не придётся.',
  },
  {
    title: 'Как перестать быть самозанятым?',
    text: 'В личном кабинете налогоплательщика или в приложении «Мой налог» перейдите в Настройки → Партнёры → Подключённые, найдите Яндекс и нажмите «Отключиться».',
  },
  {
    title: 'Где узнать подробности?',
    text: 'На сайте ФНС России о налоге на профессиональный доход.',
  },
];

const openedIndex = ref(null);
const isAllOpen = ref(false);

const toggle = (index) => {
  openedIndex.value = openedIndex.value === index ? null : index;
};

const toggleAll = () => {
  isAllOpen.value = !isAllOpen.value;
  openedIndex.value = null; // сбрасываем индивидуальный выбор
};

const isOpen = (index) => openedIndex.value === index;
</script>
<style>
.questions-and-answers-o__icon-closed {
  transition: transform 0.3s ease;
}

.questions-and-answers-o__icon-closed.rotated {
  transform: rotate(180deg);
}

.fade-expand-enter-active,
.fade-expand-leave-active {
  transition: all 0.3s ease;
  overflow: hidden;
}

.fade-expand-enter-from,
.fade-expand-leave-to {
  max-height: 0;
  opacity: 0;
}

.fade-expand-enter-to,
.fade-expand-leave-from {
  max-height: 500px; 
  opacity: 1;
}
</style>
