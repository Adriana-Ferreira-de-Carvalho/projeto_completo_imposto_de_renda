# **📑 Projeto de Gestão para Declaração de Imposto de Renda (IRPF)**  

Este repositório contém uma planilha em Excel (`projeto_completo_imposto_de_renda.xlsx`) para auxiliar na organização de dados necessários para a declaração do **Imposto de Renda Pessoa Física (IRPF)**.  

---

## **📂 Estrutura do Projeto**  
O arquivo possui **4 planilhas** principais:  

### **1. TITULAR**  
- **Finalidade**: Armazenar informações pessoais do contribuinte.  
- **Campos incluídos**:  
  - Nome, CPF, data de nascimento  
  - Título de eleitor, informações do cônjuge  
  - Endereço (rua, CEP), contatos (telefone, e-mail)  
  - Verificações (alterações em relação ao ano anterior, residente no exterior)  

### **2. INFORMES**  
- **Finalidade**: Consolidar rendimentos bancários.  
- **Funcionalidades**:  
  - Registro de até **3 bancos** (nome do banco, valor atual, anexos)  
  - **Cálculo automático** do total de rendimentos (`=SUM(D11,D16,D21)`)  

### **3. NOTAS**  
- **Finalidade**: Registrar entradas financeiras mensais (extratos, holerites).  
- **Campos**:  
  - Data, categoria e valor de cada transação.  

### **4. BANCOS**  
- **Finalidade**: Lista de referência com códigos e nomes de bancos brasileiros.  
- **Exemplos**:  
  - `001 - Banco do Brasil`  
  - `260 - Nubank`  
  - `341 - Itaú Unibanco`
- **Bancos**: A planilha se encontra oculta, pois a mesma serve como apoio para a planilha de informes.  

---

## **🛠️ Como Usar**  
1. **Preencha a planilha `TITULAR`** com seus dados pessoais atualizados.  
2. **Adicione seus rendimentos** na aba `INFORMES` (inclua comprovantes nos campos `ANEXO 🖇️`).  
3. **Registre transações mensais** na planilha `NOTAS` para controle detalhado.  
4. **Consulte a lista de bancos** na aba `BANCOS` para padronizar os registros.  

---

## **🔧 Melhorias Futuras (Roadmap)**  
- [ ] Adicionar **validação automática de CPF**.  
- [ ] Incluir **cálculo de impostos** com base na tabela da Receita Federal.  
- [ ] Criar uma **versão em Google Sheets** para colaboração online.  
- [ ] Adicionar **exportação em PDF** para envio ao contador.  

---

## **📜 Licença**  
Este projeto é **livre para uso pessoal**. Se for utilizá-lo em projetos comerciais, **cite a fonte**.  

---

### **💬 Contribuições**  
Sugestões e melhorias são bem-vindas! Abra uma **issue** ou envie um **pull request**.  

**📌 Aviso**: Esta planilha não substitui orientação profissional. Consulte um contador para declarações oficiais.  



