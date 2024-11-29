<template>
  <main class="bg-slate-900 w-full h-96">
    <div class="py-6">
      <div class="mx-8">
        <div class="max-w-6xl mx-auto">
          <div class="max-w-3xl">
            <!-- 中间 -->
            <div class="text-sm mb-9 mt-3 ml-6 flex items-center">
              <span class="text-violet-300 cursor-pointer">开发</span>
              <Icon class="px-4" name="uil:angle-right" style="color: #fff" />
              <span class="text-violet-300 cursor-pointer">编程语言</span>
              <Icon class="px-4" name="uil:angle-right" style="color: #fff" />
              <span class="text-violet-300 cursor-pointer">Python</span>
            </div>

            <!-- 标题 -->
            <h1 class="text-3xl text-white font-bold mb-6 ml-6">
              The Complete Python Bootcamp From Zero to Hero in Python
            </h1>

            <!-- 介绍 -->
            <div class="text-md text-slate-300 font-normal mb-5 ml-6">
              Learn Python like a Professional Start from the basics and go all
              the way to creating your own applications and games
            </div>

            <!-- 创建者 -->
            <div class="text-slate-300 text-sm mb-5 ml-6">
              <span>创建者 </span>
              <a class="mr-1">
                <span
                  class="text-violet-300 underline underline-offset-1 cursor-pointer"
                >
                  Jose Portilla</span
                >,
              </a>

              <a>
                <span
                  class="text-violet-300 underline underline-offset-1 cursor-pointer"
                >
                  Pierian Training
                </span>
              </a>
            </div>

            <!-- 其他信息 -->
            <div class="text-slate-300 text-sm mb-5 ml-6">
              上次更新时间：2023/7 英语 简体中文 [自动], 英语 [自动] ,
            </div>

            <!-- 卡片 -->
            <div class="border flex items-center bg-white rounded-lg h-24 ml-6">
              <div
                class="bg-violet-600 w-60 max-w-22 flex flex-col justify-center items-center rounded-l-lg h-full"
              >
                <Icon
                  class="px-4 mb-2"
                  name="uil:star"
                  style="color: white; font-size: 22px"
                />
                <div class="text-white">高级</div>
              </div>
              <div class="text-sm flex justify-center items-center px-4">
                <span
                  >通过 Udemy 方案访问此最受好评的课程以及 12,000
                  门以上最受好评的课程。<span
                    class="underline underline-offset-1 text-violet-600 cursor-pointer"
                  >
                    查看计划和定价
                  </span></span
                >
              </div>

              <div class="border-r h-1/2"></div>

              <div class="flex flex-col items-center text-sm w-80 px-12">
                <div class="text-xl font-bold">4.6</div>
                <div class="underline underline-offset-1 text-stone-400">
                  523,003 个评分
                </div>
              </div>

              <div class="border-r h-1/2"></div>

              <div class="flex flex-col items-center px-8">
                <Icon
                  class="px-4"
                  name="uil:users-alt"
                  style="color: black; font-size: 20px"
                />
                <div class="flex text-sm font-bold mb-1">1,986,546</div>
                <div class="text-sm text-stone-400">学习者</div>
              </div>
            </div>

            <!-- 您将会学到 -->
            <div class="border ml-6 p-5 mt-12">
              <div class="text-2xl font-bold mb-4">您将会学到</div>
              <div class="flex">
                <ul class="flex flex-wrap justify-between">
                  <li
                    v-for="item of data1"
                    style="width: calc(50% - 2px)"
                    class="py-1"
                  >
                    <div class="flex">
                      <Icon
                        class="px-4 text-slate-800"
                        name="uil:check"
                        style="font-size: 20px"
                      />
                      <div class="text-slate-500 text-sm">
                        <span>{{ item }}</span>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
            </div>

            <!-- 浏览相关主题 -->
            <div class="mt-12 ml-6">
              <div class="text-2xl font-bold mb-6">浏览相关主题</div>

              <div class="flex items-center gap-2">
                <a
                  class="cursor-pointer hover:bg-slate-200 h-12 border border-zinc-900 py-2 px-3 rounded-3xl flex items-center"
                >
                  <span class="text-md font-bold">Python</span>
                </a>

                <a
                  class="cursor-pointer hover:bg-slate-200 h-12 border border-zinc-900 py-2 px-3 rounded-3xl flex items-center"
                >
                  <span class="text-md font-bold">编程语言</span>
                </a>

                <a
                  class="cursor-pointer hover:bg-slate-200 h-12 border border-zinc-900 py-2 px-3 rounded-3xl flex items-center"
                >
                  <span class="text-md font-bold">开发</span>
                </a>
              </div>
            </div>

            <!-- 本课程包括 -->
            <div class="mt-12 ml-6">
              <div class="text-2xl font-bold mb-6">本课程包括：</div>

              <div class="flex items-center gap-2">
                <ul class="flex flex-wrap justify-between">
                  <li
                    class="flex items-center mb-2"
                    style="width: calc(50% - 2px)"
                  >
                    <Icon
                      class="px-4"
                      name="uil:airplay"
                      style="color: black; font-size: 20px"
                    />
                    <div class="ml-3">22 小时 长的随选视频</div>
                  </li>
                  <li
                    class="flex items-center mb-2"
                    style="width: calc(50% - 2px)"
                  >
                    <Icon
                      class="px-4"
                      name="uil:mobile-android"
                      style="color: black; font-size: 20px"
                    />
                    <div class="ml-3">在移动设备和电视上观看</div>
                  </li>
                  <li
                    class="flex items-center mb-2"
                    style="width: calc(50% - 2px)"
                  >
                    <Icon
                      class="px-4"
                      name="uil:code"
                      style="color: black; font-size: 20px"
                    />
                    <div class="ml-3">19 个代码练习</div>
                  </li>
                  <li
                    class="flex items-center mb-2"
                    style="width: calc(50% - 2px)"
                  >
                    <Icon
                      class="px-4"
                      name="uil:trophy"
                      style="color: black; font-size: 20px"
                    />
                    <div class="ml-3">结业证书</div>
                  </li>
                  <li
                    class="flex items-center mb-2"
                    style="width: calc(50% - 2px)"
                  >
                    <Icon
                      class="px-4"
                      name="uil:document-info"
                      style="color: black; font-size: 20px"
                    />
                    <div class="ml-3">15 篇文章</div>
                  </li>
                </ul>
              </div>
            </div>

            <!-- 顶级公司为他们的员工提供这门课程 -->
            <div class="border ml-6 p-5 mt-12">
              <div class="text-sm font-bold mb-4">
                顶级公司为他们的员工提供这门课程
              </div>
              <div class="text-xs text-stone-600">
                此课程被选入我们受全球企业信赖的最受好评的课程系列。<span
                  class="underline underline-offset-2 text-violet-600 cursor-pointer"
                  >了解更多</span
                >
              </div>

              <div class="flex justify-around mt-4">
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/nasdaq-dark.svg"
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/volkswagen-dark.svg"
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/box-dark.svg"
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/netapp-dark.svg"
                />
                <img
                  src="https://s.udemycdn.com/partner-logos/v4/eventbrite-dark.svg"
                />
              </div>
            </div>

            <!-- 代码练习 -->
            <div class="bg-slate-100 ml-6 p-6 mt-12 flex items-center">
              <div class="flex flex-col justify-start mr-9">
                <div class="text-2xl mb-4">代码练习</div>
                <div class="text-sm text-stone-500">
                  本课程包括我们更新的代码练习，因此您可以在学习过程中演练所掌握的技能。
                </div>
                <a
                  class="underline underline-offset-2 text-violet-600 text-sm mt-10"
                >
                  查看演示</a
                >
              </div>

              <img
                class="w-3/5"
                src="https://www.udemy.com/staticx/udemy/js/webpack/coding-exercises-demo-preview-desktop.2957bed27c3ae43a02824b61ad9cda03.png"
                alt=""
                srcset=""
              />
            </div>

            <!-- 课程内容 -->
            <div class="mt-12 ml-6">
              <div class="text-2xl font-bold mb-6">本课程包括</div>

              <div class="mt-5 flex items-center justify-between">
                <div class="text-sm text-stone-700">
                  23 个章节 • 156 个讲座 • 总时长 22 小时 13 分钟
                </div>
                <div class="text-sm text-violet-600 cursor-pointer">
                  展开所有章节
                </div>
              </div>

              <div>
                <details class="group py-4 marker:content-['']">
                  <summary
                    class="flex w-full bg-slate-100 border h-14 items-center pr-4 cursor-pointer select-none justify-between text-left text-base/7 font-semibold text-slate-900 group-open:text-indigo-600"
                  >
                    <div class="flex items-center">
                      <Icon
                        class="px-4 group-open:hidden"
                        name="uil:angle-down"
                        style="color: black; font-size: 20px"
                      ></Icon>
                      <Icon
                        class="px-4 hidden group-open:block"
                        name="uil:angle-up"
                        style="color: black; font-size: 20px"
                      ></Icon>

                      <span class="text-stone-600 text-md"
                        >Course Overview</span
                      >
                    </div>

                    <div class="text-stone-600 text-sm font-normal">
                      5 个讲座 • 19 分钟
                    </div>
                  </summary>
                  <div class="pb-6 pt-6 border">
                    <ul>
                      <li
                        class="flex justify-between px-4 mb-4 text-stone-600"
                        v-for="item in 10"
                      >
                        <div class="flex items-center">
                          <Icon
                            name="uil:document-info"
                            class="mr-4"
                            style="font-size: 16px"
                          ></Icon>
                          <span class="text-sm">Auto-Welcome Message</span>
                        </div>
                        <div class="text-sm">00:44</div>
                      </li>
                    </ul>
                  </div>
                </details>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- 右侧浮动 -->
    <!-- <div class="sidebar-container-position-manager">
      <div
        class="course-landing-page bg-white min-w-80 h-20 ml-auto top-24"
      ></div>
    </div> -->
  </main>
</template>

<script setup>
const data1 = ref([
  "You will learn how to leverage the power of Python to solve tasks.",
  "You will build games and programs that use Python libraries.",
  "You will be able to use Python for your own work problems or personal projects.",
  "You will create a portfolio of Python based projects you can share.",
  "Learn to use Python professionally, learning both Python 2 and Python 3!",
  "Create games with Python, like Tic Tac Toe and Blackjack!",
  "Learn advanced Python features, like the collections module and how to work with timestamps!",
  "Learn to use Object Oriented Programming with classes!",
  "Understand complex topics, like decorators.",
  "Understand how to use both the Jupyter Notebook and create .py files",
  "Get an understanding of how to create GUIs in the Jupyter Notebook system!",
]);
("Build a complete understanding of Python from the ground up!");
</script>

<style lang="css" scoped>
.course-landing-page {
  position: absolute;
}

.rotate-animation {
  display: inline-block;
  width: 100px;
  height: 100px;
  background-color: #3498db;
  animation: rotate180 2s ease-in-out infinite;
}

@keyframes rotate180 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(180deg);
  }
}
</style>
