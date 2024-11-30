<template>
  <header
    class="flex items-center h-16 bg-white px-7 text-sm text-slate-800 z-30 relative"
  >
    <a class="pr-3">
      <!-- LOGO -->
      <img
        src="https://www.udemy.com/staticx/udemy/images/v7/logo-udemy.svg"
        alt="Udemy"
        width="91"
        height="34"
        loading="lazy"
      />
    </a>

    <div class="text-slate-600">
      <!-- 分类 -->
      分类
    </div>

    <div
      class="grow border border-slate-800 rounded-3xl flex items-center mx-3 h-10"
    >
      <!-- 搜索框 -->
      <Icon class="px-4" name="uil:search" style="color: black" />

      <input
        type="text"
        class="grey text-slate-600 border-none outline-none"
        placeholder="搜索任何内容"
      />
    </div>

    <div class="grid-cols-4 gap-4 flex items-center">
      <div class="grow tablet:hidden laptop:block desktop:block">
        计划和定价
      </div>
      <div class="grow">Udemy Business</div>
      <div class="grow tablet:hidden laptop:block desktop:block">
        在Udemy上授课
      </div>
      <div><Icon name="uil:shopping-cart" style="font-size: 26px" /></div>
    </div>

    <div class="flex grid-cols-4 gap-1 pl-2">
      <div
        class="border-solid border border-slate-800 flex items-center justify-center w-20 h-10 cursor-pointer"
      >
        请登录
      </div>

      <div
        class="border-solid border bg-slate-800 text-slate-100 flex items-center justify-center w-20 h-10 cursor-pointer"
      >
        注册
      </div>

      <div
        class="border-solid border border-slate-800 flex items-center justify-center w-10 h-10 cursor-pointer"
      >
        <Icon name="uil:globe" style="font-size: 26px" />
      </div>
    </div>
  </header>
</template>
