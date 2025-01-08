这是一个用来做个人网站的项目，最近想借鉴AnthonyFu的antfu.me个人网站的风格，来搭建一个属于我自己的个人网站，当做自己的网络名片，以及学习技术的文档总结和自己的思考等一系列内容
* 技术栈
  * (优先) **Vue + Vite**
  * TypeScript
  * Tailwind CSS
  * pinia
* 
* [antfu.me](https://antfu.me) 是 Anthony Fu 的个人博客网站，Anthony Fu 是 Vue.js 生态的活跃贡献者，因此他的网站很可能使用了现代化的前端技术栈。以下是对该网站可能使用的技术栈的解析：

### 1. **前端框架**
   - **Vue.js**  
     Anthony Fu 是 Vue.js 的核心团队成员，因此他的网站很可能基于 Vue.js 构建。Vue.js 是一个轻量级、高性能的前端框架，适合构建单页面应用（SPA）或静态网站。
### 2. **静态站点生成器**
   - **VitePress** 或 **VuePress**  
     该网站是一个内容为主的博客，可能使用了 Vue 生态的静态站点生成器，如 [VitePress](https://vitepress.dev/) 或 [VuePress](https://vuepress.vuejs.org/)。这些工具支持 Markdown 编写内容，并生成静态网站。
     - VitePress 是 VuePress 的下一代版本，基于 Vite 构建，速度更快。
     - 网站的风格和功能（如暗黑模式、代码高亮）与 VitePress 的默认特性非常吻合。
### 3. **构建工具**
   - **Vite**  
     Vite 是一个现代化的前端构建工具，支持快速开发和构建。VitePress 就是基于 Vite 构建的，因此该网站很可能使用了 Vite 作为构建工具。
### 4. **UI 组件库**
   - **自定义组件**  
     网站的风格简洁，可能没有使用成熟的 UI 组件库（如 Element Plus 或 Ant Design），而是基于 Vue.js 自定义了组件。
   - **图标**  
     网站使用了大量的图标，可能使用了 [Iconify](https://iconify.design/) 或 [unplugin-icons](https://github.com/antfu/unplugin-icons)（Anthony Fu 开发的图标插件）。
### 5. **样式**
   - **Tailwind CSS** 或 **UnoCSS**  
     网站的样式可能使用了 [Tailwind CSS](https://tailwindcss.com/) 或 [UnoCSS](https://github.com/unocss/unocss)（Anthony Fu 开发的原子化 CSS 引擎）。这些工具可以帮助快速构建现代化的 UI。
   - **暗黑模式**  
     网站支持暗黑模式，可能是通过 CSS 变量或 Tailwind/UnoCSS 的暗黑模式功能实现的。
### 6. **代码高亮**
   - **Shiki** 或 **Prism**  
     网站中的代码块有语法高亮，可能使用了 [Shiki](https://shiki.matsu.io/) 或 [Prism](https://prismjs.com/)。Shiki 是一个基于 VSCode 语法高亮引擎的工具，支持多种主题。
### 7. **动画与交互**
   - **GSAP** 或 **原生 CSS 动画**  
     网站中的一些动画效果（如页面切换、按钮交互）可能使用了 [GSAP](https://greensock.com/gsap/) 或原生 CSS 动画。
   - **Vue Transition**  
     Vue.js 的 `<transition>` 组件可能被用于页面切换或元素动画。
### 8. **部署**
   - **Netlify** 或 **Vercel**  
     网站可能部署在 [Netlify](https://www.netlify.com/) 或 [Vercel](https://vercel.com/) 上，这些平台支持静态网站的快速部署和自动化构建。
   - **GitHub Actions**  
     如果使用了 CI/CD，可能配置了 GitHub Actions 来自动化构建和部署流程。
### 9. **其他工具**
   - **Markdown**  
     博客内容可能是用 Markdown 编写的，VitePress 或 VuePress 支持将 Markdown 转换为 HTML。
   - **RSS 订阅**  
     网站可能提供了 RSS 订阅功能，这是静态站点生成器的常见特性。
### 总结
该网站的技术栈可能包括：
- **核心框架**：Vue.js
- **静态站点生成器**：VitePress 或 VuePress
- **构建工具**：Vite
- **样式**：Tailwind CSS 或 UnoCSS
- **图标**：Iconify 或 unplugin-icons
- **代码高亮**：Shiki 或 Prism
- **部署**：Netlify 或 Vercel
Anthony Fu 是前端工具链的专家，因此他的网站可能还使用了一些他个人开发或推荐的工具（如 UnoCSS、unplugin-icons 等）。如果需要更详细的技术细节，可以查看网站的源码（如果公开）或网络请求分析。