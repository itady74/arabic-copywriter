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

### الأمر الصحيح · The correct command

```bash
npx skills add itady74/arabic-copywriter --yes
```

> الـ `--yes` مهم. من غيره الـ CLI بيوقفك عند prompt تختار فيه الـ agents يدويًا.
> The `--yes` flag is required. Without it the CLI pauses at an interactive agent-selector prompt.

---

### ايه اللي بيحصل لما تشغّل الأمر · What happens when you run it

```
◇  Source: https://github.com/itady74/arabic-copywriter.git
◇  Repository cloned
◇  Found 1 skill

●  Skill: arabic-copywriter
│  دليل شامل لكتابة تجربة المستخدم (UX Writing) والتصميم المحتوى العربي.

◇  41 agents
●  Installing to: Antigravity, Claude Code, Codex, Cursor, Gemini CLI, OpenCode

◇  Installation Summary
│  .agents/skills/arabic-copywriter
│    universal: Codex, Cursor, Gemini CLI, OpenCode, Amp +3 more
│    symlink → Antigravity, Claude Code

◇  Installation complete
✓  Installed 1 skill
```

الـ CLI بيعمل 3 حاجات تلقائيًا:

1. يـ clone الـ repo من GitHub
2. يحط الملفات في `.agents/skills/arabic-copywriter` (المسار العالمي)
3. يعمل symlinks لـ Antigravity و Claude Code في مساراتهم الخاصة

The CLI automatically:

1. Clones the repo from GitHub
2. Places files in `.agents/skills/arabic-copywriter` (the universal path)
3. Creates symlinks for Antigravity and Claude Code in their dedicated paths

---

### الـ agents المدعومة وطريقة التثبيت · Supported agents & how they connect

| Agent                                         | النوع     | المسار                             |
| --------------------------------------------- | --------- | ---------------------------------- |
| **Antigravity**                               | Symlink   | `.agent/skills/arabic-copywriter`  |
| **Claude Code**                               | Symlink   | `.claude/skills/arabic-copywriter` |
| **Cursor**                                    | Universal | `.agents/skills/arabic-copywriter` |
| **Codex**                                     | Universal | `.agents/skills/arabic-copywriter` |
| **Gemini CLI**                                | Universal | `.agents/skills/arabic-copywriter` |
| **OpenCode**                                  | Universal | `.agents/skills/arabic-copywriter` |
| **Amp, Cline, GitHub Copilot, Kimi Code CLI** | Universal | `.agents/skills/arabic-copywriter` |

> **Universal** = الملفات موجودة فعلاً في الـ path ده.
> **Symlink** = الـ agent بيشوف نفس الملفات عن طريق shortcut من مساره الخاص.

---

### لو ظهرلك prompt التحديد (بدون `--yes`) · If the agent-selector prompt appears

لو نسيت الـ `--yes` وظهر الـ prompt ده:

```
◆  Which agents do you want to install to?
│  ── Universal (.agents/skills) ── always included ────────
│    • Amp  • Cline  • Codex  • Cursor  • Gemini CLI
│    • GitHub Copilot  • Kimi Code CLI  • OpenCode
│
│  ── Additional agents ──────────────────────────────────
│  ❯ ○ Antigravity (.agent/skills)
│    ○ Claude Code (.claude/skills)
│    ...
```

اضغط **Ctrl+C** واشغّل الأمر تاني مع `--yes`.
Press **Ctrl+C** and re-run with `--yes`.

---

### استدعاء المهارة بعد التثبيت · Using the skill after installation

```
/copywriter اكتب رسالة ترحيب لمستخدم جديد
/copywriter راجع نبرة النص التسويقي ده
/copywriter هل الإشعار ده صح؟ "تم تفعيل اشتراكك"
/copywriter review error messages
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

_v1.0.0 · MIT · itady74_
