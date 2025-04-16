# QuestionarrieCognitiveTemplate

## Description

**Local template for a cognitive study questionnaire.**  
This project is a lightweight web-based demo version, developed as a prototype during research work in a neuroscience and physiology lab (unnamed for anonymity).

### Features:
- Login/password system for participant access  
- Instruction screen before questionnaire begins  
- Demographic questions (age, biological sex, gender identity)  
- Various question types:  
  - single choice  
  - multiple choice  
  - numeric input  
  - free text input  
- Embedded video with a follow-up question  
- Final screen with "exit" button  
- All responses saved locally in `responses.json` and `responses.csv`

### Language Support
- Interface and questions available in English and Russian
- Automatically loads `questions_en.json` or `questions_ru.json` based on selected language  
- Language preference is stored in browser `localStorage`


> This version runs fully offline. The next step will be integration with a remote database and analytics dashboard.

---

## Описание

**Локальная болванка опросника для когнитивного исследования.**  
Проект представляет собой лёгкую веб-реализацию, разработанную в рамках научной деятельности в лаборатории нейрофизиологии (название не указывается по этическим соображениям).

### Фичи:
- Авторизация по логину и паролю  
- Инструкции перед началом  
- Демографические вопросы (возраст, биологический пол, гендер)  
- Типы вопросов:  
  - выбор одного варианта  
  - выбор нескольких  
  - числовой ввод  
  - свободный текст  
- Встроенное видео с последующим вопросом  
- Финальный экран с кнопкой выхода  
- Сохранение всех ответов в `responses.json` и `responses.csv`

### Поддержка языков
- Интерфейс и вопросы доступны на русском и английском языках  
- Загружается `questions_ru.json` или `questions_en.json` в зависимости от выбранного языка  
- Язык сохраняется в `localStorage` браузера


> Эта версия полностью автономна. Следующим этапом станет интеграция с удалённой БД и системой анализа.
