🛡️ TryHackMe Challenge Completion 🎉

Bem-vindo ao meu repositório!

📜 Sobre o Desafio
Acabei de concluir um desafio no TryHackMe, uma plataforma de aprendizado prático em cibersegurança. Este repositório é dedicado a compartilhar minha experiência, aprendizados e habilidades adquiridas durante o desafio.

![image](https://github.com/user-attachments/assets/1e68cb52-744f-41f1-a8f1-a3b4282124a9)

🧑‍💻 O que foi abordado?
Durante o desafio, explorei os seguintes tópicos:
🔍 Reconhecimento e coleta de informações.
🛠️ Técnicas análise.
📊 Relatórios detalhados sobre as etapas realizadas.

🛠️ Ferramentas Utilizadas
Aqui estão algumas das ferramentas que utilizei para completar o desafio:
🕵️‍♂️ ExifTool: OSINT de Imagens.
🔧 Google: Interceptação, análise e pesquisas relacionadas ao desafio.
🖥️ Wigle.net: Análise detalhada de dados WIFI em todo o Mundo.

O primeiro desafio consistia em identificar qual era o avatar do usuário. Confesso que, nesse momento, fiquei um pouco apreensivo. No entanto, a plataforma disponibilizou uma imagem: a icônica paisagem do Windows XP. Diante disso, decidi pesquisar no Google sobre como analisar imagens e me deparei com a ferramenta ExifTool.

O ExifTool é uma poderosa ferramenta de linha de comando que permite extrair, editar e gerenciar metadados de arquivos multimídia, como imagens, vídeos e áudios. Com ela, é possível obter informações detalhadas sobre o arquivo, como data de criação, dispositivo utilizado, localização e muito mais. Além disso, a ferramenta suporta uma ampla variedade de formatos de arquivo, incluindo JPEG, PNG e RAW.

Para instalar o ExifTool no Ubuntu, o processo é bastante simples. Basta seguir os comandos abaixo:

![image](https://github.com/user-attachments/assets/c231e74e-7f6c-407a-afbf-32bdb5dd3da9)

Após a instalação, você pode começar a utilizá-lo para analisar imagens. Por exemplo:
Visualizar todos os metadados de uma imagem:

![image](https://github.com/user-attachments/assets/f7863f70-92f6-4855-b9d1-0bd13184059d)

Ao analisar a imagem, deparei-me com diversas informações interessantes. Inicialmente, não consegui identificar o autor imediatamente, mas, ao observar com mais atenção os metadados, notei a presença de um campo de Copyright com o nome "OWoodflint". Intrigado, decidi pesquisar esse nome no Google.

![image](https://github.com/user-attachments/assets/80b147ac-b92d-4186-9616-be9c946ccdde)

Para minha surpresa, a busca revelou uma série de links relacionados ao nome "OWoodflint". Entre eles, encontrei perfis em redes sociais, como Twitter e GitHub, além de um blog pessoal. Essas fontes continham informações valiosas que ajudaram na investigação e forneceram pistas importantes sobre o autor da imagem.

![image](https://github.com/user-attachments/assets/8649e944-c593-4f83-bbb6-98920470b708)

Retomando as perguntas, a primeira era: "Qual é o avatar deste usuário?". Para encontrar a resposta, acessei o perfil do usuário no Twitter (atualmente chamado de X) e identifiquei que a foto de perfil exibida era a imagem de um gato. Assim, a resposta para a primeira pergunta é claramente: "CAT".

![image](https://github.com/user-attachments/assets/8faf7ee0-1ca6-4b6f-b0ce-4eb781ed1e88)

A segunda pergunta envolvia descobrir em qual cidade o autor estava localizado. Durante a análise, observei que ele havia feito a seguinte postagem: 
"Da minha casa eu consigo Wi-Fi grátis ;D
BSSID: B4:5D:50:AA:86:41 - Enlouqueça!" 
Com base nisso, realizei uma pesquisa detalhada e descobri um site chamado Wigle.net, que permite localizar redes Wi-Fi utilizando o BSSID (identificador único do ponto de acesso). Ao inserir o BSSID fornecido na postagem, o site retornou a localização da rede, indicando que o usuário estava em Londres. Portanto, a resposta para a segunda pergunta era claramente: "London".

Com base na pesquisa anterior no site Wigle.net, foi possível responder à terceira pergunta: "Qual é o SSID do WAP ao qual ele se conectou?". Ao analisar os resultados da busca pelo BSSID fornecido, identifiquei o nome da rede Wi-Fi (SSID) associada. O site retornou o seguinte SSID: "UnileverWiFi". Portanto, a resposta para a terceira pergunta é: "UnileverWiFi".

Ao acessar o GitHub de OWoodflint, além de encontrar as respostas para a quarta e quinta perguntas, descobri que ele possui um site pessoal desenvolvido em WordPress. No repositório disponível no GitHub, encontrei o seguinte e-mail: OWoodflint@gmail.com. A quinta pergunta questionava onde esse e-mail foi encontrado. A resposta é clara: no GitHub, mais especificamente no arquivo README.md do repositório people_finder. Portanto, as respostas são:

    Quarta pergunta: O e-mail do autor é OWoodflint@gmail.com.
    Quinta pergunta: Esse e-mail foi encontrado no GitHub.

![image](https://github.com/user-attachments/assets/cffdf894-6be0-4b97-bb5a-1c47a0f69f50)

Ao explorar o site pessoal de OWoodflint, desenvolvido em WordPress, descobri que ele mencionou estar de férias e que viajou para Nova York. Com essa informação, foi possível responder à sexta pergunta: "Para onde ele foi de férias?". Portanto, a resposta para a sexta pergunta é: "New York".

![image](https://github.com/user-attachments/assets/28024ea9-b57a-4a32-a2f3-72b8ba03ade2)

Confesso que a última pergunta, relacionada à senha do usuário, foi a mais desafiadora. Passei cerca de 10 minutos analisando o código-fonte da página principal do site WordPress de OWoodflint até finalmente encontrar a resposta. Na linha 295, havia um texto que se destacava como uma possível senha: pennYDr0pper.!. Portanto, a resposta para a última pergunta é: "pennYDr0pper.!".

![image](https://github.com/user-attachments/assets/355f505e-bf12-4300-9da2-f4e9366a516d)


