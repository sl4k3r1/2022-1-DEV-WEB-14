# LinkU

Um aplicativo Django de reserva de voo escrito em Python, HTML, CSS e Javascript.
Este é o projeto principal para a Programação Web para faculdade 

### Características
1. Os usuários podem criar sua conta de usuário.
2. Os usuários podem reservar passagens de ida e ida e volta.
3. As páginas da Web são responsivas a dispositivos móveis.
4. Os usuários podem cancelar suas passagens reservados.
5. Os usuários podem visualizar suas passagens previamente reservadas (tanto as confirmadas como canceladas).
6. As passagens podem ser baixados como documento pdf.

### Arquivos & Diretórios
  - `capstone` - diretório do projeto.
    - `utils.py` - Contém todas as funções auxiliares do Django usadas em views.py.
    - `urls.py` - Este arquivo lida com todas as URLs do projeto.
  - `flight` - diretório principal do aplicativo.
    - `static` - contém todo o conteúdo estático.
        - `css` - Contém todos os arquivos css para estilizar as páginas da web..
        - `js` - Contém todos os arquivos javascript usados ​​no aplicativo.
        - `img` - Contém todos os arquivos de imagem usados ​​no aplicativo.
    - `templates/flight` Contém todos os modelos de aplicativo.
        - `book.html` - Modelo para mostrar o voo selecionado e ler os dados dos viajantes.
        - `bookings.html` - Modelo para mostrar reservas feitas por um usuário.
        - `index.html` - Modelo de página inicial.
        - `layout.html` - Modelo base para todas as páginas, exceto a página de login e registro.
        - `layout2.html` - Modelo base para página de login e registro.
        - `login.html` - Página do usuário de login.
        - `payment_process.html` - Página após a conclusão do pagamento.
        - `payment.html` - Página de pagamento.
        - `register.html` - Registre a página do usuário.
        - `search.html` - Página de resultados de pesquisa de voos.
        - `ticket.html` - Modelo para impressão de boleto (pdf).
    - `admin.py` - Contém alguns modelos para acesso ao administrador do Django.
    - `models.py` - Todos os modelos usados ​​no aplicativo são criados aqui.
    - `urls.py` - Este arquivo lida com todas as URLs do aplicativo da web.
    - `views.py` - Este arquivo contém todas as visualizações do aplicativo.
    - `constant.py` - Este arquivo contém o valor da taxa cobrada do usuário pela reserva de passagens aéreas.
  - `requirements.txt` - Este arquivo contém todos os pacotes python que precisam ser instalados para executar este aplicativo da web.
  - `manage.py` - Esse arquivo é usado basicamente como um utilitário de linha de comando e para implantar, depurar ou executar nosso aplicativo da web.

### Justificativa

1. Páginas da web responsivas para dispositivos móveis.
2. Modelos mais complexos.
3. Mais interativo porque as páginas da web usam a funcionalidade ajax (por exemplo, fetch) escrita em javascript.
4. Converte o modelo html em pdf para download.
