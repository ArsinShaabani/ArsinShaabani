<!--
  Arsin Shaabani — GitHub Profile README
  · Lives in: ArsinShaabani/ArsinShaabani (rendered on the profile page)
  · Theme: tokyo-night (dark) with cyan/purple accents
-->

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=230&section=header&text=Arsin%20Shaabani&fontSize=50&fontColor=ffffff&desc=Founder%20of%20ARSINSOFT%20%C2%B7%20AI%20%C3%97%20Mechatronics%20%C2%B7%20Open%20Source&descSize=17&descAlignY=70&anim=blur)

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00D9FF&center=true&vCenter=true&width=800&height=50&lines=Hello%2C+I%27m+Arsin+Shaabani;Building+PromptSeal+%E2%80%94+regression+testing+for+LLMs;AI+%C3%97+3D+Wearable+Devices;Native+Windows+apps+with+Qt+%2F+C%2B%2B;Mechatronics+%26+Robotics;Persian+(fa_IR)+localization" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/ArsinShaabani"><img src="https://komarev.com/ghpvc/?username=ArsinShaabani&style=for-the-badge&color=302b63&labelColor=0f0c29&label=PROFILE+VIEWS" alt="Profile views"/></a>
  <a href="https://github.com/ArsinShaabani?tab=followers"><img src="https://img.shields.io/github/followers/ArsinShaabani?style=for-the-badge&logo=github&color=302b63&labelColor=0f0c29&label=FOLLOWERS" alt="Followers"/></a>
  <a href="https://github.com/ArsinShaabani?tab=repositories"><img src="https://img.shields.io/github/stars/ArsinShaabani?affiliations=OWNER&style=for-the-badge&logo=github&color=302b63&labelColor=0f0c29&label=STARS" alt="Stars"/></a>
  <a href="https://pypi.org/project/promptseal/"><img src="https://img.shields.io/pypi/v/promptseal?style=for-the-badge&logo=pypi&color=302b63&labelColor=0f0c29&label=PROMPTSEAL" alt="PromptSeal on PyPI"/></a>
</p>

<p align="center">
  <a href="https://app.daily.dev/arsinshaabani"><img src="https://api.daily.dev/devcards/v2/oyPYtM2f9JzYjAya4o8de.png?type=wide&r=xsm" width="652" alt="Arsin Shaabani's dev card on daily.dev"/></a>
</p>

---

## ⚡ What I do

| 🔬 **AI & Computer Vision** | 🖥 **Native Desktop Apps** | ⚡ **Hardware & Electronics** |
|:---:|:---:|:---:|
| LLM evaluation & prompt testing · YOLO pipelines · multispectral imagery | Qt 6 / C++ / MSVC · Windows porting & packaging · clean RTL Persian (`fa_IR`) | EEPROM & Flash programming · mechatronics & robotics · PC/laptop repair |
| <div dir="rtl">ارزیابی LLM و تست پرامپت · پایپ‌لاین YOLO · تصویربرداری مولتی‌اسپکترال</div> | <div dir="rtl">Qt 6 و ++C و MSVC · پورت و بسته‌بندی ویندوزی · بومی‌سازی فارسی</div> | <div dir="rtl">پروگرام EEPROM و Flash · مکاترونیک و رباتیک · تعمیرات سخت‌افزار</div> |

---

## 🦭 Flagship — PromptSeal

**Regression testing for prompts, agents, and models.** Know what breaks *before* your users do.

> Changed one word in a system prompt? Swapped GPT-4o for a shiny open-weights model? PromptSeal records how your prompts **should** behave, then re-verifies it on every change — in your terminal and in CI.

```text
baseline (gpt-4o):       100% ██████████
candidate (new model):    87% ████████▁▁  ❌ REGRESSION: pii-guard now leaks the invoice total
                                    ✅ IMPROVEMENT: refund-tone is warmer
                                    💰 new model is 14× cheaper — passes 96% of cases
```

| | |
|---|---|
| 🧪 **YAML cases** | 13 built-in assertions: `contains`, `regex`, `json_valid`, `llm_judge`, `max_latency_s`, `max_cost_usd`, … |
| 🔁 **Seal → Diff** | `promptseal run --save-baseline`, change a prompt/model/provider, then `promptseal diff` — every case classified as regression / improvement / stable |
| 🚦 **CI gate** | [promptseal-action](https://github.com/ArsinShaabani/promptseal-action) posts a markdown report on the PR and fails the build on regressions |
| 🌐 **Any provider** | Anything OpenAI-compatible — OpenAI, OpenRouter, Ollama, vLLM — plus a zero-config offline mock |
| 🔒 **Local-first** | Runs are plain JSON in `.promptseal/` — your prompts never leave your machine |
| 🌍 **Bilingual** | Docs & full tutorial in English and فارسی — setup to first green seal in ~2 min |

[![PyPI](https://img.shields.io/pypi/v/promptseal?style=flat-square&logo=pypi&label=PyPI)](https://pypi.org/project/promptseal/)
[![Python](https://img.shields.io/pypi/pyversions/promptseal?style=flat-square&logo=python&label=Python)](https://pypi.org/project/promptseal/)
[![License](https://img.shields.io/github/license/ArsinShaabani/promptseal?style=flat-square&label=License)](https://github.com/ArsinShaabani/promptseal/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/ArsinShaabani/promptseal?style=flat-square&logo=github&label=Stars)](https://github.com/ArsinShaabani/promptseal/stargazers)
[![Action](https://img.shields.io/badge/GitHub_Action-promptseal--action%40v1-2088FF?style=flat-square&logo=githubactions)](https://github.com/ArsinShaabani/promptseal-action)
[![Docs](https://img.shields.io/badge/Docs-TUTORIAL.md-302b63?style=flat-square)](https://github.com/ArsinShaabani/promptseal/blob/main/TUTORIAL.md)

---

## 🛠 Featured — IMSProg: Windows Portable + Persian Edition

A curated fork of [bigbigmdm/IMSProg](https://github.com/bigbigmdm/IMSProg) — the open-source GUI programmer for I2C/SPI/MicroWire EEPROM & Flash chips:

| | |
|---|---|
| 🪟 **Windows port** | MSVC 2022 + Qt 6.9 build with MSVC compatibility fixes (VLA, pointer arithmetic, winsock include order) and vendored `libusb` & `libftdi` |
| 🇮🇷 **Persian translation** | Complete `fa_IR` translation of all three apps (475 strings), character-verified |
| 📦 **Portable releases** | Zip-and-run builds — no installer needed; bilingual README inside every package |

[![Release](https://img.shields.io/github/v/release/ArsinShaabani/IMSProg?style=flat-square&color=success&label=Release)](https://github.com/ArsinShaabani/IMSProg/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%20x64-0078D6?style=flat-square&logo=windows11&logoColor=white)](https://github.com/ArsinShaabani/IMSProg/releases/latest)
[![Qt 6](https://img.shields.io/badge/Qt-6.9-41CD52?style=flat-square&logo=qt&logoColor=white)](https://github.com/ArsinShaabani/IMSProg)
[![License](https://img.shields.io/github/license/ArsinShaabani/IMSProg?style=flat-square&label=License)](https://github.com/ArsinShaabani/IMSProg/blob/main/LICENSE)
[![Downloads](https://img.shields.io/github/downloads/ArsinShaabani/IMSProg/total?style=flat-square&color=orange&label=Downloads)](https://github.com/ArsinShaabani/IMSProg/releases)

<div dir="rtl">

**فارک منتخب من از IMSProg** (برنامهٔ گرافیکی متن‌باز برای پروگرام کردن چیپ‌های EEPROM و Flash):
پورت کامل برای ویندوز با MSVC و Qt 6.9، ترجمهٔ کامل فارسی هر سه برنامه (با بررسی دقیق کاراکترها)، و ریلیزهای پرتابلِ «دانلود کن و اجرا کن» بدون نیاز به نصب.

</div>

---

## 🚀 My repositories / مخازن من

<p align="center">
  <a href="https://github.com/ArsinShaabani/promptseal"><img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=ArsinShaabani&amp;repo=promptseal&amp;theme=tokyonight&amp;hide_border=true" width="49%" alt="promptseal"/></a>
  <a href="https://github.com/ArsinShaabani/promptseal-action"><img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=ArsinShaabani&amp;repo=promptseal-action&amp;theme=tokyonight&amp;hide_border=true" width="49%" alt="promptseal-action"/></a>
  <br/>
  <a href="https://github.com/ArsinShaabani/M3FD-YOLO-Converter"><img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=ArsinShaabani&amp;repo=M3FD-YOLO-Converter&amp;theme=tokyonight&amp;hide_border=true" width="49%" alt="M3FD-YOLO-Converter"/></a>
  <a href="https://github.com/ArsinShaabani/IMSProg"><img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=ArsinShaabani&amp;repo=IMSProg&amp;theme=tokyonight&amp;hide_border=true" width="49%" alt="IMSProg"/></a>
</p>

---

## 👨🏻‍💼 About me / دربارهٔ من

- 🏢 **Founder of ARSINSOFT** — بنیان‌گذار آرسین‌سافت
- 🤖 **AI Master's** student at [MehrAlborz University](https://www.mehralborz.ac.ir) — working on **AI × 3D wearable devices**
- 🦭 Author of **PromptSeal** — prompt/model regression testing, live on [PyPI](https://pypi.org/project/promptseal/)
- 🖥 Building & porting **Qt / C++** native Windows desktop apps
- ⚙️ **Mechatronics & robotics** passion — chips, boards and soldering irons 🔧
- 💬 Ask me about **PC & laptop repair and any electronics**
- 🇮🇷 **Persian localization** — clean RTL, healthy UTF-8 Persian text

<div dir="rtl">

- 🏢 **بنیان‌گذار ARSINSOFT**
- 🤖 دانشجوی ارشد هوش مصنوعی در [دانشگاه مهرالبرز](https://www.mehralborz.ac.ir) — در حال کار روی هوش مصنوعی و دست‌پوش‌های سه‌بعدی
- 🦭 نویسندهٔ **PromptSeal** — تست رگرسیون پرامپت و مدل‌های زبانی (منتشرشده روی PyPI)
- 🖥 ساخت و پورت برنامه‌های دسکتاپ ویندوزی با Qt و ++C
- ⚙️ عاشق مکاترونیک و رباتیک — تراشه، برد و هویه 🔧
- 💬 مشاورهٔ تعمیرات کامپیوتر و لپ‌تاپ و هر نوع الکترونیک
- 🇮🇷 بومی‌سازی فارسی با RTL تمیز و متن فارسی سالم و بی‌نقص

</div>

## 🧰 Tech stack / ابزارها

**🔬 AI & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**🖥 Native & Build**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![MSVC](https://img.shields.io/badge/MSVC-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**🚦 DevOps**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-publishing-3775A9?style=for-the-badge&logo=pypi&logoColor=white)

**⚡ Electronics & Hardware**

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&color=03234B&labelColor=03234B)
![EEPROM / Flash](https://img.shields.io/badge/EEPROM_%2F_Flash_programming-302b63?style=for-the-badge&labelColor=0f0c29)
![CH341A / FT232H](https://img.shields.io/badge/CH341A_%2F_FT232H-302b63?style=for-the-badge&labelColor=0f0c29)
![Schematic & Repair](https://img.shields.io/badge/Schematic_%26_Board_Repair-302b63?style=for-the-badge&labelColor=0f0c29)

---

## 📊 GitHub stats

<p align="center">
  <img align="center" width="49%" src="https://github-readme-stats.vercel.app/api?username=ArsinShaabani&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github" alt="GitHub stats"/>
  <img align="center" width="49%" src="https://streak-stats.demolab.com?user=ArsinShaabani&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

<p align="center">
  <img align="center" width="32.9%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ArsinShaabani&theme=tokyonight" alt="Repos per language"/>
  <img align="center" width="32.9%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ArsinShaabani&theme=tokyonight" alt="Most commit language"/>
  <img align="center" width="32.9%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ArsinShaabani&theme=tokyonight" alt="Productive time"/>
</p>

## 🐍 Contribution graph

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ArsinShaabani/ArsinShaabani/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ArsinShaabani/ArsinShaabani/output/github-contribution-grid-snake.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/ArsinShaabani/ArsinShaabani/output/github-contribution-grid-snake.svg"/>
  </picture>
</p>

---

## 📫 Contact / تماس

<p align="center">
  <a href="mailto:mohammad.reza.shaabani@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://wa.me/989121941368"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
  <a href="https://app.daily.dev/arsinshaabani"><img src="https://img.shields.io/badge/daily.dev-0A0A0A?style=for-the-badge&logo=dailydotdev&logoColor=white" alt="daily.dev"/></a>
  <a href="https://github.com/ArsinShaabani"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

🤝 **Open to collaborate on:** AI × wearable devices · mechatronics · Persian localization · Windows porting

<div dir="rtl">

برای همکاری در حوزهٔ هوش مصنوعی، دستگاه‌های پوشیدنی، مکاترونیک، بومی‌سازی فارسی یا پورت ویندوزی نرم‌افزارها، خوشحال می‌شوم در ارتباط باشم.

</div>

---

<p align="center">
  <b>🇮🇷 Built with 💜 in Tehran · ARSINSOFT</b><br/>
  <sub>“Seal it before you ship it.” — 🦭 <b>PromptSeal</b></sub>
</p>

<p align="center">
  <a href="#-flagship--promptseal">🦭 PromptSeal</a> ·
  <a href="https://github.com/ArsinShaabani/IMSProg/releases/latest">🛠 IMSProg Portable</a> ·
  <a href="https://github.com/ArsinShaabani/promptseal-action">🚦 promptseal-action</a> ·
  <a href="#-contact--تماس">📫 Contact</a>
</p>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=130&section=footer)




