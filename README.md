
# Phishing-com-Kali-Linux

**Criação de um Phishing com Kali Linux**

1. **Prepare o ambiente**
   - Certifique-se de que está utilizando uma máquina virtual com o Kali Linux instalado.
   - Configure a rede como **Bridged Adapter** para facilitar o acesso à rede.
2. **Acesse o terminal como root**
   - Abra o terminal no Kali Linux.
   - Utilize o comando `sudo su` para obter permissões de superusuário.
3. **Inicie o SET (Social Engineering Toolkit)**
   - Digite o comando `setoolkit` e pressione Enter.
   - Confirme a mensagem de aviso sobre o uso das ferramentas digitando `y` e pressionando Enter.
4. **Navegue pelas opções do SET**
   - Escolha a opção **1 - Social Engineering Attack**.
   - Em seguida, selecione **2 - Web Site Attack Vectors**.
   - Escolha **3 - Credential Harvester Attack Method**.
   - Por fim, opte por **2 - Site Cloner**.
5. **Configure o ataque**
   - O sistema sugerirá o IP da sua máquina. Pressione **Enter** para confirmar.
   - Insira o URL do site que deseja clonar no formato `http://site-alvo.com` e pressione Enter.
6. **Teste o ataque**
   - Copie o IP gerado anteriormente e cole no navegador.
   - A página clonada será exibida, incluindo o campo de login.
7. **Captura de credenciais**
   - Quando as credenciais forem inseridas na página falsa, os dados de login e senha serão capturados automaticamente e exibidos no terminal do Kali Linux.

**Atenção:** Este procedimento é apresentado apenas para fins educativos e de conscientização sobre segurança cibernética. O uso indevido de ferramentas de phishing é ilegal e pode resultar em sérias consequências legais. Utilize esses conhecimentos de forma ética e responsável.

![Captura de tela 2024-12-13 125334](https://github.com/user-attachments/assets/cc9b1684-63b3-4315-a956-3d71b9017f52)
![Captura de tela 2024-12-13 122559](https://github.com/user-attachments/assets/7f0a0dc8-0c98-4b6d-8113-58660267fedb)
