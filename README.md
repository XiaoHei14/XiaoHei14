<section class="relative w-full min-h-screen flex justify-center items-center bg-violet-600 overflow-hidden p-4">
  <!-- Grid 背景 -->
  <div class="absolute inset-0 z-10">
    <div
      class="absolute inset-0 opacity-20"
      style="
        background-image:
          linear-gradient(#e9d4ff 1px, transparent 1px),
          linear-gradient(90deg, #e9d4ff 1px, transparent 1px);
        background-size: 50px 50px;
      "
    ></div>
    <div
      class="absolute inset-0 opacity-10"
      style="
        background-image: radial-gradient(circle, rgba(255,255,255,0.3) 1px, transparent 1px);
        background-size: 30px 30px;
      "
    ></div>
  </div>

  <!-- 背景圓形 -->
  <div
    class="absolute bottom-0 left-1/2 -translate-x-1/2 w-[1200px] h-[600px] rounded-t-full blur-3xl opacity-80"
    style="
      background: radial-gradient(circle at center bottom, #a684ff 0%, #8e51ff 100%);
    "
  ></div>

  <!-- 內容卡片 -->
  <div class="relative z-10 bg-violet-400/50 backdrop-blur-lg w-full max-w-7xl md:max-w-4xl min-h-screen border border-white/20 rounded-2xl overflow-hidden shadow-2xl">
    <div class="text-white text-center text-4xl font-bold p-6 font-mono">
      <h1>Whoami</h1>
    </div>

    <!-- 頭像與個人資訊 -->
    <div class="flex flex-col sm:flex-row items-center w-full p-4 sm:p-6 gap-6">
      <!-- 頭像 -->
      <div class="relative group flex-shrink-0">
        <div class="relative w-32 h-32 sm:w-36 sm:h-36 bg-gradient-to-br from-indigo-300 to-purple-300 rounded-full flex items-center justify-center border-4 border-white shadow-lg">
          <img src="/chaewon.jpg" alt="Profile Picture" class="rounded-full object-cover w-full h-full" />
        </div>
      </div>

      <!-- 個人資訊 -->
      <div class="flex flex-col justify-center text-center sm:text-left">
        <h1 class="text-2xl sm:text-3xl md:text-4xl font-bold text-white tracking-wide">DaoHui</h1>
        <span class="text-[#b891f5] font-bold cursor-pointer select-none transition-colors duration-300 mt-1">@daohuirealm</span>
        <p class="text-sm sm:text-base text-white/90 mt-2">
          Full Stack Developer & Web Penetration Tester
        </p>
        <p class="text-xs sm:text-sm text-white/80 mt-1 leading-relaxed max-w-xs sm:max-w-md">
          Full Stack Developer with a passion for secure and scalable applications. Skilled in React, Node.js, and cloud platforms, bridging development and penetration testing to create resilient solutions.
        </p>
      </div>
    </div>

    <!-- Skills -->
    <div class="flex flex-col lg:flex-row gap-6 p-5">
      <div class="flex-1">
        <div class="flex items-center mb-3">
          <div class="w-2 h-6 bg-gradient-to-b from-indigo-700 to-purple-700 rounded-full"></div>
          <span class="text-xl sm:text-2xl font-bold ml-3">My Skills</span>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
          <div class="skill-card bg-violet-400/60 p-3 sm:p-4 rounded-lg border border-white/20 text-center">JavaScript</div>
          <div class="skill-card bg-violet-400/60 p-3 sm:p-4 rounded-lg border border-white/20 text-center">TypeScript</div>
          <div class="skill-card bg-violet-400/60 p-3 sm:p-4 rounded-lg border border-white/20 text-center">React</div>
          <!-- 可依序添加其他技能 -->
        </div>
      </div>

      <!-- Social -->
      <div class="flex-1">
        <div class="flex items-center mb-3">
          <div class="w-2 h-6 bg-gradient-to-b from-indigo-700 to-purple-700 rounded-full"></div>
          <span class="text-xl sm:text-2xl font-bold ml-3">Social</span>
        </div>
        <div class="grid grid-cols-3 gap-3 sm:grid-cols-3 md:grid-cols-1">
          <a href="https://github.com/daohuirealm" class="flex items-center justify-center md:justify-start p-3 bg-violet-400/60 rounded-full border border-white/20 hover:bg-violet-500/70 transition-colors duration-200 gap-2">
            GitHub
          </a>
          <a href="https://twitter.com/daohuirealm" class="flex items-center justify-center md:justify-start p-3 bg-violet-400/60 rounded-full border border-white/20 hover:bg-violet-500/70 transition-colors duration-200 gap-2">
            Twitter
          </a>
          <a href="https://www.linkedin.com/in/daohui/" class="flex items-center justify-center md:justify-start p-3 bg-violet-400/60 rounded-full border border-white/20 hover:bg-violet-500/70 transition-colors duration-200 gap-2">
            LinkedIn
          </a>
        </div>
      </div>
    </div>
  </div>
</section>
