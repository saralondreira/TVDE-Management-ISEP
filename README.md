# 🚖 TVDE Management System (Javolt)

> **Project developed for the 'Algorithms and Object-Oriented Programming' (APOO) course - ISEP 2025/2026.**

This project is a Java-based console application designed to manage a TVDE (Ride-hailing) company. It allows the management of drivers, vehicles, clients, and rides, ensuring data persistence and integrity through file manipulation.

## 👥 The "Javolt" Team
**Lead Developers & Architects:**
* **Sara Londreira**
* Levi Mota

**Contributors:**
* Leonardo
* Micael

## 🛠️ My Role & Contributions
As one of the lead developers, I was responsible for the core system architecture and implementation, specifically:
* **System Core:** Designed the main business logic (`Empresa.java`) to handle complex validations like schedule conflicts and data consistency.
* **User Interface:** Built the dynamic menu system (`Menu.java`) that handles all user interactions and CRUD operations.
* **Data Persistence:** Implemented the file handling system (`Scanner`/`Formatter`) to ensure robust data storage without using databases.
* **Algorithm Optimization:** Developed the logic for filtering available drivers/vehicles based on time slots.

## ⚙️ Key Features
* **Complete CRUD:** Management of Vehicles, Drivers, Clients, Trips, and Reservations.
* **Smart Validation:**
  * Detects schedule conflicts for drivers and vehicles before booking.
  * Prevents deletion of entities with active dependencies.
* **Multi-Company Support:** The system manages multiple companies simultaneously, with isolated file structures.
* **Statistics:** Average trip distance, most requested destinations, and driver income reports.

## 🚀 Technical Implementation
* **Language:** Java
* **Data Structures:** Extensive use of `ArrayList` for dynamic data management.
* **Persistence:** Custom file handling for `.txt` storage.
* **Architecture:** Strict separation between **Entities**, **Business Logic**, and **UI**.

---

# 🇵🇹 Versão em Português

> **Projeto desenvolvido no âmbito da Unidade Curricular de Algoritmia e Programação Orientada a Objetos (APOO) - ISEP 2025/2026.**

Este projeto consiste numa aplicação Java de consola para a gestão de uma empresa de TVDE. Permite gerir condutores, viaturas, clientes e viagens, assegurando a persistência e integridade dos dados através da manipulação de ficheiros.

## 👥 A Equipa "Javolt"
**Desenvolvimento Principal & Arquitetura:**
* **Sara Londreira**
* Levi Mota

**Colaboradores:**
* Leonardo
* Micael

## 🛠️ O Meu Contributo
Como *Lead Developer* neste projeto, liderei a arquitetura e implementação do sistema, focando-me em:
* **Core do Sistema:** Desenho da lógica de negócio (`Empresa.java`) para gerir validações complexas e consistência de dados.
* **Interface de Utilizador:** Construção do sistema de menus (`Menu.java`) que suporta todas as operações CRUD e interação com o utilizador.
* **Persistência de Dados:** Implementação do sistema de leitura/escrita em ficheiros para garantir o armazenamento sem base de dados.
* **Algoritmia:** Lógica de filtragem de recursos (condutores/viaturas) disponíveis por janela temporal.

## ⚙️ Funcionalidades Principais
* **Validação Inteligente:** Deteção de conflitos de horário (sobreposição) e proteção de integridade referencial.
* **Suporte Multi-Empresa:** Gestão isolada de múltiplas empresas com estruturas de pastas independentes.
* **Estatísticas:** Relatórios de faturação, destinos mais frequentes e médias de kms.

---
*Instituto Superior de Engenharia do Porto - Licenciatura em Engenharia Informática*
