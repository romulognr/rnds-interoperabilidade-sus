# 🏥 Portfólio de Interoperabilidade: Integração SUS e RNDS

## 👨‍⚕️ Sobre o Autor
**Rômulo Henrique da Silva Lima**
* Enfermeiro | Especialista em Vigilância em Saúde
* Mestrando em Telessaúde e Saúde Digital (UERJ)

Este repositório demonstra a aplicação prática de conceitos de **Interoperabilidade Semântica** e mapeamento de dados para o padrão **HL7 FHIR R4**, focado nos requisitos da Rede Nacional de Dados em Saúde (RNDS).

---

## 📂 Projetos Desenvolvidos

### 1. Mapeamento de Doenças Crónicas (e-SUS APS)
Modelagem da extração de dados da Ficha de Cadastro Individual.
* **Arquivo:** `condicao_diabetes.json`
* **Cenário:** Mapeamento de condição autorreferida (Diabetes) para o recurso `Condition`.
* **Padrão:** Uso da terminologia **SNOMED-CT (73211009)** para garantir integridade semântica.

### 2. Monitoramento Materno-Infantil (Temporalidade)
Gestão de ciclos de vida e datas críticas.
* **Arquivo:** `monitoramento_gestante.json`
* **Cenário:** Vinculação do estado de gravidez (`Condition`) com a Data da Última Menstruação (DUM).
* **Diferencial:** Utilização do código **LOINC 8665-2** para padronização internacional da data.

### 3. Rastreabilidade de Vacinação (ConecteSUS)
Qualidade de dados para imunização.
* **Arquivo:** `vacina_influenza.json`
* **Cenário:** Envio de registo de vacina com dados completos de farmacovigilância.
* **Destaque:** Inclusão obrigatória de **Lote**, **Via de Administração** (Intramuscular) e **Local de Aplicação** (Deltóide), essenciais para validação na RNDS.

---
*Projeto desenvolvido como portfólio de competências em Arquitetura de Informação em Saúde.*
