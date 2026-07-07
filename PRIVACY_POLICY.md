# Yaqeen Android — Privacy Policy

**Effective date:** July 7, 2026  
**App:** Yaqeen (`app.yaqeen`)  
**Platform:** Android (Google Play)

This Privacy Policy explains how the Yaqeen mobile application (“Yaqeen,” “we,” “our”) handles information when you use the Android app.

For privacy questions, use the **support contact** listed on the Google Play store listing for Yaqeen.

---

## English

### Summary

- **No accounts** — you do not sign in to use Yaqeen.
- **No Yaqeen servers** — we do not operate our own backend that stores your worship or reflection data.
- **On-device first** — settings, prayer activity, reflections, azkar progress, and app selections are stored locally on your device.
- **No ads** — Yaqeen does not show ads or sell your data.
- **Limited analytics** — we use Firebase Analytics to understand aggregate product usage (for example, that a reflection was completed). We do not collect screen content, messages, or browsing history.
- **You can delete everything** — Settings → Privacy → **Reset Yaqeen** removes local app data and returns you to onboarding.

---

### Information stored on your device

Yaqeen stores the following **only on your device** (Room database and DataStore). **This data is not sent to servers we operate.**

| Data | Purpose | Leaves your device? |
|------|---------|---------------------|
| **User settings** | Language, notifications, prayer setup, reflection options, onboarding progress, optional display name | No |
| **Protected apps** (package names you select) | Know which apps should trigger a reflection | No |
| **Reflection events** | Progress, spaced repetition, today stats | No |
| **Azkar / dhikr progress** | Sessions, counters, rhythm streaks | No |
| **Prayer events** | Prayer window reminders, “I prayed” confirmations | No |
| **Prayer location** (if you grant location) | Compute prayer times locally | No |
| **Bundled content progress** | Which reflection/trivia items you have seen | No |

Yaqeen does **not** provide a “download my data” server endpoint because we do not host your data.

---

### What Yaqeen does not collect

Yaqeen is **not** built to collect or transmit:

- Screen content, text fields, or UI node trees
- Keystrokes, screenshots, or recordings
- Messages, contacts, photos, microphone, or camera data
- Passwords or content from other apps
- Precise or background location tracking
- Data sold to advertisers or data brokers

When you enable interception, Yaqeen may read the **foreground app package name** (for example, `com.example.app`) only to decide whether to show a reflection you configured. It does **not** read what is on screen.

---

### Permissions and how they are used

Yaqeen may request the following permissions. You can deny optional permissions and still use other parts of the app.

#### Accessibility Service (for reflection interception)

- **What it is:** Android Accessibility, used only when you enable interception.
- **What we read:** The foreground app package name only.
- **What we do not read:** Screen text, fields, passwords, messages, or any window content (`canRetrieveWindowContent` is disabled).
- **If denied:** Interception is disabled; azkar, prayer times, voluntary reflection, widgets, and settings still work.

#### Usage Access (recommended)

- **Use:** Corroborate which app is in the foreground and honor your cooldown settings.
- **Privacy:** On-device only; not uploaded.

#### Display over other apps (fallback only)

- **Use:** Only if full-screen reflection cannot be shown otherwise.
- **If denied:** Yaqeen uses a full-screen activity instead.

#### Notifications (optional)

- **Use:** Local reminders (prayer, reflection, azkar, daily intention).
- **If denied:** In-app features still work; reminders stay off.

#### Location — coarse (optional, for prayer times)

- **Use:** Calculate prayer times on your device.
- **Not used for:** Tracking your movements or sending location to our servers.

Yaqeen does **not** request camera, microphone, contacts, SMS, or call log access.

---

### Analytics (Firebase)

Yaqeen uses **Google Firebase Analytics** to understand how the app is used in aggregate so we can improve stability and features.

**What may be collected (via Google/Firebase):**

- Aggregate product events (for example: `app_opened`, `onboarding_completed`, `reflection_completed`, `azkar_completed`, `prayer_confirmed`)
- Basic device/app diagnostics (app version, device model, OS version)
- An anonymous analytics identifier assigned by Firebase

**What is not collected via analytics:**

- Screen content or text you see in other apps
- Names of apps you open (beyond what is required locally for interception — that stays on device)
- Your optional preferred name, prayer notes, or reflection answers
- Advertising ID for ad targeting (ads are not used)

Analytics data is processed by **Google** according to [Google’s Privacy Policy](https://policies.google.com/privacy). Data is transmitted over encrypted connections.

You can limit ad-related signals through Android/Google settings. Core worship and reflection data remains on your device regardless of analytics.

---

### Feedback

If you choose **Settings → Send feedback**, Yaqeen opens a **Google Form** in your browser. Any information you submit there (suggestions, bug reports, device details you type) is sent to Google and received by us only as form responses. This is voluntary.

---

### Foreground service

When interception is enabled, Yaqeen may run a foreground service with a visible notification so reflection detection remains reliable on Android. This runs only while interception is on.

---

### Widgets

Yaqeen home-screen widgets read and write local app data (prayer times, dhikr counts, daily reflection) on your device. Widget data is not sent to Yaqeen servers.

---

### Children

Yaqeen is not directed at children under 13, and we do not knowingly collect personal information from children through accounts (there are no accounts). You can remove all local data with **Reset Yaqeen** on the device.

---

### Your choices and control

- **Change permissions:** Android Settings → Apps → Yaqeen → Permissions (and special access toggles for Accessibility / Usage Access).
- **Edit protected apps:** Settings → Reflection Shield.
- **Delete all app data:** Settings → Privacy → **Reset Yaqeen** (cannot be undone).
- **Uninstall:** Removing the app deletes its local data from your device.

---

### Data retention

- **On-device data:** Kept until you reset the app, uninstall Yaqeen, or erase the device.
- **Analytics:** Retained by Google/Firebase according to their retention settings and your Google account controls.
- **Feedback forms:** Retained as long as needed to respond and improve the app.

We do not retain copies of your on-device worship data on our own servers.

---

### Security

Your data is protected by **your device’s security** (screen lock, encryption at rest provided by Android). Keep your device secure. Yaqeen does not transmit your stored reflection or prayer records to our own backend.

---

### Third parties

| Third party | Role |
|-------------|------|
| **Google Play** | App distribution and updates |
| **Google Firebase Analytics** | Aggregate usage analytics |
| **Google Forms** | Optional user feedback submissions |
| **Google Location Services** | Optional coarse location for prayer times (on-device calculation) |

We do not use advertising networks or sell your data.

---

### International users

If you use Yaqeen in the European Economic Area, United Kingdom, or other regions with privacy laws, you may have rights regarding analytics data held by Google. For data stored only on your device, you can access and delete it through the app (Reset Yaqeen) and Android system settings.

---

### Changes to this policy

We may update this Privacy Policy when the app or legal requirements change. We will post the updated policy at the same URL and change the **Effective date**. Continued use after an update means you accept the revised policy.

---

### Contact

For privacy questions related to Yaqeen Android, use the **support contact** on the Google Play store listing.

---

---

## العربية

### الملخص

- **لا حسابات** — لا تحتاج إلى تسجيل دخول لاستخدام يقين.
- **لا خوادم ليقين** — لا نشغّل خادمًا خاصًا بنا لتخزين بيانات عبادتك أو تأملاتك.
- **البيانات على الجهاز أولًا** — الإعدادات، نشاط الصلاة، التأملات، تقدّم الأذكار، وتطبيقاتك المحددة تُخزَّن محليًا على جهازك.
- **لا إعلانات** — يقين لا يعرض إعلانات ولا يبيع بياناتك.
- **تحليلات محدودة** — نستخدم Firebase Analytics لفهم الاستخدام الإجمالي للتطبيق (مثل إكمال تأمل). لا نجمع محتوى الشاشة أو الرسائل أو سجل التصفح.
- **يمكنك حذف كل شيء** — الإعدادات → الخصوصية → **إعادة ضبط يقين** تحذف البيانات المحلية وتعيدك إلى الإعداد الأولي.

---

### المعلومات المخزنة على جهازك

يخزّن يقين البيانات التالية **على جهازك فقط**. **لا تُرسل هذه البيانات إلى خوادم نشغّلها نحن.**

| البيانات | الغرض | هل تغادر الجهاز؟ |
|---------|-------|------------------|
| **إعدادات المستخدم** | اللغة، الإشعارات، إعداد الصلاة، خيارات التأمل، تقدّم الإعداد الأولي، الاسم الاختياري | لا |
| **التطبيقات المحمية** (أسماء الحزم التي تختارها) | معرفة التطبيقات التي يجب أن تُظهر تأملًا | لا |
| **أحداث التأمل** | التقدّم، التكرار المتباعد، إحصائيات اليوم | لا |
| **تقدّم الأذكار/الذكر** | الجلسات، العدادات، سلسلة الانتظام | لا |
| **أحداث الصلاة** | تذكيرات نوافذ الصلاة، تأكيد «صلّيت» | لا |
| **موقع الصلاة** (إذا منحت الإذن) | حساب أوقات الصلاة محليًا | لا |
| **تقدّم المحتوى المضمّن** | العناصر التي شاهدتها أو أكملتها | لا |

---

### ما لا يجمعه يقين

يقين **غير مُصمَّم** لجمع أو إرسال:

- محتوى الشاشة أو حقول النص أو شجرة واجهة المستخدم
- ضغطات المفاتيح أو لقطات الشاشة أو التسجيلات
- الرسائل أو جهات الاتصال أو الصور أو الميكروفون أو الكاميرا
- كلمات المرور أو محتوى التطبيقات الأخرى
- تتبع الموقع الدقيق أو في الخلفية
- بيع البيانات للمعلنين أو الوسطاء

عند تفعيل الاعتراض، قد يقرأ يقين **اسم حزمة التطبيق في المقدمة** فقط (مثل `com.example.app) ليقرر إظهار التأمل الذي ضبطته. **لا يقرأ** ما على الشاشة.

---

### الأذونات وكيفية استخدامها

#### خدمة إمكانية الوصول (لاعتراض التأمل)

- **الغرض:** استخدام إمكانية الوصول في أندرويد فقط عند تفعيل الاعتراض.
- **ما نقرأه:** اسم حزمة التطبيق في المقدمة فقط.
- **ما لا نقرأه:** نص الشاشة أو الحقول أو كلمات المرور أو الرسائل أو أي محتوى نافذة.
- **عند الرفض:** يُعطَّل الاعتراض؛ تبقى الأذكار وأوقات الصلاة والتأمل الاختياري والودجات والإعدادات تعمل.

#### الوصول إلى بيانات الاستخدام (موصى به)

- **الغرض:** التحقق من التطبيق في المقدمة واحترام فترة التهدئة.
- **الخصوصية:** على الجهاز فقط؛ لا يُرفع.

#### العرض فوق التطبيقات الأخرى (احتياطي فقط)

- **الغرض:** فقط إذا تعذّر عرض التأمل بملء الشاشة بطريقة أخرى.

#### الإشعارات (اختياري)

- **الغرض:** تذكيرات محلية (صلاة، تأمل، أذكار، نية يومية).

#### الموقع — تقريبي (اختياري لأوقات الصلاة)

- **الغرض:** حساب أوقات الصلاة على جهازك.
- **لا يُستخدم لـ:** تتبع تحركاتك أو إرسال الموقع إلى خوادمنا.

---

### التحليلات (Firebase)

يستخدم يقين **Google Firebase Analytics** لفهم كيفية استخدام التطبيق بشكل إجمالي لتحسين الاستقرار والميزات.

**ما قد يُجمع (عبر Google/Firebase):**

- أحداث منتج إجمالية (مثل: `app_opened`، `onboarding_completed`، `reflection_completed`، `azkar_completed`، `prayer_confirmed`)
- معلومات أساسية عن الجهاز/التطبيق (إصدار التطبيق، طراز الجهاز، إصدار النظام)
- معرّف تحليلات مجهول من Firebase

**ما لا يُجمع عبر التحليلات:**

- محتوى الشاشة أو النص في التطبيقات الأخرى
- أسماء التطبيقات التي تفتحها (ما عدا الاستخدام المحلي للاعتراض — يبقى على الجهاز)
- اسمك الاختياري أو إجابات التأمل
- معرّف الإعلانات لاستهداف الإعلانات (لا نستخدم إعلانات)

تُعالَج بيانات التحليلات بواسطة **Google** وفق [سياسة خصوصية Google](https://policies.google.com/privacy).

---

### الملاحظات

عند اختيار **الإعدادات → إرسال ملاحظات**، يفتح يقين **نموذج Google** في المتصفح. أي معلومات ترسلها (اقتراحات، أخطاء، تفاصيل الجهاز) تُرسل إلى Google ونستلمها كردود على النموذج. هذا اختياري.

---

### الخدمة الأمامية (Foreground Service)

عند تفعيل الاعتراض، قد يشغّل يقين خدمة أمامية مع إشعار مرئي لضمان موثوقية الكشف على أندرويد. تعمل فقط أثناء تفعيل الاعتراض.

---

### الودجات

تقرأ وتكتب ودجات الشاشة الرئيسية بيانات محلية (أوقات الصلاة، عداد الذكر، التأمل اليومي) على جهازك. لا تُرسل إلى خوادم يقين.

---

### الأطفال

يقين غير موجّه للأطفال دون 13 عامًا. يمكنك حذف كل البيانات المحلية عبر **إعادة ضبط يقين**.

---

### خياراتك وتحكّمك

- **تغيير الأذونات:** إعدادات أندرويد → التطبيقات → يقين → الأذونات (وإمكانية الوصول / بيانات الاستخدام).
- **تعديل التطبيقات المحمية:** الإعدادات → درع التأمل.
- **حذف كل البيانات:** الإعدادات → الخصوصية → **إعادة ضبط يقين** (لا يمكن التراجع).
- **إلغاء التثبيت:** يحذف التطبيق وبياناته المحلية من جهازك.

---

### الاحتفاظ بالبيانات

- **بيانات الجهاز:** حتى إعادة الضبط أو إلغاء التثبيت أو مسح الجهاز.
- **التحليلات:** وفق إعدادات Google/Firebase.
- **نماذج الملاحظات:** حسب الحاجة للرد والتحسين.

---

### الأطراف الثالثة

| الطرف | الدور |
|-------|-------|
| **Google Play** | توزيع التطبيق والتحديثات |
| **Google Firebase Analytics** | تحليلات الاستخدام الإجمالية |
| **Google Forms** | ملاحظات المستخدم الاختيارية |
| **خدمات موقع Google** | موقع تقريبي اختياري لأوقات الصلاة |

لا نستخدم شبكات إعلانية ولا نبيع بياناتك.

---

### التغييرات على هذه السياسة

قد نحدّث هذه السياسة عند تغيّر التطبيق أو المتطلبات القانونية. ننشر النسخة المحدّثة في نفس الرابط ونغيّر **تاريخ السريان**.

---

### التواصل

لأسئلة الخصوصية المتعلقة بيقين أندرويد، استخدم **بيانات الدعم** في صفحة التطبيق على Google Play.

---

© 2026 Yaqeen
