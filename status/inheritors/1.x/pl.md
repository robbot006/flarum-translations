# Polish inherited translations differences

Translations for Polish (`pl`) are inherited from Flarum 1.x, but they can be adjusted
independently after inheritance. This page lists all strings which have the same source string on both
sides, but do not match between them: **5** are translated differently and **5** are
translated only in `pl`. Altogether they cover **5** components.

<!-- {% raw %} -->


## Contents

| Component | Different translations | Missing translations |
| --- | --- | --- |
| `core` | [1](#core) | 0 |
| `flarum-akismet` | [1](#flarum-akismet) | 0 |
| `fof-anti-spam` | 0 | [2](#fof-anti-spam-missing) |
| `fof-masquerade` | [1](#fof-masquerade) | [1](#fof-masquerade-missing) |
| `fof-pwa` | [2](#fof-pwa) | [2](#fof-pwa-missing) |


## Different translations

Each entry contains the English source string, followed by a diff between the translation from Flarum 1.x (`-` line) and the translation from `pl` (`+` line). Changed words are additionally marked as <del>removed</del> and <ins>added</ins> below the diff.


### `core`

#### [`core.forum.change_password.send_button`](https://weblate.rob006.net/translate/flarum2/core/pl/?q=context%3A%3D%22core.forum.change_password.send_button%22)

> Send Password Reset Email

```diff
-Wyślij e-mail resetujący hasło
+Wyślij link do zmiany hasła
```

Wyślij <del>e-mail</del><ins>link</ins> <del>resetujący</del><ins>do</ins> <del>hasło</del><ins>zmiany hasła</ins>


### `flarum-akismet`

#### [`flarum-akismet.admin.akismet_settings.api_key_label`](https://weblate.rob006.net/translate/flarum2/flarum-akismet/pl/?q=context%3A%3D%22flarum-akismet.admin.akismet_settings.api_key_label%22)

> API Key

```diff
-API Key
+Klucz API
```


### `fof-masquerade`

#### [`fof-masquerade.admin.types.boolean`](https://weblate.rob006.net/translate/flarum2/fof-masquerade/pl/?q=context%3A%3D%22fof-masquerade.admin.types.boolean%22)

> Checkbox

```diff
-Checkbox
+Pole wyboru
```


### `fof-pwa`

#### [`fof-pwa.admin.pwa.about.long_name_text`](https://weblate.rob006.net/translate/flarum2/fof-pwa/pl/?q=context%3A%3D%22fof-pwa.admin.pwa.about.long_name_text%22)

> The name of the web application displayed to the user.

```diff
-Nazwa aplikacji wyświetlana użytkownikom.
+Pełna nazwa aplikacji wyświetlana użytkownikom.
```

<del>Nazwa</del><ins>Pełna nazwa</ins> aplikacji wyświetlana użytkownikom.

#### [`fof-pwa.forum.settings.pwa_notifications.access_default_button`](https://weblate.rob006.net/translate/flarum2/fof-pwa/pl/?q=context%3A%3D%22fof-pwa.forum.settings.pwa_notifications.access_default_button%22)

> Opt In

```diff
-Zgadzam się
+Włącz
```


## Missing translations

These strings are translated only in `pl`, so there is nothing to inherit from Flarum 1.x - they could be used to fill the gaps there. Each entry contains the English source string, followed by the translation available only in `pl`.


### `fof-anti-spam` (missing)

#### [`flarum-audit.lib.browser.registration.blocked`](https://weblate.rob006.net/translate/flarum2/fof-anti-spam/pl/?q=context%3A%3D%22flarum-audit.lib.browser.registration.blocked%22)

> Blocked registration for {username} ({email}) from {ip}

```diff
+Zablokowano rejestrację użytkownika {username} ({email}) z {ip})
```

#### [`flarum-audit.lib.browser.user.marked_as_spammer`](https://weblate.rob006.net/translate/flarum2/fof-anti-spam/pl/?q=context%3A%3D%22flarum-audit.lib.browser.user.marked_as_spammer%22)

> Marked {username} as a spammer

```diff
+Oznaczono {username} jako spamera
```


### `fof-masquerade` (missing)

#### [`flarum-audit.lib.browser.masquerade.profile_updated`](https://weblate.rob006.net/translate/flarum2/fof-masquerade/pl/?q=context%3A%3D%22flarum-audit.lib.browser.masquerade.profile_updated%22)

> Updated {username}'s profile fields

```diff
+Zaktualizowano pola profilu użytkownika {username}
```


### `fof-pwa` (missing)

#### [`fof-pwa.admin.pwa.other.share_buttons_label`](https://weblate.rob006.net/translate/flarum2/fof-pwa/pl/?q=context%3A%3D%22fof-pwa.admin.pwa.other.share_buttons_label%22)

> Enable share buttons

```diff
+Włącz przyciski udostępniania
```

#### [`fof-pwa.admin.pwa.other.share_buttons_text`](https://weblate.rob006.net/translate/flarum2/fof-pwa/pl/?q=context%3A%3D%22fof-pwa.admin.pwa.other.share_buttons_text%22)

> If enabled, a "Share" button will be added to discussions, posts, and users.

```diff
+Po włączeniu przycisk „Udostępnij” zostanie dodany do dyskusji, postów i profili użytkowników.
```

<!-- {% endraw %} -->
