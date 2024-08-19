<template>
  <nav class="py-3 px-5 d-flex align-items-center justify-content-between">
    <h1>
      <img src="@/assets/images.png" alt="" width="40" height="40" />
    </h1>
    <ul class="list-unstyled d-flex align-items-center gap-3 mb-0">
      <li>
        <RouterLink to="products">產品系列</RouterLink>
      </li>
      <li>
        <RouterLink to="news">最新消息</RouterLink>
      </li>
      <li>
        <RouterLink to="about">關於我們</RouterLink>
      </li>
      <li>
        <RouterLink to="qa">Q&A</RouterLink>
      </li>
    </ul>
  </nav>
</template>
