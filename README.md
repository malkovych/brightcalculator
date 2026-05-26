Calc — яскравий калькулятор з формулою

iOS-додаток (SwiftUI) з повним відображенням поточної формули та проміжної суми.

Можливості





Рядок формули — наприклад 200+2000+1000+300 (3500) дрібним шрифтом



Головний дисплей — поточне число, як у звичайному калькуляторі



8 готових палітр + власні теми з редактором кольорів



Ланцюгові обчислення з пріоритетом × і ÷

Запуск





Відкрийте Calc.xcodeproj у Xcode



Оберіть симулятор або пристрій



Product → Run (⌘R)



Для запуску на реальному iPhone вкажіть свій Development Team у Signing & Capabilities.

Структура

Calc/
  CalcApp.swift
  ContentView.swift
  Models/CalculatorTheme.swift
  Services/CalculatorEngine.swift
  Services/ThemeStore.swift
  Views/CalculatorView.swift
  Views/SettingsView.swift
  Views/ThemeEditorView.swift

Варіанти назви додатку





Formula Glow — підкреслює формулу та яскравий UI



Rainbow Sum — веселка кольорів + підсумок



ChainCalc — ланцюгові обчислення



Vivid Ledger — «яскравий запис» обчислень



Hue & Equals — гра кольорів і знак дорівнює

Назва на домашньому екрані: Bright Calculator (англ. «Яскравий калькулятор»).
