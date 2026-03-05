## 🐞 Bug 1 — Vídeo do YouTube não carrega

### Descrição
O vídeo incorporado do YouTube não é exibido na página.  
Ao carregar a página, o player apresenta a mensagem:

"Erro 153 – Erro de configuração do player de vídeo".

### Ambiente
- Navegador: Google Chrome
- Versão: 22H2
- Sistema Operacional: Windows 10 Pro

### Passos para reproduzir
1. Abrir o arquivo HTML no navegador.
2. Navegar até a seção "Inserindo vídeos do YouTube".
3. Aguardar o carregamento do player.

### Resultado esperado
O vídeo do YouTube deve carregar e permitir reprodução.

### Resultado atual
O player exibe erro de configuração e o vídeo não é carregado.

### Evidência
Mensagem exibida pelo player:
Erro 153 – Erro de configuração do player de vídeo. 

<img width="416" height="384" alt="erro 153" src="https://github.com/user-attachments/assets/772f95b4-8ae2-497f-9019-3fa455075e0f" />

---

## 🐞 Bug 2 — Tag iframe do YouTube incompleta

### Descrição
A tag `<iframe>` utilizada para incorporar o vídeo do YouTube está incompleta no código HTML, podendo causar falha de renderização do elemento.

### Ambiente
- Navegador: Google Chrome
- Versão: 22H2
- Sistema Operacional: Windows 10 Pro

### Passos para reproduzir
1. Abrir o arquivo HTML no editor de código.
2. Localizar a seção de incorporação do vídeo do YouTube.

### Resultado esperado
A tag `<iframe>` deve estar completa e corretamente estruturada para garantir o carregamento do conteúdo.

### Resultado atual
A estrutura da tag `<iframe>` apresenta inconsistência no código.

### Evidência
Trecho do código HTML referente ao vídeo do YouTube.
<img width="836" height="144" alt="image" src="https://github.com/user-attachments/assets/0e7de6ac-17d1-491f-a2b7-28430f6ef10f" />


---

## 🐞 Bug 3 — Erro de ortografia no título da página

### Descrição
O título da seção apresenta erro de ortografia.

Texto atual:
"Incerindo videos hospedado localmente"

### Ambiente
- Navegador: Google Chrome
- Versão: 22H2
- Sistema Operacional: Windows 10 Pro

### Passos para reproduzir
1. Abrir a página HTML no navegador.
2. Verificar o primeiro título exibido na página.

### Resultado esperado
O texto deve estar escrito corretamente.

### Resultado atual
O título apresenta erro de digitação.

### Evidência
Título exibido na página com erro ortográfico.
<img width="563" height="265" alt="image" src="https://github.com/user-attachments/assets/cef29a78-0704-49f3-96b7-c41474a36508" />
