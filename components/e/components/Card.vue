<template>
  <UCard>
    <template #header>
      <slot name="header">
        <img src="https://avatars.githubusercontent.com/u/27631697?v=4" alt="daniel">
      </slot>
    </template>

    <slot name="content">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid beatae deleniti dolorem dolores et exercitationem
        ipsum, labore minus necessitatibus provident quia ullam? Dolorum fuga in officiis quia! Cum, dolores perspiciatis.
      </p>
    </slot>

    <template #footer>
      <UButton color="red">
        <slot name="text">
          button text
        </slot>
      </UButton>
    </template>
  </UCard>
</template>
