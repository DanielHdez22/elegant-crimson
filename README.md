# 🎨 Elegant Crimson Theme

<p align="center">
    <img width="1024" height="430" alt="banner" src="https://github.com/user-attachments/assets/258cbf31-d6c2-48a0-860a-1e40c4c36606" />
</p>

A dark theme for Visual Studio Code built around a deep crimson palette — bold, warm, and easy on the eyes during long coding sessions. Every color decision is intentional: the crimson family dominates the syntax, while carefully chosen complementary accents give the most important tokens the emphasis they deserve.

## ✨ Key Features

- **Crimson-dominant palette** — the syntax system is built on a red/crimson base with complementary accents that never break the visual coherence of the theme
- **Semantic color differentiation** — structure keywords (`class`, `function`, access modifiers) use lavender purple; control flow (`if`, `return`) uses bold crimson; constants use teal; variables use golden amber
- **Low eye strain** — background `#101017` avoids pure black; foreground avoids pure white; contrast is tuned for multi-hour sessions
- **Harmonious terminal** — ANSI palette integrated with the editor aesthetic, no jarring color jumps between editor and terminal panels
- **Multi-language ready** — designed and tested across PHP, JavaScript, TypeScript, Vue SFCs, HTML, CSS, and Markdown

## 🎨 Token Color System

| Token Category | Example | Color | Hex |
| :--- | :--- | :--- | :--- |
| **Background** | — | Deep dark blue-black | `#101017` |
| **Foreground text** | — | Off-white | `#ECEFF1` |
| **Keywords** | `if` `return` `foreach` | Bold crimson | `#FF2B59` |
| **Storage** | `class` `function` `public` `private` | Lavender purple | `#C792EA` |
| **Variables** | `$name` `myVar` | Golden amber | `#EEAF27` |
| **Functions** | `myFunction()` | Sky blue | `#7FB4FF` |
| **Strings** | `"text"` | Salmon pink | `#FF89A1` |
| **Constants** | `true` `false` `null` `42` | Teal cyan | `#56D0DD` |
| **Type / Class names** | `MyClass` `InvoiceStatus` | Golden amber | `#EEAF27` |
| **Comments** | `// ...` | Muted blue-gray | `#7A8A9C` |
| **Punctuation** | `;` `.` `()` `{}` | Muted berry red | `#9E3A5A` |
| **Primary accent** | UI elements | Bright crimson | `#FF2E5B` |

## 🚀 Installation

1. Open **Visual Studio Code**
2. Go to the **Extensions** view (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for `Elegant Crimson` by **DanielHdez22**
4. Click **Install**
5. Open **Code > Preferences > Color Theme** and select **Elegant Crimson**

### 📦 Extension Details

| | |
| :--- | :--- |
| **Extension** | `elegant-crimson` |
| **Publisher** | `DanielHdez22` |
| **Version** | `1.0.3` |
| **License** | MIT |

## 📝 Changelog

### 1.0.3
- Differentiated `storage` tokens (`class`, `function`, access modifiers) from control flow keywords — now lavender purple instead of crimson
- Changed `constant` and `variable.other.constant` to teal cyan to distinguish them from string tokens at a glance
- Reduced punctuation visual weight from vibrant red to muted berry red, letting meaningful tokens stand out
- Added specific token rule for PHP `use` statement aliases (`entity.other.alias.php`)

### 1.0.2
- Version bump and banner image update

### 1.0.1
- Initial adjustments and logo refinement

### 1.0.0
- Initial release

## 🤝 Contributing

Found a color that could be improved or a language that needs better token coverage?

- [Open an issue](https://github.com/DanielHdez22/elegant-crimson/issues) describing the problem and what language / token is affected
- Pull requests are welcome — please include a brief description of the visual change and the reasoning behind it

## 🔗 Links

- [Repository](https://github.com/DanielHdez22/elegant-crimson)
- [Report an Issue](https://github.com/DanielHdez22/elegant-crimson/issues)

---

**© 2026 Daniel Hdez (DanielHdez22)**
