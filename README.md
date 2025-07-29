
# 📘 Projeto: Sistema de Aluguel de Carros com Interface | Car Rental System with Interface

## 📌 Português

### 📝 Sobre o Projeto  
Este projeto em Java simula o processo de aluguel de um veículo. O sistema solicita dados do aluguel (modelo, datas, preços) e calcula o valor total a ser pago, incluindo impostos. A estrutura faz uso de programação orientada a objetos e aplica o conceito de **interfaces**, permitindo que diferentes serviços de imposto possam ser injetados e utilizados de forma flexível.

### 🚗 Funcionalidades  
- Leitura de dados de aluguel (modelo, datas, valores)  
- Cálculo de pagamento básico por hora ou dia  
- Aplicação de imposto por meio de uma **interface de serviço de taxa**  
- Exibição de fatura com total e impostos

### 🔧 Como Compilar e Executar  
Requisitos:
- Java 17+  
- IDE (Eclipse, IntelliJ, VS Code) ou terminal

Passos:
```bash
# Compile
javac src/application/Program.java

# Execute
java application.Program
```

### 💡 Exemplo de Uso
```
Entre com os dados do aluguel: 
Modelo do carro: Civic
Retirada (dd/MM/yyyy HH:mm): 25/06/2018 10:30
Retorno (dd/MM/yyyy HH:mm): 25/06/2018 14:30
Preço por hora: 10.0
Preço por dia: 130.0

FATURA:
Pagamento básico: 40.00
Imposto: 8.00
Pagamento total: 48.00
```

### 📂 Estrutura do Projeto
```
src/
├── application/
│   └── Program.java
├── model/entities/
│   ├── CarRental.java
│   ├── Invoice.java
│   └── Vehicle.java
├── model/service/
│   ├── BrazilTaxService.java
│   ├── TaxService.java (interface)
│   └── RentalService.java
```

---

## 📌 English

### 📝 About the Project  
This Java project simulates the car rental process. The system receives rental details (car model, start/end dates, pricing) and calculates the total payment including taxes. It is built using object-oriented principles and applies the concept of **interfaces** to allow flexible tax services.

### 🚗 Features  
- Input of rental data (model, dates, pricing)  
- Payment calculation by hour or day  
- Tax applied via a **tax service interface**  
- Invoice printing with detailed amounts

### 🔧 How to Compile and Run  
Requirements:
- Java 17+  
- IDE (Eclipse, IntelliJ, VS Code) or terminal

Steps:
```bash
# Compile
javac src/application/Program.java

# Run
java application.Program
```

### 💡 Usage Example
```
Enter rental data: 
Car model: Civic
Pickup (dd/MM/yyyy HH:mm): 25/06/2018 10:30
Return (dd/MM/yyyy HH:mm): 25/06/2018 14:30
Price per hour: 10.0
Price per day: 130.0

INVOICE:
Basic payment: 40.00
Tax: 8.00
Total payment: 48.00
```

### 📂 Project Structure
```
src/
├── application/
│   └── Program.java
├── model/entities/
│   ├── CarRental.java
│   ├── Invoice.java
│   └── Vehicle.java
├── model/service/
│   ├── BrazilTaxService.java
│   ├── TaxService.java (interface)
│   └── RentalService.java
```
