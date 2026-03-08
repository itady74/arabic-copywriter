# arabic-copywriter

**دليل احترافي للكتابة الإبداعية وصوت العلامة التجارية العربية**
An expert guide for Arabic brand copywriting — voice, tone, campaigns, and editorial review.

---

## ما هو هذا المشروع؟ · What is this?

مهارة ذكاء اصطناعي تحمّل دليل أسلوب الكتابة الإبداعية العربية الكامل داخل أي محادثة مع الـ AI.
الفرق عن `ux-writing-arabic` إن الـ focus هنا على **صوت العلامة التجارية والمحتوى التسويقي والتحريري**.

An AI skill that loads a complete Arabic brand copywriting guide into any agent conversation.
Unlike `ux-writing-arabic`, the focus here is **brand voice, marketing copy, and editorial content**.

**يُستخدم لـ · Use for:**

- صوت العلامة التجارية والنبرة · Brand voice & tone
- نصوص الحملات والبريد الإلكتروني · Campaign & email copy
- رسائل الترحيب والإعداد · Welcome & onboarding messages
- الإشعارات الفورية · Push notifications
- مراجعة المحتوى تحريريًا · Editorial content review

---

## التثبيت · Installation

### عن طريق الشات (مباشرةً مع الـ agent) · Via agent chat

اكتب في أي محادثة مع Claude / Antigravity / OpenCode / Cursor / Windsurf:
Type in any Claude / Antigravity / OpenCode / Cursor / Windsurf chat:

```
npx skills add itady74/arabic-copywriter
```

الـ agent سيشغّل الأمر ده ويثبّت المهارة تلقائيًا.
The agent will run this command and install the skill automatically.

---

### عن طريق git (قبل النشر / local) · Via git (pre-publish / local)

```bash
# Clone the skill into your project's .skills folder
git clone https://github.com/itady74/arabic-copywriter.git .skills/arabic-copywriter
```

أو اكتب في الشات:
Or type in chat:

```
git clone https://github.com/itady74/arabic-copywriter.git .skills/arabic-copywriter
```

---

### الـ agents المدعومة · Supported agents

| Agent               | طريقة التثبيت                                             |
| ------------------- | --------------------------------------------------------- |
| **Antigravity**     | اكتب في الشات: `npx skills add itady74/arabic-copywriter` |
| **Claude Code**     | اكتب في الشات: `npx skills add itady74/arabic-copywriter` |
| **OpenCode**        | اكتب في الشات: `npx skills add itady74/arabic-copywriter` |
| **Cursor**          | اكتب في الشات: `npx skills add itady74/arabic-copywriter` |
| **Windsurf**        | اكتب في الشات: `npx skills add itady74/arabic-copywriter` |
| **VS Code Copilot** | اكتب في الشات: `npx skills add itady74/arabic-copywriter` |
| **Terminal مباشر**  | `npx skills add itady74/arabic-copywriter`                |

> [!NOTE]
> المهارة لسه مش منشورة على skills.sh. استخدم طريقة git في الوقت الحالي.
> Skill not yet published on skills.sh. Use the git method for now.

---

## الاستخدام · Usage

بعد التثبيت، اكتب في الشات:
After installing, type in chat:

```
/copywriter اكتب رسالة ترحيب لمستخدم جديد
/copywriter راجع نبرة النص التسويقي ده
/copywriter هل الإشعار ده صح: "تم تفعيل اشتراكك"
/copywriter راجع رسائل الخطأ
```

أو بالإنجليزي:

```
/copywriter write a welcome message for a new Arabic-speaking user
/copywriter review tone of this Arabic copy
/copywriter check this push notification: "تم تفعيل اشتراكك"
```

---

## الفرق بين المهارتين · vs. ux-writing-arabic

|               | `arabic-copywriter`       | `ux-writing-arabic`      |
| ------------- | ------------------------- | ------------------------ |
| **الأفضل لـ** | حملات، بريد، محتوى تحريري | نصوص واجهة، microcopy    |
| **المستخدم**  | كتّاب محتوى، مسوّقون      | كتّاب UX، مصممون، مطورون |
| **الاستدعاء** | `/copywriter`             | `/ux-writing-arabic`     |

---

## محتوى المهارة · Skill Contents

| الملف          | المحتوى                    |
| -------------- | -------------------------- |
| `SKILL.md`     | الدليل الكامل — 8 أقسام    |
| `checklist.md` | قائمة مراجعة قبل النشر     |
| `examples.md`  | أمثلة تطبيقية موسعة        |
| `glossary.md`  | مسرد المصطلحات ثنائي اللغة |
| `reference.md` | مرجع سريع للمصطلحات        |

---

## الجمهور المستهدف · Audience

كتّاب محتوى · كتّاب إبداعيون · فرق تسويق · استراتيجيو محتوى · كتّاب UX · مديرو منتجات

---

_v1.0.0 · MIT · arabixuxwriting_
