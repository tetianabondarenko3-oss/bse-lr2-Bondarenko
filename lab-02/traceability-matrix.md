# Матриця трасовності (Traceability Matrix)

Нижче представлена матриця трасовності, яка пов'язує функціональні вимоги (FR) з прецедентами використання (UC), задіяними класами та діаграмами послідовності (Sequence Diagram).

| Вимога | Use Case | Класи | Sequence |
| :--- | :--- | :--- | :--- |
| **FR-01** Вибір категорії події | **UC-01** Вибір категорії події | Guest, RegisteredUser, Category | 03-sequence-diagram |
| **FR-02** Генерація карток фактів | **UC-02** Генерація карток фактів | FactCard, Category, AIService | 03-sequence-diagram |
| **FR-03** Перегляд карток | **UC-03** Перегляд карток | Guest, RegisteredUser, FactCard | 03-sequence-diagram |
| **FR-04** Реєстрація користувача | **UC-04** Реєстрація / Вхід | Guest, RegisteredUser, Profile | 03-sequence-diagram |
| **FR-05** Збереження в «Обране» | **UC-05** Збереження в Обране | RegisteredUser, FavoriteList, FactCard | — |
| **FR-06** Редагування профілю | **UC-06** Редагування профілю | RegisteredUser, Profile | — |
| **FR-07** Модерування контенту | **UC-07** Модерування контенту | Administrator, FactCard | — |
| **FR-08** Інтеграція з AI | **UC-08** AI генерація контенту | AIService, FactCard, Category | 03-sequence-diagram |
