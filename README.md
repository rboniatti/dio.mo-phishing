# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Pré-requisitos

- Um sistema operacional baseado em Linux (como Kali Linux ou Debian).
- O SEToolkit instalado no seu sistema.

Para instalar o SEToolkit no Debian ou Ubuntu, use os comandos:
```bash
sudo apt update
sudo apt install setoolkit
```

---

## 🚀 Passos para clonar um site

### 1️⃣ Passo 1: Iniciar o SEToolkit

1. Abra o terminal e digite o comando abaixo para iniciar o SEToolkit:
   ```bash
   sudo setoolkit
   ```
2. Você verá uma tela inicial como a seguinte:  

![123](https://github.com/user-attachments/assets/1206e3f9-6c24-4da8-995b-c1aa95cdd712)


### 2️⃣ Passo 2: Escolher a opção de Ataque de Engenharia Social

1. No menu principal, escolha a opção **1) Social-Engineering Attacks**.  

### 3️⃣ Passo 3: Escolher a opção "Website Attack Vectors"

1. Em seguida, escolha **2) Website Attack Vectors**.
   
![Captura de tela de 2025-01-24 11-21-03](https://github.com/user-attachments/assets/d5b6c4c6-cea6-407b-a43c-e6b317a2cc56)


### 4️⃣ Passo 4: Escolher a opção "Credential Harvester Attack Method"

1. No próximo menu, selecione **3) Credential Harvester Attack Method**.  

![Captura de tela de 2025-01-24 11-22-48](https://github.com/user-attachments/assets/74b4c3e2-1f08-41f2-93e4-e27318e472cd)


### 5️⃣ Passo 5: Escolher "Site Cloner"

1. Agora, selecione **2) Site Cloner** para clonar um site.

![Captura de tela de 2025-01-24 11-24-08](https://github.com/user-attachments/assets/4d687b6d-9611-4354-b835-f4be3ace5117)


### 6️⃣ Passo 6: Inserir o endereço do site a ser clonado

1. O SEToolkit pedirá para você inserir o URL do site que deseja clonar. Por exemplo:
   ```plaintext
   Enter the URL to clone: http://www.facebook.com
   ```

2. Após inserir o URL, o SEToolkit configurará automaticamente o servidor.

---

### 7️⃣ Passo 7: Acessar o site clonado

1. Quando o processo estiver completo, o SEToolkit exibirá o endereço IP local onde o site clonado está hospedado, algo como:
   ```plaintext
   Credential Harvester is running on http://192.168.0.105
   ```

2. Abra um navegador e acesse o IP fornecido para visualizar o site clonado.

![Captura de tela de 2025-01-24 11-27-32](https://github.com/user-attachments/assets/05707745-056d-4aef-a7f9-8471cc87b9bd)


### Passo 8: Inserção dos dados no site clonado

1. Supondo que o usuário insira seu usuario e senha acreditando se tratar do site verdadeiro

![Captura de tela de 2025-01-24 11-29-39](https://github.com/user-attachments/assets/8775b714-37c8-4fd8-9098-78cf07610a92)

2. Após a inserção das credenciais, o usuario é direcionado para a pagina real.

### Passo 9: Captura dos dados

1. Na maquina onde o site clonado foi hospedado, podemos observar as credenciais inseridas pelo usuário.

![Captura de tela de 2025-01-24 11-34-07](https://github.com/user-attachments/assets/a1cc5f13-c84d-47dc-ad1e-26366a52cd43)

