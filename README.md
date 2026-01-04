# T02 - Grupo D: Sistema de Caja de Ahorros

Este proyecto implementa una API RESTful para la gestión de una cooperativa financiera. Permite la administración de socios, cuentas, transacciones bancarias y cálculo de préstamos.

## 📋 Integrantes

-**Isaias Silva**
-**Alberto Quinde**
-**Gerardo Rocafuerte**
-**Marcelo Jaramillo**

## 🚀 Funcionalidades Principales
* **Gestión de Socios:** Registro automático con generación de cuentas.
* **Transacciones:** Depósitos y Retiros con validación de fondos en tiempo real.
* **Préstamos:** Simulador de crédito con tabla de amortización (sistema francés).
* **Seguridad:** Validación crítica que impide retiros con saldo insuficiente (Error 400).
* **Base de Datos:** Conexión persistente a MySQL en la nube (Aiven).

## 🛠️ Tecnologías
* Python 3.x
* FastAPI
* MySQL (SQLAlchemy)
* Uvicorn
