# 🧪 BDD Login Project

## 🚀 Pasos Rápidos

1. Crea un proyecto Maven: `bdd-login-project`.

2. Estructura:
src/
├── main/java/pages/LoginPage.java
└── test/
├── java/steps/LoginSteps.java
├── java/runners/RunTest.java
└── resources/features/login.feature


3. `login.feature`:
```gherkin
Feature: Acceso a la plataforma bancaria
  Scenario: Login exitoso con credenciales válidas
    Given que el usuario está en la página de login
    When escribe su nombre "admin" y su clave "admin123"
    Then debería ver el mensaje "Bienvenido, admin"
