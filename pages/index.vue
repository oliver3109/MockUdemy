<template>
  <main>
    <!-- 顶部固定 -->
    <div class="fixed top-0 w-full bg-slate-900 h-16 z-20 px-5 py-2">
      <div class="text-white font-bold">
        The Complete Python Bootcamp From Zero to Hero in Python
      </div>
      <div class="flex items-center">
        <div class="text-amber-500 text-sm mr-2">4.6</div>
        <Icon name="uil:star" class="text-amber-500 mr-2"></Icon>
        <div
          class="text-violet-300 text-sm underline underline-offset-1 cursor-pointer"
        >
          (523092 个评分)
        </div>
        <div class="text-white text-sm ml-2">1986546 名学生</div>
      </div>
    </div>

    <!-- 第一部分 -->
    <div class="bg-slate-900 w-full h-96 py-6">
      <div class="mx-8">
        <div
          class="desktop:max-w-6xl laptop:max-w-5xl tablet:max-w-4xl mx-auto"
        >
          <div class="desktop:max-w-3xl laptop:max-w-2xl tablet:max-w-xl">
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
            <div class="text-md text-white font-normal mb-5 ml-6">
              Learn Python like a Professional Start from the basics and go all
              the way to creating your own applications and games
            </div>

            <!-- 创建者 -->
            <div class="text-white text-sm mb-5 ml-6">
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
            <div class="text-white text-sm mb-5 ml-6">
              <span class="flex items-center">
                <Icon
                  name="uil:exclamation-octagon"
                  style="color: white; font-size: 16px"
                  class="mr-2"
                ></Icon>
                上次更新时间：2023/7
                <span class="flex items-center ml-4">
                  <Icon
                    name="uil:globe"
                    style="color: white; font-size: 16px"
                    class="mr-2"
                  ></Icon>
                  英语</span
                >
                <span class="flex items-center ml-4">
                  <Icon
                    name="uil:file-landscape-alt"
                    style="color: white; font-size: 20px"
                    class="mr-2"
                  ></Icon>
                  简体中文 [自动], 英语 [自动] ,</span
                >
              </span>
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
                <div class="underline underline-offset-1 text-stone-600">
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
                <div class="text-sm text-stone-600">学习者</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- 第二部分 -->
    <div class="py-6">
      <div class="mx-8">
        <div
          class="desktop:max-w-6xl laptop:max-w-5xl tablet:max-w-4xl mx-auto"
        >
          <div class="desktop:max-w-3xl laptop:max-w-2xl tablet:max-w-xl">
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
                      <div class="text-slate-600 text-sm">
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

              <div class="mt-2">
                <details
                  class="group marker:content-['']"
                  v-for="item of data2"
                >
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

                      <span class="text-stone-600 text-md">{{ item }}</span>
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

            <!-- 要求 -->
            <div class="mt-6 ml-6">
              <div class="text-2xl font-bold mb-6">要求</div>
              •
              <span class="text-sm"
                >Access to a computer with an internet connection.</span
              >
            </div>

            <!-- 描述 -->
            <div class="mt-8 ml-6">
              <div class="text-2xl font-bold mb-6">描述</div>
              <div class="text-sm">
                <p class="mb-2">
                  <strong
                    >Become a Python Programmer and learn one of employer's most
                    requested skills of 2023!</strong
                  ><br />
                </p>
                <p class="mb-2">
                  This is the
                  <strong
                    >most comprehensive, yet straight-forward, course for the
                    Python programming language on Udemy!</strong
                  >
                  Whether you have never programmed before, already know basic
                  syntax, or want to learn about the advanced features of
                  Python, this course is for you! In this course we
                  will&nbsp;<strong>teach you Python 3. </strong>
                </p>
                <p class="mb-2">
                  With <strong>over 100 lectures</strong> and more than 21 hours
                  of video this comprehensive course leaves no stone unturned!
                  This course includes quizzes, tests, coding exercises and
                  homework assignments as well as 3 major projects to create a
                  Python project portfolio!
                </p>
                <p class="mb-2">
                  <strong
                    >Learn how to use Python for real-world tasks, such as
                    working with PDF Files, sending emails, reading Excel files,
                    Scraping websites for informations, working with image
                    files, and much more!</strong
                  >
                </p>
                <p class="mb-2">
                  This course will teach you Python in a practical manner, with
                  every lecture comes a full coding screencast and a
                  corresponding code notebook! Learn in whatever manner is best
                  for you!
                </p>
                <p class="mb-2">
                  We will start by helping you get Python installed on your
                  computer, regardless of your operating system, whether its
                  Linux, MacOS, or Windows, we've got you covered.
                </p>
                <p class="mb-2">
                  We cover a wide variety of topics, including:
                </p>
                <ul class="list-disc ml-10 mb-2 font-extralight">
                  <li><p>Command Line Basics</p></li>
                  <li><p>Installing Python</p></li>
                  <li><p>Running Python Code</p></li>
                  <li><p>Strings</p></li>
                  <li><p>Lists&nbsp;</p></li>
                  <li><p>Dictionaries</p></li>
                  <li><p>Tuples</p></li>
                  <li><p>Sets</p></li>
                  <li><p>Number Data Types</p></li>
                  <li><p>Print Formatting</p></li>
                  <li><p>Functions</p></li>
                  <li><p>Scope</p></li>
                  <li><p>args/kwargs</p></li>
                  <li><p>Built-in Functions</p></li>
                  <li><p>Debugging and Error Handling</p></li>
                  <li><p>Modules</p></li>
                  <li><p>External Modules</p></li>
                  <li><p>Object Oriented Programming</p></li>
                  <li><p>Inheritance</p></li>
                  <li><p>Polymorphism</p></li>
                  <li><p>File I/O</p></li>
                  <li><p>Advanced Methods</p></li>
                  <li><p>Unit Tests</p></li>
                  <li><p>and much more!</p></li>
                </ul>
                <p class="mb-2">
                  <strong
                    >You will get lifetime access to over 100 lectures plus
                    corresponding Notebooks for the lectures! </strong
                  ><br />
                </p>
                <p class="mb-2">
                  This course comes with a
                  <strong>30 day money back guarantee!</strong> If you are not
                  satisfied in any way, you'll get your money back. Plus you
                  will keep access to the Notebooks as a thank you for trying
                  out the course!
                </p>
                <p class="mb-2">
                  <strong
                    >So what are you waiting for? Learn Python in a way that
                    will advance your career and increase your knowledge, all in
                    a fun and practical way!</strong
                  >
                </p>
              </div>
            </div>

            <!-- 要求 -->
            <div class="mt-6 ml-6">
              <div class="text-2xl font-bold mb-4">此课程面向哪些人：</div>
              <ul class="list-disc text-sm font-light ml-10">
                <li>Beginners who have never programmed before.</li>
                <li>Programmers switching languages to Python.</li>
                <li>
                  Intermediate Python programmers who want to level up their
                  skills!
                </li>
              </ul>
            </div>

            <!-- 精选评论 -->
            <div class="border ml-6 p-5 mt-12">
              <div class="text-2xl font-bold mb-4">精选评论</div>
              <div class="flex">
                <img
                  src="https://img-c.udemycdn.com/user/200_H/101610246_6b5d_3.jpg"
                  class="rounded-full size-16"
                />
                <div class="flex flex-col ml-3">
                  <div class="font-bold">Ken K.</div>
                  <div class="text-sm text-stone-500">9 门课程</div>
                  <div class="text-sm text-stone-500">2 条评论</div>
                </div>
              </div>
              <div class="text-sm text-stone-500 mt-4">
                Everything on this course is a goldmine except for the GUI since
                it's specific for Jupyter Notebooks and it's missing the video
                for GUI Events. Still it was a nice introduction to GUI. Don't
                let that disappoint you though. THIS IS A MUST HAVE COURSE. I
                have already recommended it to few people and always will. Do
                yourself a favor and do this course if you want to learn Python
                3. Thank you so much for this course, Jose-sensei!!
              </div>

              <div class="text-xs text-stone-500 mt-6">此评论是否有用？</div>

              <div class="flex gap-2 items-center mt-2">
                <div
                  class="rounded-full border border-black size-10 flex items-center justify-center"
                >
                  <Icon name="uil:thumbs-up" style="font-size: 22px"></Icon>
                </div>

                <div
                  class="rounded-full border border-black size-10 flex items-center justify-center"
                >
                  <Icon name="uil:thumbs-down" style="font-size: 22px"></Icon>
                </div>

                <div
                  class="text-sm underline underline-offset-2 text-stone-600 cursor-pointer"
                >
                  举报
                </div>
              </div>
            </div>

            <!-- 学生还购买了 -->
            <div class="mt-6 ml-6">
              <div class="text-2xl font-bold mb-4">学生还购买了</div>
              <div>
                <div
                  class="flex border-b border-stone-300 pb-4 mb-6"
                  v-for="item in 5"
                >
                  <div>
                    <img
                      src="https://img-c.udemycdn.com/course/50x50/2776760_f176_10.jpg"
                      width="64"
                      height="64"
                      loading="lazy"
                    />
                  </div>

                  <div class="grow text-sm ml-3">
                    <a class="font-md font-bold"
                      >100 Days of Code: The Complete Python Pro Bootcamp</a
                    >
                    <div class="flex mt-2">
                      <div
                        class="flex items-center justify-center bg-yellow-200"
                      >
                        <div class="px-2 text-xs">热门课程</div>
                      </div>
                      <div>
                        <span class="text-green-900 ml-3">总共 56.5 小时</span
                        ><span class="text-stone-600"> · 更新日期 2024/11</span>
                      </div>
                    </div>
                  </div>

                  <div class="flex gap-4">
                    <div class="text-sm font-bold">4.7</div>
                    <div class="flex">
                      <Icon name="uil:users-alt"></Icon>
                      <span class="text-xs ml-1">1,439,152</span>
                    </div>
                    <div>
                      <div class="text-sm font-bold">US$13.99</div>
                      <div class="line-through text-xs text-stone-500">
                        US$124.99
                      </div>
                    </div>
                    <div
                      class="size-10 border border-black rounded-full flex justify-center items-center"
                    >
                      <Icon
                        name="uil:heart"
                        style="color: black; font-size: 20px"
                      ></Icon>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- 常见购买搭配 -->
            <div class="border ml-6 p-5 mt-12">
              <div class="text-2xl font-bold mb-4">常见购买搭配</div>

              <!-- 课程列表 -->
              <div class="space-y-4">
                <!-- 单个课程 -->
                <div class="flex items-start border-b pb-4" v-for="item in 3">
                  <!-- 左侧图片 -->
                  <div class="w-48 h-24 flex-shrink-0 border">
                    <img
                      src="https://img-c.udemycdn.com/course/240x135/567828_67d0.jpg"
                      class="object-contain w-full h-full"
                    />
                  </div>

                  <!-- 右侧内容 -->
                  <div class="flex-1 pl-4">
                    <h3 class="text-sm font-semibold text-gray-900">
                      The Complete Python Bootcamp From Zero to Hero in Python
                    </h3>
                    <p class="text-xs text-gray-500">
                      Jose Portilla, Pierian Training
                    </p>
                    <div class="flex items-center text-sm mt-1">
                      <span class="text-black text-xs font-bold">4.6</span>
                      <span class="text-gray-500 ml-1 text-xs">(523,003)</span>
                    </div>
                    <span
                      class="flex w-16 text-xs bg-purple-800 font-medium text-purple-100 px-2 py-1 rounded mt-1 items-center justify-center"
                    >
                      <Icon
                        name="uil:check-circle"
                        class="mr-1"
                        style="color: white"
                      ></Icon
                      >高级
                    </span>
                  </div>

                  <!-- 价格 -->
                  <div class="text-right">
                    <div class="text-sm text-gray-900 font-bold">US$22.99</div>
                    <div class="text-xs text-gray-500 line-through">
                      US$199.99
                    </div>
                  </div>
                </div>
              </div>

              <!-- 总计 -->
              <div class="flex justify-between items-center mt-6">
                <div class="text-sm">
                  总计：
                  <span class="text-lg font-bold text-gray-900">US$56.97</span>
                  <span class="text-sm text-gray-500 line-through">
                    US$499.97
                  </span>
                </div>
                <button
                  class="bg-purple-600 text-white px-6 py-2 rounded text-sm hover:bg-purple-700"
                >
                  全部添加至购物车
                </button>
              </div>
            </div>

            <!-- 讲师 -->
            <div class="mt-12 ml-6">
              <div class="text-2xl font-bold mb-6">讲师</div>

              <div>
                <div class="flex flex-col items-start">
                  <!-- 用户名和职位 -->
                  <h2
                    class="text-lg font-bold text-violet-600 underline underline-offset-4"
                  >
                    Jose Portilla
                  </h2>
                  <p class="text-sm text-gray-500">
                    Head of Data Science at Pierian Training
                  </p>
                </div>

                <div class="flex mt-3">
                  <!-- 头像 -->
                  <img
                    src="https://img-c.udemycdn.com/user/200_H/9685726_67e7_4.jpg"
                    alt="Jose Portilla"
                    class="w-24 h-24 rounded-full"
                  />

                  <!-- 统计数据 -->
                  <div class="flex flex-col items-start justify-around ml-4">
                    <!-- 评分 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:star"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">4.6 讲师评分</span>
                    </div>
                    <!-- 条评论 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:medal"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">1224340 条评论</span>
                    </div>
                    <!-- 名学生 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:users-alt"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">4077344 名学生</span>
                    </div>
                    <!-- 门课程 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:play-circle"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">87 门课程</span>
                    </div>
                  </div>
                </div>

                <p class="text-xs text-gray-700 mt-4 leading-relaxed">
                  Jose Marcial Portilla has a BS and MS in Mechanical
                  Engineering from Santa Clara University and years of
                  experience as a professional instructor and trainer for Data
                  Science, Machine Learning and Python Programming. He has
                  publications and patents in various fields such as
                  microfluidics, materials science, and data science. Over the
                  course of his career he has developed a skill set in analyzing
                  data and he hopes to use his experience in teaching and data
                  science to help other people learn the power of programming,
                  the ability to analyze data, and the skills needed to present
                  the data in clear and beautiful visualizations. Currently he
                  works as the Head of Data Science for Pierian Training and
                  provides in-person data science and python programming
                  training courses to employees working at top companies,
                  including General Electric, Cigna, SalesForce, Starbucks,
                  McKinsey and many more. Feel free to check out the website
                  link to find out more information about training offerings.
                </p>
              </div>

              <div class="mt-8">
                <div class="flex flex-col items-start">
                  <!-- 用户名和职位 -->
                  <h2
                    class="text-lg font-bold text-violet-600 underline underline-offset-4"
                  >
                    Pierian Training
                  </h2>
                  <p class="text-sm text-gray-500">
                    Data Science and Machine Learning Training
                  </p>
                </div>

                <div class="flex mt-3">
                  <!-- 头像 -->
                  <img
                    src="https://img-c.udemycdn.com/user/200_H/265589972_dca1.jpg"
                    alt="Jose Portilla"
                    class="w-24 h-24 rounded-full"
                  />

                  <!-- 统计数据 -->
                  <div class="flex flex-col items-start justify-around ml-4">
                    <!-- 评分 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:star"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">4.6 讲师评分</span>
                    </div>
                    <!-- 条评论 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:medal"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">1224340 条评论</span>
                    </div>
                    <!-- 名学生 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:users-alt"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">4077344 名学生</span>
                    </div>
                    <!-- 门课程 -->
                    <div class="flex items-center text-gray-600">
                      <Icon
                        name="uil:play-circle"
                        style="color: black"
                        class="mr-4"
                      ></Icon>
                      <span class="text-sm">94 门课程</span>
                    </div>
                  </div>
                </div>

                <p class="text-xs text-gray-700 mt-4 leading-relaxed">
                  Pierian Training stands as a premier provider in the realms of
                  Data Science and Machine Learning education, offering both
                  in-person and virtual instructor-led training tailored for
                  enterprises. Explore our comprehensive profile to discover a
                  wide range of courses designed to enhance your professional
                  skills and organizational capabilities. Feel free to contact
                  us if you have any questions in the link on our profile!
                </p>
              </div>
            </div>

            <!-- 学生还购买了 -->
            <div class="mt-8 ml-6">
              <div class="text-2xl font-bold mb-4 flex items-center">
                <Icon name="uil:star" class="text-amber-600 mr-2"></Icon> 4.6
                课程评分 · 523K 评分
              </div>

              <div class="flex flex-wrap">
                <div
                  class="h-72 border-t border-stone-200 even:ml-auto mb-2"
                  style="width: calc(50% - 20px)"
                  v-for="item in 4"
                >
                  <div class="flex mt-6">
                    <div
                      class="bg-black w-10 h-10 text-white rounded-full font-bold flex items-center justify-center"
                    >
                      JB
                    </div>
                    <div class="ml-4 flex justify-between flex-1">
                      <div class="flex flex-col w-full">
                        <div class="font-bold">Jason B.</div>
                        <div class="text-xs mt-auto">1周前</div>
                      </div>
                      <Icon
                        name="uil:ellipsis-v"
                        style="color: black; font-size: 30px"
                      ></Icon>
                    </div>
                  </div>

                  <div class="mt-5 text-stone-500">
                    Other than frequently having to pause or rewind because I
                    couldn't practice in the Workspaces and keep up with the
                    lectures, this was a well done course with lots of useful
                    information.
                  </div>

                  <div class="text-xs text-stone-500 mt-10">有帮助吗？</div>
                </div>
              </div>
            </div>

            <div class="ml-6">
              <div
                class="border border-black w-36 px-6 py-2 text-sm hover:bg-stone-200 cursor-pointer"
              >
                显示所有评论
              </div>
            </div>

            <div class="mt-8 ml-6">
              <!-- 标题 -->
              <h2 class="text-2xl font-bold text-purple-700 mb-4">
                Jose Portilla <span class="text-black">的更多课程</span>
              </h2>

              <!-- 课程列表 -->
              <div class="flex gap-3">
                <div
                  class="bg-white rounded-lg overflow-hidden flow"
                  v-for="iten in 3"
                >
                  <!-- 图片部分 -->
                  <img
                    src="https://img-c.udemycdn.com/course/240x135/762616_7693_3.jpg"
                    class="h-40 w-60 object-cover border"
                  />

                  <!-- 课程信息部分 -->
                  <div class="p-4">
                    <h3 class="text-lg font-semibold text-gray-800 truncate">
                      The Complete SQL Bootcamp: Go from Zero to Hero
                    </h3>
                    <p class="text-sm text-gray-600 mb-2">
                      Jose Portilla, Pierian Training
                    </p>

                    <!-- 评分和评价 -->
                    <div class="flex items-center text-balck text-sm mb-2">
                      <span class="text-xs font-bold">4.7</span>
                      <span class="text-gray-600 ml-1"> (47 条评价) </span>
                    </div>

                    <!-- 课程时长 -->
                    <p class="text-xs text-gray-600 mb-2">
                      总共 9 小时 · 83 个讲座 · 所有级别
                    </p>

                    <!-- 价格信息 -->
                    <div class="flex items-center">
                      <span class="text-lg font-bold text-black mr-2">
                        US¥16.99
                      </span>
                      <span class="text-sm line-through text-gray-400">
                        US$159.99
                      </span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- 右侧浮动 -->
    <div class="">
      <div
        :class="
          isActive
            ? 'bg-white w-80 ml-auto fixed top-4 left-2/3 z-20 border border-white shadow-md'
            : 'bg-white w-80 ml-auto absolute top-28 left-2/3 z-10 border border-white shadow-md'
        "
      >
        <div class="flex items-center justify-center" v-show="!isActive">
          <img
            src="https://img-c.udemycdn.com/course/240x135/567828_67d0.jpg"
            class="w-full min-h-48 max-h-48"
          />
          <div
            class="absolute flex flex-col left-0 right-0 items-center justify-center z-10 bg-gradient-to-t from-gray-900 w-full min-h-48 h-48"
          >
            <div
              class="size-16 bg-white rounded-full flex justify-center items-center"
            >
              <Icon name="uil:youtube" style="font-size: 30px"></Icon>
            </div>

            <div class="text-white absolute bottom-3">预览本课程</div>
          </div>
        </div>
        <div class="flex border-b">
          <div
            class="w-full h-12 flex justify-center items-center font-bold border-b-2 border-black"
          >
            个人
          </div>
          <div class="w-full h-12 flex justify-center items-center">团队</div>
        </div>
        <div>
          <div class="flex items-center px-9 mt-3">
            <Icon name="uil:check-circle" class="text-violet-600"></Icon>
            <span class="text-sm text-stone-600 ml-2"
              >此高级课程包含在方案中</span
            >
          </div>
          <div class="px-9">
            <span class="text-2xl font-bold">US$22.99</span>
            <span class="text-sm text-stone-600 line-through ml-2"
              >US$199.99</span
            >
            <span class="text-md text-stone-700 ml-2">折扣88% 折扣</span>
          </div>

          <div class="flex items-center px-9 mt-1">
            <Icon name="uil:clock-nine" class="text-red-600"></Icon>
            <span class="text-sm text-red-600 ml-2"
              >此优惠价格仅剩 18 小时！</span
            >
          </div>
          <div
            class="mx-8 h-12 bg-violet-600 flex items-center justify-center text-white mt-4 hover:bg-violet-800 cursor-pointer"
          >
            添加至购物车
          </div>
          <div class="text-xs text-stone-500 text-center mt-4">
            30 天退款保证
          </div>
          <div class="text-xs text-stone-500 text-center mt-4">
            完整的永久访问权
          </div>

          <div class="flex mx-8 text-sm justify-around mt-4">
            <div class="underline underline-offset-2 flow">分享</div>
            <div class="underline underline-offset-2 flow">
              将该课程作为礼物赠送
            </div>
            <div class="underline underline-offset-2 flow">使用优惠券</div>
          </div>

          <div class="mx-8 flex border border-black items-center h-10 mt-6">
            <input
              type="text"
              class="grey text-slate-600 border-none outline-none text-sm pl-4 grow"
              placeholder="输入优惠卷"
            />
            <div
              class="bg-black text-white w-20 h-full flex items-center justify-center"
            >
              应用
            </div>
          </div>

          <div
            class="text-xs or--separator flex items-center mx-8 text-stone-500 py-4"
          >
            或
          </div>

          <div class="mx-8">
            <span class="text-md"> 订阅 Udemy 的热门课程 </span>
            <span class="text-sm">
              通过个人方案订阅，获得这门课程以及 12000
              多门我们最受好评的课程。<span
                class="underline underline-offset-1 cursor-pointer text-violet-600"
                >了解更多</span
              >
            </span>
          </div>

          <div
            class="mx-8 h-12 bg-white flex items-center justify-center text-black border border-black mt-2 hover:bg-stone-200 cursor-pointer"
          >
            免费使用个人方案
          </div>
          <div class="text-xs text-stone-500 text-center mt-2">
            试用后每月 US$20.00 起售
          </div>

          <div class="text-xs text-stone-500 text-center mt-2 pb-6">
            随时取消
          </div>
        </div>
      </div>
    </div>
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
  "Build a complete understanding of Python from the ground up!",
]);

const data2 = ref([
  "Course Overview",
  "Python Setup",
  "Python Object and Data Structure Basics",
  "Python Comparison Operators",
  "Python Statements",
  "Methods and Functions",
  "Milestone Project - 1",
  "Object Oriented Programming",
  "Modules and Packages",
  "Errors and Exceptions Handling",
  "Milestone Project - 2",
  "Python Decorators",
  "Advanced Python Modules",
  "Web Scraping with Python",
  "Working with PDFs and Spreadsheet CSV Files",
  "Emails with Python",
  "Final Capstone Python Project",
  "Advanced Python Objects and Data Structures",
  "Bonus Material - Introduction to GUIs",
  "APPENDIX: OLDER PYTHON 2 MATERIAL",
  "BONUS SECTION: THANK YOU!",
]);

const isActive = ref(false);

const handleScroll = () => {
  // 判断滚动位置，比如滚动到 300px 切换样式
  isActive.value = window.scrollY > 300;
};

onMounted(() => {
  // 添加滚动事件监听器
  window.addEventListener("scroll", handleScroll);
});

onUnmounted(() => {
  // 移除滚动事件监听器，防止内存泄漏
  window.removeEventListener("scroll", handleScroll);
});
</script>

<style lang="css" scoped>
.or--separator::before,
.or--separator::after {
  content: "";
  flex: 1;
  border-bottom: 1px solid #d1d7dc;
}

.or--separator::before {
  margin-right: 8px;
}
.or--separator::after {
  margin-left: 8px;
}
</style>
