<template>
  <div v-if="isVisible" class="notification">
    <div class="notification__content">
      <span class="notification__message">
        На нашем сайте мы используем cookie-файлы и Яндекс-Метрику для обработки
        персональных данных.
      </span>
      <span class="notification__message">
        Продолжая использовать сайт вы даёте согласие на обработку персональных
        данных.
      </span>
      <a href="/policy.pdf" target="_blank" class="notification__link">
        Узнать подробнее
      </a>
    </div>

    <button @click="acceptPolicy" class="notification__button">
      <span class="notification__button-text">Согласен</span>
    </button>
  </div>
</template>
<script setup>
const isVisible = ref(false);
const ACCEPTED_POLICY_KEY = 'accepted_policy';

const checkPolicy = () => {
  const accepted = localStorage.getItem(ACCEPTED_POLICY_KEY);

  if (!accepted) {
    isVisible.value = true;
  }
};
const acceptPolicy = () => {
  localStorage.setItem(ACCEPTED_POLICY_KEY, 'true');
  isVisible.value = false;
};

onMounted(() => {
  checkPolicy();
});
</script>

<style lang="scss">
.notification {
  font-size: 20px;
  position: fixed;
  right: 1rem;
  bottom: 1.5rem;
  width: calc(100% - 2rem);
  max-width: 57.7rem;
  padding: 1.5rem;
  background-color: #fff;
  box-shadow: 0 1px 20px #0000029a;
  border-radius: 1rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 100;

  &__content {
    display: flex;
    flex-direction: column;
    color: #39393d;
    margin-right: 1.5rem;
    gap: 0.4rem;
  }

  &__message {
    margin-bottom: 0.5rem;

    @media (min-width: 768px) {
      margin-bottom: 0;
      margin-right: 1rem;
    }
  }

  &__link {
    color: #007aff;
    text-decoration: none;
    border: none;
    background: none;
    padding: 0;
    margin: 0;
    cursor: pointer;
  }

  &__button {
    max-width: 300px;
    padding: 24px 0;
    color: #fff;
    font-size: 20px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    border-radius: 60px;
    background-color: #f9423a;
    box-shadow: 0px 10px 20px 0px rgb(249 66 58 / 50%);
    border: none;
    outline: none;
    transition: all 0.3s ease;
    width: 100%;

    &:hover {
      background-color: #ff4e46;
    }
    @media (max-width: 480px) {
      padding: 15px 0;
    }
  }

  &__button-text {
    font-weight: 500;
  }
  @media (max-width: 768px) {
    align-items: baseline;
    flex-direction: column;
    font-size: 16px;
    gap: 1.2rem;
  }
}
</style>
