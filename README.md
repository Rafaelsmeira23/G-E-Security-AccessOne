# G&E Security - AccessOne

Desenvolvimento do sistema AccessOne, uma solução integrada de controle de acesso para portarias e estacionamentos de condomínios.  
Focado em segurança, praticidade e rastreabilidade, o sistema permite uma gestão eficiente de entradas e saídas, com funcionalidades como registro de encomendas e cadastro de usuários com foto.

---

## Funcionalidades

- Controle de acesso com autenticação de usuários;
- Cadastro e gerenciamento de moradores, visitantes e prestadores;
- Registro e acompanhamento de encomendas;
- Painel administrativo para visualização de logs e relatórios;
- Integração entre as versões Web e Mobile.

---

## Estrutura do Projeto

/web -> Versão web estruturada em MVC (Model, View, Controller);
/mobile -> Versão mobile (arquivos Dart solicitados pelo professor);
/docs -> Documentação técnica e diagramas;
/LICENSE -> Licença de uso MIT;
/README.md -> Documento atual.

---

## Tecnologias Utilizadas

### Web
- PHP 8+  
- MySQL  
- HTML5 / CSS3  
- JavaScript (ES6)  
- Estrutura MVC  

### Mobile
- Flutter (Dart) — requer versão 3.0 ou superior

---

## Como Executar o Projeto

### Versão Web (MVC)
1. Descompacte a pasta `web.zip`.
2. Mova o conteúdo para a pasta `htdocs` do XAMPP (ou equivalente).
3. Inicie o servidor Apache e o MySQL.
4. Importe o banco de dados (arquivo `.sql` dentro da pasta `web`).
5. Acesse no navegador:  
   `http://localhost/accessone/`

### Versão Mobile (Flutter)
1. Certifique-se de ter o Flutter 3.0+ instalado ([guia oficial](https://docs.flutter.dev/get-started/install)).
2. Abra a pasta `mobile` no VS Code ou Android Studio.
3. No terminal, execute:
   ```bash
   flutter pub get
   flutter run
O aplicativo será inicializado no emulador ou dispositivo conectado.

---

## Equipe
- Rafael Santos;  
- Sillas Santana;  
- Matheus Melo;
- Murilo Carneiro  

---

## 🧾 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---

Observações Técnicas

A estrutura MVC foi aplicada na versão Web para separar lógica, apresentação e controle, facilitando manutenção e escalabilidade.

A versão Mobile contém apenas os arquivos .dart conforme solicitado pelo orientador, garantindo compatibilidade com o repositório principal.

O sistema está em desenvolvimento contínuo, com futuras melhorias previstas para integração direta entre módulos Web e Mobile via API REST.
